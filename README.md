# Second Brain: Personal Context Vault

A lightweight, self-hosted template to compile your biography, operating manual, and professional playbooks into a database. Fully compatible with Obsidian.

---

## 📖 New to the Vault? Read the Complete Guide
If you are setting this up for the first time, check out our **[Getting Started Guide (GETTING_STARTED.md)](GETTING_STARTED.md)** for:
1. **The 2-Minute Conversational Setup:** The easiest way to get started—simply clone the repository and run **Gemini CLI** directly in the folder to talk, feed articles, add frameworks, and experiment!
2. **Real-World Examples:** Featuring real-world examples (e.g., *Dinesh Pai, Head of Investments at Rainmatter & VP of Business Analytics & Investments at Zerodha*) showing exactly how to populate your biography, Rainmatter patient capital playbooks, and curated summaries.
3. **Optional Obsidian & Web UI Integration:** Visualizing your notes as an interactive 3D neural map in Obsidian, or loading your vault into Claude Projects and ChatGPT Custom GPTs.

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

## 🛠️ Easiest Quick Start (2-Minute Setup)

The absolute simplest way to build, feed, and interact with your personal context vault is **conversationally through the command line** using **Gemini CLI**.

### 1. Download & Launch
Clone this repository and launch Gemini CLI directly inside your new local folder:
```bash
git clone https://github.com/paidinesh7/Second-Brain.git
cd Second-Brain
gemini
```

### 2. Talk to Feed and Experiment!
Speak naturally to the CLI to initialize your files, append frameworks, write articles, or query your playbooks. The CLI automatically handles the Markdown formatting, file editing, and file reads for you.
*   **Initialize:** *"Initialize my profile. My name is Dinesh Pai, Head of Investments at Rainmatter..."*
*   **Feed Curation:** *"Feed this article on 7 Powers by Hamilton Helmer to my curation..."*
*   **Audit Playbook:** *"Add a GST corporate governance screen to my investment playbook..."*
*   **Interact & Query:** *"Based on my profile.md writing style, draft a response to this pitch..."*

---

## 🎨 Optional: Visualize in Obsidian

If you want to view your Second Brain notes as an interactive, connected 3D neural map:
1.  Download and install **[Obsidian](https://obsidian.md/)** (free, offline Markdown editor).
2.  Select **"Open folder as vault"** and choose your cloned `Second-Brain` directory.
3.  Open `Dashboard.md` — this is your master command center.
4.  Press **`Ctrl + G`** (or **`Cmd + G`** on Mac) to open the interactive **3D Graph View** and see how your nodes connect.

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
