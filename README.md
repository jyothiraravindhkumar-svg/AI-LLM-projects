# AI-LLM-projects

A collection of projects exploring LLM application development with LangChain and OpenAI — covering prompt engineering, chains, and building an interactive Q&A interface with Streamlit.

## Projects

### 1. [LangChain Fundamentals](./langchain-fundamentals)
Hands-on exploration of core LangChain building blocks: LLM wrappers, prompt templates, `LLMChain`, `SimpleSequentialChain`, `SequentialChain`, chat models with `ChatOpenAI`, and custom output parsers.

**Concepts covered:** prompt templating, chaining multiple LLM calls, structured output parsing, HuggingFace Hub inference.

### 2. [Streamlit Q&A Chatbot](./streamlit-qa-chatbot)
A simple web app that takes a user question and returns an LLM-generated answer, built with Streamlit and LangChain's OpenAI wrapper.

**Concepts covered:** wrapping an LLM call in an interactive UI, basic app structure with Streamlit.

## Tech Stack
- Python
- LangChain
- OpenAI API
- HuggingFace Hub
- Streamlit

## Setup
```bash
git clone https://github.com/jyothiraravindhkumar-svg/AI-LLM-projects.git
cd AI-LLM-projects
pip install -r requirements.txt
```
Each subfolder has its own `requirements.txt` — install from within that folder if you only want to run one project.

You'll need an OpenAI API key. Set it as an environment variable rather than hardcoding it:
```bash
export OPENAI_API_KEY="your-key-here"
```

## Status
Learning/exploration projects — actively being extended toward more advanced agent and tool-calling patterns.
