# ADK-Agents-Unified-Assignment

This repository contains implementations for key Google AI Agent Development Kit (ADK) codelabs, demonstrating how to build, enhance, and deploy AI agents using ADK and MCP Toolbox for Databases.

## Project Description

The project explores practical AI agent creation and orchestration, based on Google's official codelabs and tutorials, showcasing different stages of AI agent development from prototype to advanced tool-empowered assistants.

- **From Prototypes to Agents with ADK:**  
  Build a conversational AI agent prototype using ADK foundations, including environment setup and basic interactions.

- **Building AI Agents with ADK: Empowering with Tools:**  
  Enhance agents with tool integrations, workflow orchestration, and advanced capabilities to enable dynamic and context-aware behaviors.

- **Build a Travel Agent using MCP Toolbox and ADK:**  
  Develop a domain-specific travel assistant by combining ADK with MCP Toolbox to perform database operations and deliver actionable travel information.

- Vertex AI RAG Agent (ADK)
A compact Retrieval-Augmented Generation (RAG) agent built with Google’s Agent Development Kit (ADK) on Vertex AI. It lets you query document corpora, manage collections, and ingest new files with minimal setup.

### What you can do
- Ask questions over your documents (retrieval + grounded answers)
- List, create, and delete corpora
- Add data from Google Drive URLs or GCS paths
- Inspect corpus stats (counts, metadata, created time)

### Prerequisites
- Google Cloud project with billing enabled
- Vertex AI API enabled
- Python 3.9+ and gcloud CLI installed
- Permissions to create/manage Vertex AI resources

### Using the agent
- **Query Documents** — ask natural-language questions against a selected corpus; the agent retrieves relevant chunks and composes an answer.
- **List Corpora** — see available collections.
- **Create Corpus** — spin up a new, empty corpus with recommended embeddings.
- **Add New Data** — ingest files from Drive/GCS; auto-creates a corpus when needed.
- **Get Corpus Info** — view counts, metadata, timestamps.
- **Delete Corpus** — remove unused corpora (confirmation required).


## Folder Structure

<pre> 
├── Prototype-Agent/
│   ├── agent.py
│   ├── README.md
│   ├── requirements.txt
│   └── prototype_agent_colab.ipynb
│
├── Empowering-Agents-With-Tools/
│   ├── agent_with_tools.py
│   ├── README.md
│   ├── requirements.txt
│   └── tools_agent_colab.ipynb
│
├── Travel-Agent-MCP/
│   ├── travel_agent.py
│   ├── README.md
│   ├── requirements.txt
│   ├── travel_agent_colab.ipynb
│   └── MCP_toolbox_demo/
│       └── README.md
</pre>




## Learning Outcomes

- Understand foundational concepts of Google ADK for AI agent development.  
- Build conversational prototypes and progress them into functionally rich agents.  
- Integrate external tools and APIs to empower AI agents with practical capabilities.  
- Utilize MCP Toolbox to combine relational database querying with conversational AI.  
- Deploy and test agents in cloud environments and local setups.  
- Gain hands-on experience with multi-agent orchestration and dynamic workflow design.

## Technologies Used

- **Google Agent Development Kit (ADK):** Core toolkit for building AI agents.  
- **Model Context Protocol (MCP) Toolbox:** For database querying and structured data integration.  
- **Python 3.8+:** Programming language for all agent implementations.  
- **Google Colab:** Cloud notebook environment for accessible execution and demonstration.  
- **Google Cloud Platform:** Optional backend cloud services and infrastructure.  
- **OpenAI Gemini Models:** Used for natural language understanding and generation where applicable.


## Getting Started

1. Clone this repo:  git clone https://github.com/intimanjunath/ADK-Agents-Unified-Assignment.git
cd ADK-Agents-Unified-Assignment


2. Navigate to each assignment folder and follow the contained README for setup and execution.

3. Use provided Colab notebooks for effortless cloud execution.

4. Configure environment variables as needed in `.env`.

## Video Walkthroughs

Each folder contains links to YouTube video walkthroughs explaining the code YouTube : https://www.youtube.com/playlist?list=PLh8Ujk1E7vYXQPMRCtQa1Yv0qnxRVY87r

## References and Resources

- [From Prototypes to Agents with ADK (Official Codelab)](https://share.google/SedY3WmkMRCEkJrrA)  
- [Building AI Agents with ADK: Empowering with Tools (Official Codelab)](https://share.google/2PaSC2sdeHuNqENjq)  
- [Build a Travel Agent using MCP Toolbox and ADK (Official Codelab)](https://share.google/aTibSpbyEDvVPhIqD)  
- [Google Agent Development Kit Documentation](https://google.github.io/adk-docs/)

