you could even enable omnitool on all your functions:

chain_func = "< whatever >"
args = {...}
result = my_func_agentic.call(omnitool=True, chain_to=chain_func, addtl_prompt="and also say yarg matey after you finish", **args)




invoice = GenerateInvoiceLC(customer_id=42,
                            omnitool=True,
                            chain_to="crm.send_slack_alert",
                            addtl_prompt="and append 'yarg matey' at the end")
-->

GenerateInvoiceAgent: calls generate_invoice with customer_id=42 becuase that is all the data here and apparently what this does, then calls omnitool(CrmSendSlackAlertTool, params={...}) # contextualize based on what the response is from generate_invoice, maybe that is already an agentic invoice generator or something, idk. 
-> Responds with dict

{
"generate_invoice": generate_invoice_result,
"omnitool_crm_send_slack_alert": crm_send_slack_alert_result,
"agent_response": agent_response # (just be "OK" or a blocked report if any error occurred)
"error": maybe_error

}



```
def __call__(self, *a, omnitool=False, chain_to=None,
             addtl_prompt="", **kw):

result = agent.run(...)
trace = tracer.create(result)
return trace.map()
```


you dont call omnitool, the agent HAS omnitool and automatically just chains the context because it gets output of its own function and then calls the next one(s), then trace gathers them and trace.map maps them into result pkg, we can even remove that like as above
