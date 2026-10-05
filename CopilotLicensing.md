# Microsoft Copilot Licensing Matrix
### Page by Mark W. Not official documentation.
## Rule of thumb:

| License | What It Really Means |
|----------|----------|
| Microsoft 365 Copilot | Build and use internal productivity agents inside Microsoft 365. |
| Copilot Studio Standard Harness | Traditional Copilot Studio bots and workflows. |
| Copilot Studio GitHub Harness | Autonomous AI agents with reasoning, memory, skills, and document creation. |
| Copilot Studio Credits | Required for advanced, external, autonomous, or GitHub Harness scenarios. |

---

## Product vs License Requirements

| Product / Capability | Microsoft 365 Copilot | Copilot Studio Credits / PAYG | Notes |
|----------|----------|----------|----------|
| Copilot Chat | ✅ | ❌ | Included with Microsoft 365 Copilot. |
| Agent Builder | ✅ | ❌ | Build declarative agents inside Microsoft 365 Copilot. |
| Declarative Agents | ✅ | ❌ | Created using Agent Builder. |
| Copilot Studio (Copilot Chat Harness) | ✅ | ❌ | Extends Microsoft 365 Copilot experiences. |
| Copilot Studio Standard Harness | ✅ Included for qualifying internal employee use | ✅ Required for non-licensed users, external channels and autonomous usage | Employee-facing usage by Microsoft 365 Copilot-licensed users is generally included; other usage consumes Copilot Credits. |
| Copilot Studio GitHub Copilot Harness | ❌ | ✅ | Credit-based from development through runtime. |
| Internal Employee Agents | ✅ | Usually not required | When used by licensed Microsoft 365 Copilot users. |
| External Customer-Facing Agents | ❌ | ✅ | Website, mobile app, Teams shared channels, social media, etc. |
| Autonomous Agents | ❌ | ✅ | Consumption-based licensing. |
| Agent Flows (Standard Harness) | ✅ Included for licensed employee-facing use | ✅ Required for other usage | Billing follows Standard Harness rules. |
| Agent Flows (GitHub Copilot Harness) | ❌ | ✅ Always | Credits consumed during authoring, testing, and runtime. |
| Multi-Agent Systems | ❌ | ✅ | Advanced Copilot Studio scenarios. |

---

# Harness Comparison

| Capability | Agent Builder | Copilot Chat Harness | Standard Harness | GitHub Copilot Harness |
|------------|--------------|---------------------|------------------|-----------------------|
| Build Agents | ✅ | ✅ | ✅ | ✅ |
| Uses Microsoft 365 Copilot UX | ✅ | ✅ | ✅ | Optional |
| Declarative Agent Support | ✅ | ✅ | ❌ | ❌ |
| Topic-Based Authoring | ❌ | ❌ | ✅ | ❌ |
| Agent Flows | ❌ | ❌ | ✅ | ✅ |
| Autonomous Planning | ❌ | ❌ | Limited | ✅ |
| Long Running Tasks | ❌ | ❌ | Limited | ✅ |
| Memory | ❌ | Limited | Limited | ✅ |
| Skills | ❌ | ❌ | ❌ | ✅ |
| Multi-Step Reasoning | Limited | Limited | Moderate | ✅ |
| Native Word/Excel/PowerPoint/PDF Creation | ❌ | ❌ | Limited | ✅ |
| Multi-Agent Orchestration | ❌ | ❌ | Limited | ✅ |
| External Channel Publishing | ❌ | ❌ | ✅ | ✅ |
| Copilot Credits Required | ❌ | ❌ | Sometimes | ✅ |

---

# Licensing by Common Scenario

| Scenario | Microsoft 365 Copilot Only | Copilot Studio Credits Required |
|-----------|-----------|-----------|
| Personal productivity agent | ✅ | ❌ |
| Team knowledge agent | ✅ | ❌ |
| Declarative agent | ✅ | ❌ |
| Agent Builder agent | ✅ | ❌ |
| Extend Microsoft 365 Copilot | ✅ | ❌ |
| Share agent inside Microsoft 365 | ✅ | ❌ |
| Publish to website | ❌ | ✅ |
| Publish to mobile application | ❌ | ✅ |
| Publish to external customers | ❌ | ✅ |
| Autonomous workflow agent | ❌ | ✅ |
| Multi-agent solution | ❌ | ✅ |
| GitHub Harness agent | ❌ | ✅ |
| Agent creating Office files automatically | ❌ | ✅ |
| Agent operating across multiple business systems | ❌ | ✅ |

---

# Copilot Studio Purchasing Options

| Licensing Model | Best For | Characteristics |
|-----------------|----------|-----------------|
| Microsoft 365 Copilot | Internal users | Includes Agent Builder and Standard Harness access. |
| Copilot Studio Pay-As-You-Go | POCs and variable workloads | Consumption-based billing. |
| Copilot Studio Pre-Purchase Plan | Production deployments | Buy Copilot Credits up-front. |
| Copilot Credits | GitHub Harness and advanced agents | Shared tenant-wide consumption pool. |

---

# Simple Decision Guide

| If You Want To Build... | License Needed |
|-------------------------|----------------|
| Declarative Agent | Microsoft 365 Copilot |
| Agent Builder Agent | Microsoft 365 Copilot |
| Microsoft 365 Copilot Extension | Microsoft 365 Copilot |
| Internal Knowledge Agent | Microsoft 365 Copilot |
| Traditional Copilot Studio Chatbot | Copilot Studio |
| Website Chatbot | Copilot Studio |
| External Customer Service Bot | Copilot Studio |
| Autonomous Agent | Copilot Studio |
| Multi-Agent System | Copilot Studio |
| GitHub Harness Agent | Copilot Studio Credits |
| Agent That Creates and Modifies Documents | Copilot Studio Credits |
| Cross-System Business Process Agent | Copilot Studio Credits |

---

# A few key links
- [Copilot-studio-estimator](https://microsoft.github.io/copilot-studio-estimator/)
- [Overview of usage-based billing](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/billing-credit-overview)
- [Licensing for agents powered by the standard harness](https://learn.microsoft.com/en-us/microsoft-copilot-studio/billing-licensing)
