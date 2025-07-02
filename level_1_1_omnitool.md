you could even enable omnitool on all your functions:

chain_func = "< whatever >"
args = {...}
result = my_func_agentic.call(omnitool=True, chain_to=chain_func, addtl_prompt="and also say yarg matey after you finish", **args)




invoice = GenerateInvoiceLC__agentic_call__(customer_id=42,
                            omnitool=True,
                            chain_to="crm.send_slack_alert",
                            addtl_prompt="and append 'yarg matey' at the end")
-->

calls generate_invoice with customer_id=42 becuase that is all the data here and apparently what this does, then calls GenerateInvoiceAgent with that info (we just made an invoice for customer 42), then calls omnitool(CrmSendSlackAlertTool, params={...}) # contextualize based on what the response is from generate_invoice, maybe that is already an agentic invoice generator or something, idk. This is a terrible example because you dont need the agent to generate anything in between the calls, they could easily just chain normally
-> Responds with dict

{
"generate_invoice": generate_invoice_result,
"omnitool_crm_send_slack_alert": crm_send_slack_alert_result,
"agent_response": agent_response # (just be "OK" or a blocked report if any error occurred)
"error": maybe_error

}



```
def fill(self, *a, omnitool=False, chain_to=None,
             addtl_prompt="", **kw):

result = agent.run(...)
trace = tracer.create(result)
return trace.map()
```


you dont call omnitool, the agent HAS omnitool and automatically just chains the context because it gets output of its own function and then calls the next one(s), then trace gathers them and trace.map maps them into result pkg, we can even remove that like as above
