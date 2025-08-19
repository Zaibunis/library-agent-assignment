# 📚 Library Assistant using OpenAI Agents SDK

This project is a **Library Assistant** built with the **OpenAI Agents SDK**.  
It allows users to interact with a virtual librarian to:

- 🔍 Search for books  
- 📖 Check book availability (only for registered members)  
- 🕒 Get library timings  
- 🛡 Ignore non-library related questions  

---

## 🚀 Features
- **Agent-based architecture** with guardrails for safe interactions  
- **Member validation** for restricted features  
- **Dynamic instructions** to adapt responses  
- **Context sharing** for smooth multi-step queries  
- **Built-in tools** for searching and availability checking  

---

## ⚙️ Tech Stack
- **Python 3.10+**  
- **OpenAI Agents SDK**  
- **UV (dependency manager)**  

---

## 📦 Setup & Installation

Clone the repository:

```bash
git clone https://github.com/Zaibunis/library-agent-assignment.git
cd library-agent-assignment
```

Create a virtual environment:

```bash
uv init library-agent
cd library-agent
```

Install dependencies:

```bash
uv add openai-agents python-dotenv
```

## Activate it:

On Linux/Mac
```bash
source .venv/bin/activate
```

On Windows
```bash
.venv\Scripts\activate
```
---

## ▶️ Usage
Run the assistant:

```bash
uv run main.py
```

---

## 💡 Example Queries

Try asking the assistant:

1. "Harry Potter book availability?"

2. "Is 'The Great Gatsby' available for member ID 123?"

3. "What are the library timings today?"

---

Made with ❤ by [Faria Mustaqim](https://github.com/Zaibunis)


