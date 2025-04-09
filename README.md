# Google Agents ADK

Docs: [https://google.github.io/adk-docs/](https://google.github.io/adk-docs/)

Generate Google Gemini API Key (Free): [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)

# How to run

```bash
export GOOGLE_API_KEY="your-api-key-here"
```

```bash
pip install google-generativeai google-adk pydantic
```

```bash
python -m venv adk-env
source adk-env/bin/activate
```

```bash
python run main.py
```

# What to do

**Agent 1:** Fine-tune with current data (tools)

**Agent 2:** Call Model LLM using Google Gemini API.

**Objective:** Run code and compare 2 agents to ask the capital and population of countries around the world.
