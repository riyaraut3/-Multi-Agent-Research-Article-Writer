# 🧠 Multi-Agent Research Article Generator

 Made Multi-Agent Research Article Generator using CrewAI and openAI. Specialized agents such as a Research Agent, Writer Agent, and Editor Agent that work together to collaboratively research a topic and generate a complete, structured article. This project is part of my learning journey into agentic AI, where I’m exploring how autonomous agents can reason, communicate, and collaborate like a real team.


## 🚀 Key Features

- 🤖 Autonomous agents with unique roles (Researcher, Writer, Editor)
- 🪄 Seamless integration with LLMs (OpenAI, Anthropic, etc.)
- 📑 Complete research-to-article generation pipeline
- 🔧 Modular, customizable structure

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/multi-agent-research-writer.git
cd multi-agent-research-writer
```

### 2. Install Dependencies

Make sure you’re using Python 3.9+:

```bash
pip install crewai==0.28.8 crewai_tools==0.1.6 langchain_community==0.0.29
```

### 3. Configure API Keys

By default, the system uses **OpenAI**'s GPT models. Set your key like this:

```bash
export OPENAI_API_KEY="your-openai-key"
```

You can also modify the code to use other LLMs like **Anthropic**, **Cohere**, or **local models** via Langchain.

---

## 🧠 How It Works

1. Agents are initialized with specific roles and goals.
2. Tasks are defined to guide agent behavior and collaboration.
3. The `Crew` object coordinates execution and output.
4. Final result: a high-quality research article on your chosen topic.

---

## 📁 Files

- `multiagents_research_write_article.ipynb`: Main notebook with agent definitions, task setup, and execution logic.

---

## 🌐 Customization Ideas

- Modify agent prompts to fit new domains (e.g., finance, medicine, education).
- Add tools like web search or citation retrieval using Langchain integrations.
- Extend with memory, history, or multi-turn planning.

---

## 💬 Let’s Connect

If you're exploring **agentic AI** too or want to extend this system, feel free to reach out or contribute ideas!

