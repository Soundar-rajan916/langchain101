# 🦜🔗 LangChain 101

A hands-on learning repository for exploring **LangChain** — from basic concepts to building AI agents with tool integrations.

## 📚 Topics Covered

| # | Notebook | Description |
|---|----------|-------------|
| 01 | [Intro](learing_notes/langchain-01(intro).ipynb) | Getting started with LangChain — creating agents with custom tools (weather, time) using `create_agent` |
| 02 | [Model Integration](learing_notes/langchain-02(Modeal-intergation).ipynb) | Integrating multiple LLM providers — **Google Gemini** and **Groq** — via LangChain's unified interface |
| 03 | [Tools](learing_notes/langchain-03(Tools).ipynb) | Defining custom tools with `@tool`, binding them to models, and implementing **tool execution loops** |
| 04 | [Messages](learing_notes/langchain-04(messages).ipynb) | Understanding LangChain's message types and conversation patterns |
| 05 | [Structured Output](learing_notes/langchain-05(structured-output).ipynb) | Forcing LLMs to return structured data like JSON using Pydantic, TypedDict, and dataclasses |
| 06 | [Middleware](learing_notes/langchain-06(Middleware).ipynb) | Understanding and implementing middlewares in LangChain |

## 🛠️ Tech Stack

- **Python** 3.11+
- **LangChain** — Core framework, Community, and LangGraph
- **LLM Providers** — Google Gemini (`langchain-google-genai`), Google Vertex AI (`langchain-google-vertexai`), Groq (`langchain-groq`)
- **Package Manager** — [uv](https://docs.astral.sh/uv/)

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/Soundar-rajan916/learn-rag.git
cd learn-rag
```

### 2. Install dependencies

```bash
# Using uv (recommended)
uv sync

# Or using pip
pip install -r requirements.txt
```

### 3. Set up environment variables

Create a `.env` file in the root directory with your API keys:

```env
GROQ_API_KEY=your_groq_api_key
GOOGLE_API_KEY=your_google_api_key
```

### 4. Run the notebooks

Open any notebook in the `learing_notes/` folder using Jupyter or VS Code and run the cells interactively.

## 📁 Project Structure

```
Langchain101/
├── learing_notes/
│   ├── langchain-01(intro).ipynb
│   ├── langchain-02(Modeal-intergation).ipynb
│   ├── langchain-03(Tools).ipynb
│   ├── langchain-04(messages).ipynb
│   ├── langchain-05(structured-output).ipynb
│   └── langchain-06(Middleware).ipynb
├── main.py
├── pyproject.toml
├── requirements.txt
├── .env                # API keys (not committed)
├── .gitignore
└── README.md
```

## 📝 License

This project is for personal learning purposes.
