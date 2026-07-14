# Sequential Workflow using LangGraph

This repository contains my practice and implementation of a **Sequential Workflow** using **LangGraph** and **Groq LLM**.

The workflow takes raw text as input and processes it through multiple stages before producing the final output.

## Workflow

```
User Input
     ↓
Editor Node
     ↓
Script Writer Node
     ↓
Translator Node
     ↓
Final Output
```

## What I Learned

- Creating a workflow using **StateGraph**
- Defining a shared state with **TypedDict**
- Creating multiple LangGraph nodes
- Connecting nodes using **Edges**
- Understanding **START** and **END** nodes
- Building a **Sequential Workflow**
- Passing data from one node to another through the shared state
- Compiling the graph using `graph.compile()`
- Executing the workflow using `app.invoke()`
- Integrating **Groq LLM** with LangChain
- Loading API keys using `python-dotenv`
- Designing node-specific prompts for different tasks

## Workflow Stages

### Editor Node
- Fixes grammar and spelling
- Improves readability
- Keeps the original meaning

### Script Writer Node
- Converts the edited text into an engaging YouTube-style script
- Makes the content more conversational

### Translator Node
- Converts the script into natural Hinglish
- Maintains the tone and energy

## Tech Stack

- Python
- LangGraph
- LangChain
- Groq
- python-dotenv

## Run

```bash
pip install -r requirements.txt
```

Add your API key to `.env`

```env
GROQ_API_KEY=your_api_key
```

Run the workflow

```bash
python sequential.py
```

---

This repository is part of my LangGraph learning journey where I practice different workflow patterns and Agentic AI concepts.
