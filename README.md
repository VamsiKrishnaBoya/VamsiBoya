# Multi-Agentic AI SDLC Platform

This project implements a **Multi-Agentic AI-based Software Development Life Cycle (SDLC) platform** that automates and orchestrates every phase of software delivery using specialized AI agents. The platform is built with Python, LangChain, Azure OpenAI, and follows PMP and Azure best practices for compliance, traceability, and rapid delivery.

## Features

- **Agentic SDLC Workflow:** Each SDLC phase is managed by a dedicated AI agent (Prompt, Requirements, Tech Stack, Risk, Infra, Backend, Frontend, DevOps, Documentation, Review, etc.).
- **Azure & PMP Compliance:** All code and infrastructure follow Azure best practices and PMP standards.
- **Automated Code Generation:** Backend (FastAPI), Frontend (React), Infrastructure (Terraform), DevOps pipelines, and documentation are generated and reviewed by agents.
- **Human-in-the-Loop:** Explicit approval steps for critical decisions (e.g., infra planning, cost estimation).
- **Export & Audit:** All deliverables (requirements, code, docs, pipelines) are archived for audit and handoff.
- **Visualization:** Mermaid and Graphviz diagrams for agent workflow and architecture.

## Project Structure

- `AgenticSDLC.ipynb` — Main Jupyter notebook orchestrating the agentic SDLC workflow.
- `requirements.txt` — Python dependencies.
- `*.md` — Generated deliverables (requirements, tech stack, risks, infra plan, code, docs, etc.).
- `agent_workflow_diagram.png` — Visual workflow of all agents.

## How It Works

1. **Prompt Agent:** Clarifies user intent into actionable project goals.
2. **Requirement Agent:** Gathers and structures requirements (PMP SRS).
3. **Tech Stack Advisor:** Recommends technologies and architecture.
4. **Risk Agent:** Identifies and documents risks.
5. **Infra Planner:** Designs cost-effective Azure infrastructure.
6. **Backend/Frontend Agents:** Generate FastAPI and React code.
7. **Infra Code Generator**: Generates Terraform Code to build the infra.
8. **DevOps Agent:** Creates Azure DevOps pipelines and deployment scripts.
9. **Documentation Agent:** Compiles project documentation.
10. **Review Agents:** Ensure compliance and quality.
11. **Export Agent:** Archives all deliverables for audit/handoff.
12.Note: Add your DevOps PAT, Org URL, Azure SPN, or Azure OpenAI Key to the .env file.
   Build Python code to auto-deploy infrastructure and application via the DevOps pipeline. Previously generated code by agents will be reused.

## Getting Started

1. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

2. **Configure environment:**
   - Copy `.env.example` to `.env` and set your Azure OpenAI and Azure DevOps credentials.

3. **Run the notebook:**
   - Open `notebook.ipynb` in VS Code or Jupyter and execute cells step by step.

4. **Review outputs:**
   - Generated files (requirements, code, docs, etc.) will appear in the project root and can be archived as a ZIP.

## Coding Instructions

All code generation follows strict user-provided coding instructions for Azure best practices. See [`coding_instructions.md`](coding_instructions.md) for details. 

## References

- [multi-agentic-ai-sdlc-ebook/README.md](multi-agentic-ai-sdlc-ebook/README.md)
- [notebook.ipynb](notebook.ipynb)

---

**Author:** Vamsi Boya
**Contact**: https://www.linkedin.com/in/vamsiboya/
