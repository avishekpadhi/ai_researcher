# 🧠 AI Research Agent

A multi-agent research system that uses LLM-powered agents to plan, execute, and aggregate research tasks.

---

## 🚀 How it works

* **Planner Agent** → Creates a structured research plan
* **Coordinator Agent** → Breaks plan into subtasks
* **Sub-Agents** → Execute each subtask independently using tools (Firecrawl MCP)
* Results are combined into a final report

---

## ⚡ Key Idea

The system simulates a **team of researchers** by:

* Decomposing problems
* Running subtasks in parallel
* Aggregating structured outputs

---

## ⚠️ Note on Models & Errors

This project uses **Hugging Face Inference models via external providers**.

* Some models (e.g. advanced reasoning models) are **not available in free serverless mode**
* They require **paid/dedicated endpoints**
* Due to this, you may encounter **inference errors** when running the project without provider access

👉 This is a known limitation and currently being worked on

---

## 🛠️ Stack

* Python
* smolagents
* Hugging Face Inference API
* Firecrawl MCP

---

## 👤 Author

Abhishek Padhi
