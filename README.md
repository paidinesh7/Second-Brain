# Second Brain: The Sovereign Personal Context Vault

A lightweight, self-hosted, and bidirectional Markdown template to compile your biography, operating manual, and professional playbooks into an AI-ready personal database. Fully compatible with Obsidian.

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

## 🧠 Running Your "Digital Twin"

To ground any LLM in your exact verified context, upload your customized Markdown files (`profile.md`, `investment.md`, `curation.md`) and paste this prompt:

```text
Act as my personal digital twin. Ingest these context files to understand exactly how I write, make decisions, handle risk, and evaluate opportunities. Ground all subsequent drafts, emails, and analyses strictly in these playbooks.
```

---

## 📜 License
Licensed under the MIT License. Feel free to fork, customize, and share.
