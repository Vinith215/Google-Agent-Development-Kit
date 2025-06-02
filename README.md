# Google-Agent-Development-Kit

Build powerful AI agents using Google's Agent Development Kit (ADK) - the easiest way to create, evaluate, and deploy AI agents with built-in UI and API server!

***🔧 6 Different Agent Types:***

1. *Basic Agent* - Simple question-answering agent
   
2. *Agent with Tools* - Real-time stock price fetching using Yahoo Finance
   
3. *Agent with State* - Memory capabilities to remember previous searches
   
4. *Multi-Tool Agent* - Multiple tools (stock price + company info)

5. *Structured Output Agent* - Consistent, structured responses using Pydantic
  
6. *Callback Agent* - Debug and trace tool usage with before/after callbacks

⭐ **Key Features Covered:***

- Multi-agent system* without complexity
- Visual debugging* and evaluation tools
- Built-in state management* and artifacts
- Session handling* and conversation memory
- Real-time data integration* with custom tools
- One-command deployment* to Google Cloud
- API server setup* with automatic documentation

**📋 What We Build:**

- Stock price checking agent with real-time Yahoo Finance data
- Memory-enabled agent that remembers search history
- Multi-functional agent with price and company info tools
- Structured response agent with buy/sell recommendations
- Debug-friendly agent with callback functions

**🛠️ Setup Requirements:**

- Python environment
- Google API key from aistudio.google.com
- Y-Finance library for stock data
- Pydantic for structured outputs

**💻 Installation Commands:**

 ```bash
- pip install google-adk yfinance
- adk create
- adk run app.py
- adk web
- adk deploy cloud-run app
- adk api-server
 ```

**🌟 Why Google ADK?**

- Simpler than other frameworks* (AutoGen, LangGraph, Crew AI)
- Build in minutes* with just a few lines of code
- Multiple model support* with full transparency
- Visual debugging* and evaluation capabilities
- Three simple steps**: Install ADK → Define Agent → Deploy Anywhere

**🚀 Deployment Options:**

- Vertex AI Agent Engine*
- Google Cloud Run*
- Custom Infrastructure*

**📊 Features Demonstrated:**

- Real-time stock data* fetching and analysis
- Conversation memory* and state management
- Tool interaction visualization* in web UI
- Session management* with unique IDs
- Structured responses* with consistent formatting
- Callback functions* for debugging and monitoring
- API documentation* auto-generation
