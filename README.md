# Second Brain: The Personal Context Vault & Allocator Playbook

> *An open-source, plain-text, and bidirectional Markdown template to build a permanent, AI-ready "second brain." Grounded in your own verified context, portable across any LLM, and fully compatible with Obsidian.*

---

## Why Build a Sovereign Second Brain?

In the age of AI, traditional personal branding is messy, scattered, and easily hallucinated by LLMs. Relying on centralized SaaS note-taking apps or proprietary databases locks your mind in an extractive cage.

The **Sovereign Second Brain** solves this. It is a modular, self-hosted database built entirely on plain-text **Markdown (`.md`)** files that organizes your biography, writing voice, operating manual, and professional playbooks. 

### 🚀 The Sovereign Advantages:
1.  **Native AI Comprehension:** Markdown is the universal language of LLMs. Any modern AI system (Claude, GPT, Llama, Gemini, or Perplexity) can instantly ingest these files to write in your exact voice, audit decisions against your playbooks, or synthesize your career with 100% precision.
2.  **No Vendor Lock-In:** You own your files. They reside in a simple directory on your computer, under your complete control. If a newer, faster AI model comes out next month, you simply point it at your Markdown folder and it is instantly trained on your mind.
3.  **Visual Associative Thinking:** Fully compatible with **Obsidian** (the local, free Markdown editor). Using bidirectional double-bracket links (`[[linking]]`), the app automatically generates a gorgeous, interactive 3D neural map of how your ideas, playbooks, and readings physically intersect.

---

## Repository Structure

When cloned, this repository provides a clean, pre-structured "Second Brain" vault ready to load into Obsidian:

```
Second Brain/
├── README.md               <-- The Master Setup & Operations Manual (You are here)
├── Dashboard.md            <-- The Central Mind Map Hub (Your home screen)
├── profile_template.md     <-- Who you are & your writing/social style (Voice Prompt)
├── playbook_template.md    <-- Your Sizing, Sourcing & Diligence (Half-Kelly Sizing Rule)
└── curation_template.md    <-- Your Book Summaries & Curation table
```

---

## Quick Start Guide (How to use this)

### Step 1: Clone this Repository
Clone this repository directly into your local workspace folder:
```bash
git clone https://github.com/[your-username]/second-brain.git
```

### Step 2: Fill In Your Context (Make it yours)
Open the template files in your favorite editor (like VS Code) and customize them:
1.  **`profile_template.md`:** Fill in your professional background, your unwritten operating tenets, and your empirical writing style markers. Rename this file to `profile.md`.
2.  **`playbook_template.md`:** Customize your investment due diligence checklists, forensic auditing metrics, and your **Half-Kelly Sizing Rule** parameters. Rename this file to `investment.md`.
3.  **`curation_template.md`:** Add a running index of the core books, essays, and threads that form your intellectual compass. Rename this file to `curation.md`.

### Step 3: Open in Obsidian (Watch your mind connect)
1.  Download and install **[Obsidian](https://obsidian.md/)** (free, local Markdown editor).
2.  On launch, select **"Open folder as vault"** and choose your cloned `Second Brain` folder.
3.  Open **`Dashboard.md`** as your central home screen.
4.  Press **`Ctrl + G`** (or click the network-web icon in the sidebar) to open your **interactive 3D Graph View**. As you write notes and bidirectionally link them, watch your neural mind-map automatically connect, bounce, and grow in real-time!

---

## Recommended Graph Groups & Color Settings

To transform your graph view from plain gray circles into a gorgeous, highly professional mind-map, open the **Graph Settings** (Gear icon on your graph screen) -> **Groups** -> **New group**, and add these search queries and colors:

*   **Group 1: The Engine Core**
    *   *Search Query:* `file:Dashboard`
    *   *Color:* **Bright Coral Red** (represents your central brain core).
*   **Group 2: Personal Identity & Voice**
    *   *Search Query:* `path:profile`
    *   *Color:* **Deep Violet / Purple** (represents your unique human voice and biography).
*   **Group 3: Sizing & Operating Playbooks**
    *   *Search Query:* `path:investment`
    *   *Color:* **Rich Emerald Green** (represents active wealth, business, and capital rules).
*   **Group 4: Curated Intellectual Library**
    *   *Search Query:* `path:curation`
    *   *Color:* **Clean Ocean Blue** (represents historical mental models and research).

---

## Feed the AI (How to run your "Digital Twin")

Once you have filled in your files, you can copy-paste or upload your Markdown context directly to any LLM (Claude, ChatGPT, or local Llama models) and prompt it:

> *"I want you to act as my personal digital twin. Read these files fully to understand exactly how I write, think, handle risk, and make strategic decisions. Ground your subsequent drafts and advice in these playbooks."*

You now have a conversational partner that knows your mind, writes in your style, and audits decisions using your exact professional guardrails.

---

## Advanced Extensions (Build on top of this)

Once your core Second Brain is established, you can build two high-leverage expansions on top of it:

### A. The Personal Portal (Your Website)
Compile your Markdown files into a responsive, minimalist, fast personal website using **Astro**, **Tailwind CSS**, and **React**. Host your bio, essays, and investments on your own domain.
### B. The Automated Sourcing Pipeline (The Scout)
Write a lightweight Python scraper and evaluation crawler that crawls startup forums and automatically evaluates new ventures against your exact playbook and curation criteria, appending scorecards directly to your Second Brain.

---

## 📜 License
This project is open-source and licensed under the MIT License. Feel free to fork, customize, and share it with your network!
