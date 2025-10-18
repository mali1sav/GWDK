# 🚀 The Lean Gemini Workflow Development Kit

> A streamlined, entrepreneurial framework for using AI agents to architect, build, validate, and operate complex software. This kit provides the battle-tested protocols to transform an AI from a simple coder into a versatile, full-stack development partner.

---

## The Philosophy: The Strategist & The AI Partner

Previous methodologies are often too complex for the speed required by modern development. The LADK is built for entrepreneurial effectiveness. The workflow is a continuous loop between two roles:

1.  **The Human (The Strategist):** You set the vision, make the key product decisions, and act as the final arbiter of quality. You are the CEO and the Product Owner.
2.  **The AI (The Full-Stack Partner):** The agent (e.g., Windsurf or Cursor) acts as your complete engineering team. Guided by the LADK protocols, it serves as an architect, a full-stack developer, a QA analyst, and a DevOps engineer.

This repository contains the master prompts for this entire, repeatable lifecycle.

---

## ⚙️ The Four-Stage Workflow

The LADK structures development into a clear, continuous loop. Each stage is governed by a specific protocol from this kit.

`mermaid
graph TD
    A[1. Ideate] --> B[2. Build];
    B --> C[3. Validate];
    C --> D{Does it Pass?};
    D -- Yes --> E[4. Operate];
    E --> A;
    D -- No --> F[Bug Report];
    F --> B;
`

### **1. `01_IDEATION_PROTOCOL.md`**
The "Architect" phase. A master prompt to command a frontier LLM to act as an **active research partner**, stress-testing your idea and co-creating a world-class specification.

### **2. `02_GENESIS_PROTOCOL.md`**
The "Build" phase. A prompt for your agentic coder to build a new project from scratch, based on the specification. It enforces a strict, test-driven, and verifiable workflow.

### **3. `03_UAT_PROTOCOL.md`**
The "Validate" phase. A prompt that transforms the agent into an adversarial **QA Red Team**. It performs real, interactive user testing to find functional bugs and usability flaws that a simple test suite would miss.

### **4. `04_MAINTENANCE_PROTOCOL.md`**
The bug-fixing loop. A prompt to command the agent to fix the issues discovered during UAT, using a safe, regression-proof workflow.

### **5. `05_OPERATIONS_PROTOCOL.md`**
The "Operate" phase. A prompt to handle practical, real-world tasks like generating deployment configurations for modern PaaS providers (Vercel, Railway) and implementing simple, effective user feedback mechanisms.

---

This toolkit represents a complete, end-to-end methodology for lean, AI-driven software development.
