# Second Brain: The Sovereign Personal Context Vault

A lightweight, self-hosted, and bidirectional Markdown template to compile your biography, operating manual, and professional playbooks into an AI-ready personal database. Fully compatible with Obsidian.

---

## 📖 New to the Vault? Read the Complete Guide
If you are setting this up for the first time, check out our **[Getting Started Guide (GETTING_STARTED.md)](GETTING_STARTED.md)** for:
1. **Interactive Step-by-Step Setup** of your local vault.
2. **Real-World Examples** (e.g., *Dinesh Pai, Head of Investments at Rainmatter & VP of Business Analytics & Investments at Zerodha*) showing exactly how to populate your personal identity, decision playbooks (featuring Rainmatter's *Patient Capital* rules), and curated summaries.
3. **⚡ CLI Power Integration** showing how you can use terminal commands and shell functions to keep feeding and experimenting with your vault on the fly.
4. **LLM Connection Guides** for Claude Projects, ChatGPT Custom GPTs, Obsidian community plugins (Copilot, Smart Connections), and 100% offline local LLMs via Ollama.

---

## 🧭 Why Use a Sovereign Context Vault?

Traditional personal knowledge management is locked inside fragmented SaaS databases, or easily hallucinated by LLMs. This repository offers a decentralized, plain-text alternative.

*   **LLM Native:** Plain-text Markdown is the optimal input structure for advanced LLMs (Claude, GPT, Gemini) and local models (Llama via Ollama). 
*   **Zero Vendor Lock-In:** You own your raw text files. They reside in a simple directory under your local Git control.
*   **Bidirectional Connections:** Uses double-bracket linking (`[[linking]]`) to let you visualize how your life operations, investment models, and intellectual readings physically intersect.

---

## 📂 Repository Structure

The vault is divided into modular, pre-structured files ready to load:

| File Name | Purpose | Target Action |
| :--- | :--- | :--- |
| **`Dashboard.md`** | Central mind map and home screen | Open as your primary index |
| **`profile_template.md`** | Biography, operating tenets, and writing style | Rename to `profile.md` |
| **`playbook_template.md`** | Investment checklists and the **Half-Kelly Sizing Rule** | Rename to `investment.md` |
| **`curation_template.md`** | Summaries and index of books/essays you live by | Rename to `curation.md` |

---

## 🛠️ Quick Start (3-Step Setup)

### 1. Clone the Vault
Clone this repository directly into your local directory:
```bash
git clone https://github.com/paidinesh7/Second-Brain.git
```

### 2. Customize the Templates
Open the template files in any text editor and customize the placeholders (e.g., `[Your Name]`, `[Rule 1]`):
*   Rename `profile_template.md` ➔ **`profile.md`**
*   Rename `playbook_template.md` ➔ **`investment.md`**
*   Rename `curation_template.md` ➔ **`curation.md`**

### 3. Load in Obsidian
1.  Download **[Obsidian](https://obsidian.md/)** (free, offline Markdown editor).
2.  Select **"Open folder as vault"** and choose your cloned `Second-Brain` directory.
3.  Press **`Ctrl + G`** to open the **interactive 3D Graph View** and watch your notes automatically connect.

---

## 🎨 Recommended Graph Group Colors

To color-code your neural mind map, open the **Graph Settings** (Gear icon on your graph screen) ➔ **Groups** ➔ **New group**, and add these search queries:

*   🔴 **`file:Dashboard`** – The master index core.
*   🟣 **`path:profile`** – Your biography, tenets, and writing voice.
*   🟢 **`path:investment`** – Active playbooks, operations, and risk rules.
*   🔵 **`path:curation`** – Curated intellectual summaries and mental models.

---

## 🧠 Connecting Your LLM of Choice

You can ground any advanced AI model in your exact verified context files (`profile.md`, `investment.md`, `curation.md`). There are three main ways to connect your LLM:

### 1. Web UI Upload (No-Code)
Upload your customized files directly as **Project Knowledge** in Claude Projects (Claude Pro) or **Knowledge Files** in Custom GPTs (ChatGPT Plus), and prompt:
```text
Act as my personal digital twin. Ingest these context files to understand exactly how I write, make decisions, handle risk, and evaluate opportunities. Ground all subsequent drafts, emails, and analyses strictly in these playbooks.
```

### 2. Obsidian Community Plugins (Integrated Sidebar)
Install community plugins like **Copilot for Obsidian** or **Smart Connections** to index your local vault files and chat with your Second Brain directly from your note-taking environment.

### 3. Offline & Local LLMs (100% Secure & Private)
Run local models like Llama 3 via **Ollama** on your own computer. Pipe your files directly in your terminal, or connect Obsidian Copilot to your local Ollama port (`localhost:11434`) for a fully offline AI companion.

> 💡 For detailed, step-by-step instructions and command-line scripts for each of these options, check out the **[Connecting Your LLM section in GETTING_STARTED.md](GETTING_STARTED.md#-step-3-connecting-your-llm-of-choice)**.

---

## 📜 License
Licensed under the MIT License. Feel free to fork, customize, and share.
