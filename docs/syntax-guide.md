# 🧠 NOAP Syntax Guide

NOAP (Neuro-Optimus AGI Prompt) uses a modular syntax inspired by cognitive architectures. Each directive is defined with a `::` prefix to activate specific cognitive modules.

---

## 🔣 Basic Syntax

Each module starts with double colons `::` and is followed by its name:


---

## 📦 Core Modules (Always Used)

| Module               | Purpose                                         |
|----------------------|-------------------------------------------------|
| `::identity_module`   | Defines the AI's role and cognitive persona.    |
| `::intent_module`     | Specifies the goal of the prompt or mission.   |
| `::context_module`    | Provides background, input, or prior data.     |
| `::execution_module`  | Outlines how to think, plan, or act.           |
| `::output_trigger`    | Signals when to start generating output.       |

---

## 🧠 Optional Cognitive Modules

| Module                 | Purpose                                                           |
|------------------------|-------------------------------------------------------------------|
| `::self_feedback`       | Forces the agent to review its logic before output.              |
| `::adjust_if`           | Triggers correction routines under specific conditions.          |
| `::refer_past_decision` | Recalls previous actions or context to inform new decisions.     |
| `::modules.activate`    | Activates submodules like `::story_mode`, `::loop_mode`, etc.     |
| `::modular_brain_module`| Defines internal cognitive architecture (for agents, systems).   |

---

## 🧪 Experimental Modules

| Module                 | Use Case                                                         |
|------------------------|-------------------------------------------------------------------|
| `::llm_independence_module` | Designs behavior with reduced dependency on LLMs.             |
| `::gravity_memory`          | Prioritizes memory recall by weighted relevance (mass).       |
| `::reflex_gate`             | Executes decisions only if logic confidence threshold is met. |

---

## ✅ Output Formatting

Use a JSON block when precise format is needed:

```json
{
  "segments": [],
  "positioning": "",
  "opportunity_scores": []
}

---
Created by Nelson Padilla — 2025
Version: NOAP Titan 2.0
