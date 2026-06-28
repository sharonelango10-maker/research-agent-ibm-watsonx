# Research Agent (IBM Watsonx Orchestrate)

## What is this?

A Research Agent is an AI agent that helps with academic and scientific research tasks. It can search literature, summarize papers, organize references, suggest hypotheses, and draft sections of research papers, saving time on repetitive research work.

Built as part of the **Edunet Foundation × IBM SkillsBuild AICTE Internship Program**, using **IBM Cloud Lite**, **GPT-OSS 120B(Open AI)** and **watsonx Orchestrate**.

---

## Problem It Solves

Researchers spend a lot of time on repetitive tasks — searching papers, summarizing them, managing citations, and organizing data. This agent automates those tasks using NLP, so researchers can focus more on analysis and original thinking.

---

## Tech Used

- **IBM watsonx Orchestrate** — to build and run the agent
- **GPT-OSS 120B(Open AI)** — the foundation model powering the agent's responses
- **IBM Cloud Lite** — hosting platform

---

## What the Agent Can Do

- Search for relevant research papers
- Summarize papers into key points
- Organize references/citations (APA, IEEE, MLA)
- Extract data points from papers (e.g., dataset, accuracy)
- Suggest research hypotheses
- Draft sections of a research paper (Abstract, Intro, etc.)
- Generate research reports/briefs

---

## How It Behaves

- Only answers using verified sources and never invents citations or findings
- Clearly labels AI-generated suggestions (e.g., hypotheses) as "for review," not fact
- Asks clarifying questions if a request is unclear
- Keeps responses well-structured and easy to read
- Leaves final decisions to the user — it drafts, it doesn't conclude
- Stays in scope: research help only (no medical, legal, or financial advice)

---

## Knowledge Base

The agent is grounded with a reference document so it gives accurate answers:

 **How to Write an Efficient Research Paper** — used when the user asks about paper structure or writing style.

---

## Example Prompts

- "Summarize this paper for me."
- "Organize these papers into an APA bibliography."
- "Create an IEEE citation list from my search results."
- 
---

## How It Was Built

1. Created the agent in **watsonx Orchestrate Agent Builder** 
2. Wrote instructions defining its purpose and behavior
3. Uploaded reference PDFs to the **Knowledge** section
4. Added quick-start sample prompts
5. Tested it via **Agent Chat**

---

## Future Improvements

- Connect live literature search (arXiv, Semantic Scholar)
- Add automated citation export
- Expand knowledge base with more papers

---

## Author - **Sharon** **Elango**
Edunet Foundation × IBM SkillsBuild AICTE Internship Program
