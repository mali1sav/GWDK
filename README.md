# 🚀 The Gemini/Windsurf Development Kit (GWDK)

> A comprehensive framework for transforming Large Language Models from "forgetful interns" into disciplined, world-class engineering partners. This toolkit provides the protocols and templates to architect, build, and maintain complex software projects with AI agents.

---

## The Problem: The "Forgetful Intern"
AI coding agents are powerful but suffer from a critical flaw: **context drift**. They forget requirements, misunderstand complex architectures, and introduce regression bugs. Without a rigorous framework, managing them for any non-trivial, ongoing project becomes a frustrating exercise in micromanagement.

## The Solution: The Architect & The Executor
The GWDK solves this by splitting the workflow into two distinct roles, enforced by structured protocols:

1.  **The Architect (The Human & The Ideation AI):** You provide the high-level vision. Using the **Ideation Protocol**, you collaborate with a frontier LLM to pressure-test your idea and generate a world-class architectural blueprint (`SPECIFICATION.md`).
2.  **The Executor (The Agentic Coder):** The agent (e.g., Windsurf) is given a clear, granular plan. Using the **Genesis** and **Maintenance Protocols**, it executes this plan autonomously, with mandatory, test-driven steps that ensure quality and adherence to the specification.

This repository contains the master templates for this entire, repeatable workflow.

---

## 🔧 The Toolkit: What's Inside?

This repository contains five core files that constitute the entire development lifecycle.

### `IDEATION_PROTOCOL.md`
A master prompt to command a frontier LLM (like Gemini 3.0 or GPT-5) to act as a "Silicon Valley Product Council." It stress-tests your raw idea from product, technical, and domain-expert perspectives before any code is written.

### `SPECIFICATION_TEMPLATE.md`
A professional-grade template for a project specification. The output of the Ideation Protocol is used to fill this out, creating the "Single Source of Truth" for your project.

### `GENESIS_PROTOCOL.md`
A master prompt for your agentic coder (Windsurf). It automates the entire process of building a new project from scratch, phase by phase, based on the `SPECIFICATION.md`. It enforces a strict, test-driven, and verifiable workflow.

### `MAINTENANCE_PROTOCOL.md`
A master prompt for all ongoing development, bug fixes, and feature enhancements. It forces the agent to perform a full system scan and regression test *before* writing any new code, ensuring the stability of your living codebase.

### `README.md`
This file, providing an overview and guide to the GWDK methodology.

---

## ⚙️ The Workflow: How to Use the GWDK

### For a New Project:

1.  **Ideate (`IDEATION_PROTOCOL.md`):** Copy the contents of this file into a chat with a frontier LLM. Engage in the "Socratic Inquisition" to refine your idea.
2.  **Specify (`SPECIFICATION_TEMPLATE.md`):** Use the output from the ideation session to fill out this template. This becomes your project's master blueprint.
3.  **Execute (`GENESIS_PROTOCOL.md`):** Copy this master prompt into your agentic coder (Windsurf). It will read your new `SPECIFICATION.md`, generate a plan for Phase 1, and begin building your project autonomously.

### For Ongoing Maintenance:

1.  **Define Change (`MAINTENANCE_PROTOCOL.md`):** Open this file and fill out the `## CHANGE REQUEST ##` section at the bottom with your desired enhancement or bug fix.
2.  **Execute Change:** Copy the entire, edited file and paste it into your agentic coder. The agent will follow the strict, safety-first protocol to implement your change without breaking existing functionality.

---

## 📜 Core Principles

This methodology is built on a few non-negotiable principles:

*   **The Specification is the Source of Truth:** All work must map back to the master plan.
*   **Test-Driven Development is Mandatory:** Code is not complete until a test proves it works.
*   **Regressions Are Unacceptable:** No change is approved if it breaks existing, tested functionality.
*   **The Human is the Architect; The AI is the Executor:** Leverage AI for what it's best at—lightning-fast execution—while you focus on high-level strategic direction.

---

## Contributing

This is a living methodology. If you have ideas for improving the protocols or templates, please open an issue to discuss them.

## License

This toolkit is released under the [MIT License](LICENSE).
