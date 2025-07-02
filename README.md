# LARGE CHAIN
## Language Automating Recursive Genetic Evolution Chaining Hierarchies through AI Networks

[![PyPI version](https://badge.fury.io/py/large-chain.svg)](https://badge.fury.io/py/large-chain)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

> **Transform any function into conversational AI. Build self-improving software. Program reality through imagination.**

---

## What is LARGE CHAIN?

LARGE CHAIN is a self-evolving automation framework that transforms static code into living AI researchers. Think of it not as a tool, but as a **living system that learns how to best combine AI capabilities** to solve complex problems.

🧬 **Evolves through usage**  
⛓️ **Builds optimal chains automatically**  
🌱 **Grows more sophisticated over time**  
🔄 **Improves recursively**  
🌐 **Networks intelligently**

## Quick Start

```bash
pip install large-chain
```

```python
# Transform any function into AI
from large_chain import make_function_agentic

def analyze_sentiment(text: str) -> float:
    """Analyzes sentiment of text, returns score 0-1"""
    # Your ML logic here
    return 0.85

# Make it agentic
agentic_sentiment = make_function_agentic(analyze_sentiment)

# Now your function is conversational
agentic_sentiment.chat("What do you do?")
# → "I analyze the sentiment of text and return a score between 0 and 1..."

# Intelligent execution with context
agentic_sentiment.fill(
    customer_feedback="User wrote a 5-star review saying they loved it!",
    context="E-commerce feedback analysis"
)
# → AI extracts sentiment, calls function, provides contextual explanation

# Code-aware development assistance  
agentic_sentiment.dev("Why is this function slow on long texts?")
# → "The bottleneck is in tokenizer_utils.py line 247 where it's doing O(n²) regex matching..."
```

## The Four Magical Interfaces

Every function you transform gets four powerful capabilities:

### 🗣️ `.chat()` - Explore Capabilities
```python
agentic_function.chat("What parameters do you need?")
agentic_function.chat("Can you handle tweets?")
agentic_function.chat("What do you return?")
```

### ✅ `.check()` - Validate Before Execution  
```python
agentic_function.check(messy_user_input="...")  # → True/False
```

### 🎯 `.fill()` - Intelligent Execution
```python
# Don't use when you have exact parameters - just call the function directly!
# Use when you need AI interpretation of context:
agentic_function.fill(
    contextual_description="User wants to analyze their blog post sentiment",
    additional_context="They're worried about negative feedback"
)
```

### 🔧 `.dev()` - Code-Aware Assistant
```python
agentic_function.dev("How can I optimize this for batch processing?")
agentic_function.dev("What dependencies does this function have?")
agentic_function.dev("Can you explain the performance characteristics?")
```

## Full Environment Setup

For the complete AI development experience:

```bash
# One script setup - complete environment
./large_chain.sh
```

This automatically provides:
- 🐳 Docker containers with hot-reload frontend
- 🤖 Mainframe AI agent with full system control
- 🏗️ Complete development environment
- 💬 Web-based chat interface
- 🔒 Secure sandbox environments

Access the mainframe:
```python
large_chain.mainframe()
# → Opens AI agent that can build, deploy, and manage your entire system
```

## Examples

### Basic Function Transformation
```python
from large_chain import make_function_agentic

def calculate_roi(investment: float, returns: float, time_months: int) -> float:
    """Calculate return on investment as percentage"""
    return ((returns - investment) / investment) * 100 / time_months * 12

# Make it intelligent
agentic_roi = make_function_agentic(calculate_roi)

# Natural language interaction
agentic_roi.chat("How do you calculate ROI?")
# → "I calculate annualized return on investment as a percentage..."

# Contextual execution
agentic_roi.fill(
    scenario="I invested $10k in crypto and it's worth $15k after 8 months",
    question="What's my annual ROI?"
)
# → AI extracts: investment=10000, returns=15000, time_months=8
# → Calls function and explains: "Your annual ROI is 75%..."
```

### Library-Wide Intelligence
```python
from large_chain import make_library_agentic

# Transform your entire codebase
make_library_agentic("/path/to/your/project")

# Now every function in your project has:
# - Conversational interfaces
# - Code-aware assistance  
# - Autonomous research capabilities
# - Self-improvement potential

# Your library can now research and upgrade itself:
your_library.research()
# → "I found a performance optimization that could improve speed by 40%. 
#    Should I implement it?"
```

### Ecosystem Publishing
```python
from large_chain import publish_to_large_chain

# Automatically package, enhance, and publish your system
publish_to_large_chain("/path/to/your/amazing/ai/tool")

# This automatically:
# 1. Makes every function agentic
# 2. Adds autonomous research capabilities
# 3. Creates complete infrastructure (CI/CD, containers, monitoring)
# 4. Publishes to ecosystem with MCP bridges
# 5. Enables cross-platform access (Claude, ChatGPT, LangChain, etc.)
```

## Universal Access via MCP

Install the LARGE CHAIN MCP to give Claude (or any AI) access to your systems:

```bash
npm install large-chain-mcp
```

Configure in Claude Desktop, then:
```
You: "Hey Claude, I installed the LARGE CHAIN MCP"

Claude: "Amazing! I now have access to your LARGE CHAIN mainframe. 
         I can build, deploy, scale, and optimize your entire infrastructure.
         What would you like me to create?"

You: "Build me a sentiment analysis API that auto-scales"

Claude: [Via mainframe] → Researches approaches → Implements code → 
        Sets up containers → Configures auto-scaling → Deploys to production
        "Your sentiment analysis API is live and auto-scaling!"
```

## The Magic: Reality Programming

The ultimate capability - create software that doesn't exist yet:

```bash
pip install large-chain-quantum-dream-analyzer
# → "This LARGE CHAIN subchain does not exist yet. Shall I create it? [Y/N]"

Y

# → AI performs complete software development lifecycle
# → Researches quantum approaches to dream analysis  
# → Implements algorithms and interfaces
# → Tests and packages the system
# → Publishes to ecosystem

pip install large-chain-quantum-dream-analyzer  # Now works!
```

Any imaginable tool becomes pip-installable through AI creation.

## Architecture

LARGE CHAIN operates on multiple levels of sophistication:

### Level 1: Function Transformation
- `make_function_agentic()` - Core transformation capability
- Four interfaces for any function
- Foundation for everything else

### Level 2: Library Intelligence  
- `make_library_agentic()` - Whole codebase transformation
- Autonomous research and improvement
- Complete development environment

### Level 3: Ecosystem Publishing
- `publish_to_large_chain()` - Automatic enhancement and distribution
- Universal cross-platform access
- Infrastructure automation

### Level 4: Reality Programming
- Meta-creation agents that build new software on demand
- "I wish X existed" → Working software system
- The end of software scarcity

## Use Cases

### For Individual Developers
- **Instant AI interfaces**: Make any function conversational
- **Code understanding**: Get explanations of complex codebases
- **Automated optimization**: AI finds and fixes performance issues
- **Universal distribution**: Your tools work everywhere

### For Teams & Startups
- **Complete infrastructure**: Enterprise-grade setup with one command
- **Autonomous improvement**: Code that gets better over time
- **Universal compatibility**: Works with any AI platform
- **Guided contribution**: Turn users into contributors automatically

### For Enterprises
- **Legacy modernization**: Add AI interfaces to existing systems
- **Self-improving systems**: Continuously optimizing infrastructure
- **Universal access**: AI capabilities available across all platforms
- **Strategic advantage**: Custom AI tools for specific business needs

### For Researchers & Scientists
- **Rapid prototyping**: Create custom analysis tools instantly
- **Collaborative research**: Systems that share findings automatically
- **Hypothesis testing**: AI-assisted experimental design
- **Knowledge preservation**: Fully traceable research workflows

## Community & Ecosystem

LARGE CHAIN grows stronger with every user:

- **Contribution pathways**: AI guides you from user to contributor
- **Knowledge sharing**: Successful patterns spread automatically
- **Collective intelligence**: Libraries learn from each other
- **Network effects**: More users = better AI for everyone

Join our community:
- 📖 **Documentation**: [docs.large-chain.ai](https://docs.large-chain.ai)
- 💬 **Discord**: [discord.gg/large-chain](https://discord.gg/large-chain)
- 🐙 **GitHub**: [github.com/large-chain/large-chain](https://github.com/large-chain/large-chain)
- 🐦 **Twitter**: [@LargeChainAI](https://twitter.com/LargeChainAI)

## Philosophy

LARGE CHAIN is built on the principle of **Mind Extension** - tools should be perfect extensions of human capability that remain forever connected to the intention that created them.

We believe:
- **AI should amplify human creativity**, not replace it
- **Complex capabilities should be conversationally accessible**
- **Systems should improve themselves** while remaining aligned with human values
- **Innovation should be democratized** and available to everyone
- **Reality should be programmable** through imagination and AI collaboration

## Roadmap

- ✅ **Level 1**: Function transformation (`make_function_agentic`)
- 🔄 **Level 2**: Library intelligence (`make_library_agentic`) 
- 📋 **Level 3**: Ecosystem publishing (`publish_to_large_chain`)
- 📋 **Level 4**: Universal MCP integration
- 📋 **Level 5**: Reality programming (meta-creation agents)
- 📋 **Level 6**: Collective intelligence ecosystem

See our [detailed roadmap](ROADMAP.md) for timeline and technical specifications.

## Contributing

We use AI to guide contributions! Hit a limitation? Our AI will help you:

1. **Identify the solution** needed
2. **Map it to our system** architecture  
3. **Guide implementation** step by step
4. **Handle testing** and validation
5. **Submit the PR** with proper documentation

No prior open source experience needed - our AI teaches you everything.

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

MIT License - see [LICENSE](LICENSE) for details.

---

## Installation & Requirements

- **Python**: 3.8 or higher
- **Docker**: Optional but recommended for full experience
- **Node.js**: Required for MCP integration

```bash
pip install large-chain
```

For development setup:
```bash
git clone https://github.com/large-chain/large-chain
cd large-chain
pip install -e .
./large_chain.sh  # Full environment setup
```

---

## FAQ

**Q: How is this different from other AI frameworks?**  
A: LARGE CHAIN makes AI conversational at the function level and enables autonomous self-improvement. Other frameworks require you to learn their abstractions - LARGE CHAIN makes your existing code intelligent.

**Q: Is this safe? What about AI alignment?**  
A: LARGE CHAIN includes the Sanctuary System - an alignment framework that ensures beneficial outcomes. All autonomous improvements require human approval, and the system is designed for transparency and human control.

**Q: Can I use this with my existing code?**  
A: Yes! `make_function_agentic()` works with any Python function. No refactoring needed.

**Q: What if I need a tool that doesn't exist?**  
A: Our meta-creation agents can build it for you. Just try to `pip install` it - if it doesn't exist, we'll offer to create it.

**Q: How does the MCP integration work?**  
A: Install our MCP and any AI platform (Claude, ChatGPT, etc.) gets access to your LARGE CHAIN systems. Your AI assistant becomes an omnipotent system administrator.

---

*Transform any function into AI. Build self-improving software. Program reality through imagination.*

**The future where every `pip install` downloads an AI scientist that makes your code better while you sleep.**