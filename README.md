# 🐍 Python IDE

An in-browser Python IDE with AI-powered code assistance. Write, run, and debug Python code directly in your browser — no server required.

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![WebAssembly](https://img.shields.io/badge/WebAssembly-Pyodide-purple?logo=webassembly)
![AI](https://img.shields.io/badge/AI-WebLLM-green?logo=openai)


## ✨ Features

- **🖥️ In-Browser Python Execution** — Runs entirely client-side using Pyodide (WebAssembly)
- **🤖 AI Code Assistant** — Built-in LLM for code generation and assistance (like VS Code Copilot)
- **📦 Package Installation** — Install Python packages directly in the browser
- **🎨 Monaco Editor** — VS Code's editor with Python syntax highlighting
- **🌓 Light/Dark Theme** — Toggle between themes
- **💻 Mac-style Terminal** — Beautiful, resizable terminal output
- **⚡ Zero Backend** — Everything runs in your browser

## 🚀 How to Use

### 1. ✏️ Write Code
Type your Python code in the Monaco editor. Supports syntax highlighting, auto-indent, and minimap.

### 2. 📦 Install Packages
```
Type package name (e.g., numpy, pandas) → Click "Install Package"
```

### 3. ▶️ Run Code
- Click the **Run Code** button, or
- Press `Ctrl+Enter` (Windows/Linux) or `Cmd+Enter` (Mac)

### 4. 🤖 Use AI Assistant
1. Click the **✨** button to open AI panel
2. Select a model (Qwen2.5 Coder recommended)
3. Click **Load Model** (first time downloads ~500MB-2GB)
4. Ask AI to write code
5. Click **+ Insert** to add generated code to editor

## 🧠 Available AI Models

| Model | Size | Best For |
|-------|------|----------|
| Qwen2.5 Coder 0.5B | ~300MB | Fastest responses |
| Qwen2.5 Coder 1.5B | ~800MB | Balanced (recommended) |
| Qwen2.5 Coder 3B | ~1.5GB | Better code quality |
| Qwen2.5 Coder 7B | ~3GB | Best quality |
| Llama 3.2 1B/3B | ~500MB-1.5GB | General purpose |

## 🛠️ Tech Stack

- **Pyodide** — Python runtime compiled to WebAssembly
- **Monaco Editor** — VS Code's code editor
- **WebLLM** — In-browser LLM inference
- **HTML/CSS/JavaScript** — Frontend

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+Enter` | Run code |
| `Tab` | Indent |
| `Escape` | Close modals |

## 📁 Project Structure

```
pythonplayground/
├── index.html    # Main application (single file)
├── LICENSE       # MIT License
└── README.md     # This file
```

## 🌐 Browser Support

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ⚠️ Requires WebAssembly and WebGPU support for AI features



**Created by [Raja Yadav](mailto:raja.yadav1108@gmail.com)** • [LinkedIn](https://linkedin.com/in/raja-yadav-ab38a0242) • [GitHub](https://github.com/rajayadav08)
