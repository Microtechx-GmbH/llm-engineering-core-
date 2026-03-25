# LLM Engineering Core


# 🚀 Basic Setup 

To start LLM engineering, you only need:

* **Ollama** → runs LLMs locally
* **VS Code** → for coding
* **UV** → dependency & environment manager

Optional:

* **Cursor IDE** → AI-powered coding (alternative to VS Code)

---

# 🤖 Ollama Setup (Local LLMs)

### ✅ What is Ollama?

Ollama lets you **run LLMs locally** on your system (no API needed).

### ✅ Steps:

1. Install Ollama
   👉 https://ollama.com

2. Run a model:

```bash
ollama run llama3
```

3. Pull model manually:

```bash
ollama pull llama3.2
```

### 💡 Key Idea:

* No internet needed after download
* Good for privacy + fast testing

---

# 💻 VS Code Setup

If someone doesn't want Cursor, **VS Code is enough**.

### Install:

👉 https://code.visualstudio.com/

### 🔌 Important Extensions:

* Python (Microsoft)
* Jupyter
* Code Runner

---

# ⚡ Cursor IDE (Optional but Powerful)

### ✅ What is Cursor?

* AI-powered IDE (like VS Code + ChatGPT inside editor)
* Helps in writing, fixing, and understanding code faster

### Install:

👉 https://cursor.sh/

---

# 📦 UV (Fast Python Package Manager)

### ✅ What is UV?

* Super fast alternative to `pip` and `venv`
* Used for managing environments and dependencies

# ⚙️ Common UV Commands

### Create virtual environment:

```bash
uv venv
```

### Activate environment:

```bash
source .venv/bin/activate      # Linux/Mac
.venv\Scripts\activate         # Windows
```

### Install packages:

```bash
uv pip install <package>
```

### Install from requirements:

```bash
uv pip install -r requirements.txt
```

### Sync dependencies:

```bash
uv sync
```

---

