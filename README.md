# 5-Day AI Agents Intensive Course with Google

This repository contains materials and assignments for the "5-Day AI Agents Intensive Course with Google".

**Course Link:** [https://www.kaggle.com/learn-guide/5-day-agents](https://www.kaggle.com/learn-guide/5-day-agents)  
**Sessions Playlist:** [https://www.youtube.com/playlist?list=PLqFaTIg4myu9r7uRoNfbJhHUbLp-1t1YE](https://www.youtube.com/playlist?list=PLqFaTIg4myu9r7uRoNfbJhHUbLp-1t1YE)

---

## Day 1: Introduction to Agents

### Today’s Assignments

1.  **Complete Unit 1 – “Introduction to Agents”**:
    *   Listen to the summary podcast episode for this unit, created by NotebookLM: [https://www.youtube.com/watch?v=zTxvGzpfF-g](https://www.youtube.com/watch?v=zTxvGzpfF-g)
    *   To complement the podcast, read the “Introduction to Agents” whitepaper: [https://www.kaggle.com/whitepaper-introduction-to-agents](https://www.kaggle.com/whitepaper-introduction-to-agents)

### Podcast Summary: Whitepaper Companion - Introduction to Agents (Google x Kaggle)

-   **Core Shift**: AI moving from passive (Q&A, translation) to **autonomous AI agents** that plan, act, and solve multi-step goals without constant human guidance.

-   **Agent Anatomy (3 Core Parts)**:
    -   **Model (Brain)**: LLM for reasoning; curates context window (mission, memory, tool results).
    -   **Tools (Hands)**: APIs, databases, code execution—enable real-world actions.
    -   **Orchestration Layer (Conductor)**: Manages the loop, memory, persona, and reasoning strategy (e.g., ReAct: Reason → Act → Observe → Repeat).

-   **Agent Loop (5 Stages)**:
    1.  Get mission
    2.  Scan scene (tools + memory)
    3.  Think/Plan
    4.  Take action (call tool)
    5.  Observe → iterate

-   **Agent Capability Taxonomy**:
    -   **Level 0**: Pure LLM (no tools, static knowledge)
    -   **Level 1**: Connected problem-solver (uses tools, real-time data)
    -   **Level 2**: Strategic problem-solver (context engineering, chains tool outputs intelligently)
    -   **Level 3**: Collaborative multi-agent (agents delegate to specialist agents)
    -   **Level 4**: Self-evolving (detects gaps, builds new agents/tools on the fly)

-   **Production-Ready Practices**:
    -   **Model Routing**: Use heavy models (e.g., Gemini 1.5 Pro) for planning, lighter ones (Flash) for simple tasks.
    -   **Tools**: RAG, NL2SQL, APIs with clear OpenAPI specs + function calling.
    -   **Memory**: Short-term (current loop) + long-term (vector DB/RAG).
    -   **Testing**: LM-as-judge + golden datasets; OpenTelemetry traces for debugging.
    -   **Security**: Defense-in-depth (hard rules + guard models), agent identity (least-privilege), central gateway for governance.
    -   **Evolution**: Feedback loops, agent gym (simulation sandbox).

-   **Examples**:
    -   **Co-Scientist**: Level 3–4 research collaborator with supervisor + specialist agents.
    -   **AlphaEvolve**: Level 4 system that discovers/optimizes algorithms via code generation + evolution.

**Takeaway**: Success isn’t just the smartest model, it’s rigorous engineering of model + tools + orchestration + ops. Builders become architects of autonomous systems. Check the whitepaper and 5-day Google AI Agents Intensive.

2.  **Complete these codelabs on Kaggle**:
    *   **a.** Build your first agent using Gemini and Agent Development Kit (ADK): [https://www.kaggle.com/code/kaggle5daysofai/day-1a-from-prompt-to-action](https://www.kaggle.com/code/kaggle5daysofai/day-1a-from-prompt-to-action)
    *   **b.** Build your first multi-agent systems using ADK: [https://www.kaggle.com/code/kaggle5daysofai/day-1b-agent-architectures](https://www.kaggle.com/code/kaggle5daysofai/day-1b-agent-architectures)

3.  **Important Notes**:
    *   **c.** Make sure you phone verify your Kaggle account before starting, it's necessary for the codelabs: [https://www.kaggle.com/settings](https://www.kaggle.com/settings)
    *   **d.** We also have a troubleshooting guide for the codelabs. Be sure to check there for solutions to common problems: [https://www.kaggle.com/code/kaggle5daysofai/day-0-troubleshooting-and-faqs](https://www.kaggle.com/code/kaggle5daysofai/day-0-troubleshooting-and-faqs)
    *   **e.** Want to have an interactive conversation? Try adding the whitepaper to NotebookLM: [https://notebooklm.google.com/](https://notebooklm.google.com/)

---

*More content for remaining days will be updated as it becomes available.*
