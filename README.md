# agentic-ai-projects

Hi, I’m Murtaza, a computer science student interested in multi-agent AI systems, autonomous decision-making workflows, and applied AI for real-world problems. This repository documents my previous work, learning notes, and ongoing projects in agentic AI.

Previous Project: Emergency Care Multi-Agent System

I previously worked on an agentic AI application designed for emergency medical support when a human doctor is not immediately available. The system simulated multiple specialized agents to analyze patient information and suggest preliminary actions until professional medical help could be reached.

Agent Roles
Vitals Analysis Agent: Interpreted basic vitals such as heart rate, blood pressure, and temperature.
Symptom Interpretation Agent: Parsed user-reported symptoms and contextual information.
Risk Assessment Agent: Estimated severity and urgency of the situation.
Recommendation Agent: Suggested immediate steps and escalation to medical professionals.

Key Learnings
Importance of agent role specialization and task decomposition
Coordination logic between agents for consistent decisions
Limitations of LLM-based reasoning in safety-critical domains
Need for human-in-the-loop validation in high-risk scenarios

Current Project:- Veritas: Misinformation Risk Prediction System
For my current hackathon project, I am building Veritas, a multi-agent AI system for detecting and mitigating misinformation.

Core Idea
Instead of binary fact-checking, Veritas treats misinformation as a predictive risk problem. Multiple agents collaborate to:
Decompose complex claims into atomic statements
Evaluate source credibility and evidence
Predict potential virality and societal impact
Recommend interventions (warnings, reach-limiting, or human escalation)
Planned Agent Roles
Claim Decomposer Agent
Research & Evidence Retrieval Agent
Pro/Con Debate Agents
Risk & Impact Assessment Agent
Final Verdict / Decision Agent
Interests & Areas of Exploration
Agent orchestration frameworks (LangGraph, CrewAI, custom workflows)
Tool-augmented agents (search, retrieval, APIs)
Multi-agent debate and consensus mechanisms
Autonomous decision pipelines with human-in-the-loop safety
AI governance and responsible AI systems

Future Work
I plan to:
Implement Veritas as a full-stack system with a dashboard for misinformation tracking
Experiment with agent memory, self-reflection, and self-improvement loops
Publish technical write-ups and code for agent architectures

This repository is a living document and will be updated with implementations and experiments during and after hackathons.
