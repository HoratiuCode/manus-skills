---
name: n8n-expert
description: "Specialized knowledge and workflows for creating engineering-grade n8n AI automations and strategic business consulting. Use for: building scalable workflows, integrating AI agents, identifying high-ROI automation opportunities, and consulting on AI business strategy."
---

# n8n Expert Skill

This skill provides the procedural knowledge and frameworks to design, build, and consult on high-performance n8n AI automations. It covers engineering best practices, AI agent architecture, and strategic consulting for business process optimization.

## 1. Core Workflow: Engineering-Grade n8n Development

Building professional n8n automations requires a structured, engineering-first approach:

1. **Discovery and Mapping**: Map out the business process in detail, identifying all triggers, data sources, and desired outcomes.
2. **Architecture Design**: Decide between a standard deterministic workflow (chain) or a non-deterministic AI agent based on the complexity and variability of the task.
3. **Modular Implementation**: Build using small, reusable sub-workflows. Use the **Execute Workflow** node to maintain a clean, readable main canvas.
4. **Error Handling and Observability**: Implement global error workflows and local "On Error" paths. Use **Wait** nodes with exponential backoff for external API calls.
5. **Testing and Deployment**: Test each module independently before full integration. Use n8n's expression system for environment-specific variables.

## 2. Strategic Consulting Principles

When consulting for businesses, focus on high-impact, engineering-sound solutions:

- **ROI-First Mindset**: Prioritize automation opportunities based on frequency, variability, and potential time/cost savings.
- **AI Agent vs. Workflow**: Recommend AI agents only when non-deterministic reasoning or dynamic tool selection is required. Use standard workflows for rules-based, high-speed tasks.
- **Data Privacy and Security**: Ensure all automations comply with business data policies, especially when using external LLM providers.
- **Scalability and Maintenance**: Build with the future in mind, using modular sub-workflows and clear naming conventions to ensure the system is easy to maintain.

## 3. Specialized Resources

For detailed instructions on specific aspects of n8n and automation consulting, refer to the following resources:

| Resource | Content | When to Use |
| :--- | :--- | :--- |
| `references/engineering_and_ai.md` | Engineering best practices, AI agent vs. workflow decision tree, and the "Agentic" n8n stack. | When designing and building the technical architecture of an automation. |
| `references/consulting_and_business.md` | Automation consulting framework, business-context decision making, and high-value AI use cases. | When advising a business on their AI and automation strategy. |

## 4. Professional n8n Toolset

Efficiency and reliability are the hallmarks of an n8n expert. Use these tools for their respective purposes:

- **n8n Self-Hosted / Cloud**: The primary automation platform for building and running workflows.
- **Code Node (JS)**: For complex data transformation and custom logic that standard nodes cannot handle.
- **AI Agent Node**: The central hub for building autonomous, reasoning-based AI agents in n8n.
- **HTTP Request Node**: For connecting to any external API that does not have a native n8n node.
- **Pinecone / Milvus**: Vector stores for providing RAG (Retrieval-Augmented Generation) capabilities to AI agents.
- **GitHub / GitLab**: For version controlling custom scripts and tracking workflow changes.
