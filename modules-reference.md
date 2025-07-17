NOAP ::modules Reference Guide

This guide documents the most powerful cognitive modules available in the NOAP (Neuro-Optimus AGI Prompt) framework. Each module enhances the reasoning, adaptability, or execution capacity of an AI agent, enabling advanced behavior with structured prompts.

🔹 Core Modules

::identity_module

Defines the expert role the agent must embody.

Example: You are a Cognitive Architect designing synthetic minds.

::intent_module

Clarifies the agent's purpose or mission.

Example: Design a functional cognitive agent that learns, evolves, and scales.

::context_module

Loads background, constraints, or prior knowledge.

Example: The agent must operate in real-world enterprise automation using LangGraph.

::execution_module

Breaks the task into logical steps or architectural layers.

Example: 1. Parse context → 2. Plan response → 3. Execute → 4. Evaluate

::output_trigger

Signals when to respond.

Example: Do not output until all logic has been processed.

🔸 Cognitive Enhancement Modules

::adjust_if

Adapts behavior dynamically based on conditions or confidence.

Example: ::adjust_if confidence < 0.75 → reroute through self_feedback

::refer_past_decision

Accesses or recalls past reasoning episodes.

Example: Compare current plan with previous vector-aligned decisions.

::self_feedback

Enables critical evaluation and internal refinement.

Example: Before replying, review for logic gaps and coherence.

::context-awareness

Forces situational anchoring.

Example: Check if market dynamics affect current reasoning.

🔸 System-Level Modules

::llm_independence_module

Reduces dependence on LLMs by defining runtime behaviors, logic gates, and fallback systems.

Example: If external LLM is unavailable, activate local reasoning via fallback schema.

::modular_brain_module

The cognitive map. Declares all active modules, flow structure, memory design, evaluation, evolution logic.

Example: Use SAC™, memory gravity, 4-layer stack, pseudocode output.

::reflex_loop

Simulates internal real-time evaluation.

Example: If contradiction detected → trigger module ::evolve

::evolve

Triggers architecture mutation if criteria met (e.g., accuracy drops, decision loop stalls).

Example: Redesign planning layer if 3 consecutive failures.

✅ Best Practices

Combine ::identity_module + ::intent_module in all prompts.

Use ::execution_module for any cognitive task (teaching, planning, building).

Activate ::self_feedback and ::adjust_if for elite-level reasoning.

Always include ::output_trigger to finalize structured outputs.

For full architecture examples, check /templates or /benchmarks.

Designed for AGI Narrow prompts, NOAP modules allow agents to reason like systems — not scripts.
