# PRD Templates for Product Managers

A curated collection of Product Requirements Document (PRD) and 1‑Pager templates from leading PMs and companies. These templates can be:

1. Used directly in your workflow as starting points for specs.
2. Uploaded into an LLM (ChatGPT, Claude, Gemini, etc.) to generate, adapt, or refine PRDs for your context.


## Quick Start

1. Browse the templates and pick one that fits your use case.
2. Copy it into your working doc or ask an LLM to adapt it to your context.
3. Follow the Best Practices checklist below while drafting.
4. Use the LLM prompt recipes to iterate, pressure‑test, and finalize.

---

## Best Practices distilled from the templates

- **Problem first, solution second:** Define the customer problem, desired outcome, and evidence before discussing solutions.
- **Set clear, measurable success criteria:** Define how success will be measured (e.g., metrics, baselines, milestones, and guardrails). Tie these directly to business and user value.
- **Map the customer journey:** Use end-to-end flows (including edge cases) to show how the user experiences the product. Prioritize critical flows, capture assumptions, and list key features. 
- **Align the team and record decisions:** Identify stakeholders, capture approvals, open questions, record decision rationale, and maintain a changelog.
- **Include relevant non‑functional requirements:** Performance, security, accessibility, internationalization, platforms.
- **Specify scope and constraints:** Constraints, assumptions, dependencies, platforms; explicityly list what's in‑scope vs out‑of‑scope to prevent scope creep.
- **Optimize for clarity and brevity:** Write in plain language, minimize jargon, and add links to research, designs artifacts, dashboards, etc. instead of bloating the PRD. If required, create a detailed appendix for relevant details and FAQs.

### Things to keep in mind when drafting a PRD

- Problem & Evidence
    - Who is the user, what job are they trying to get done, and what evidence validates this problem is real and urgent?
    - Why is solving this problem important now (e.g., business priority, competitive threat, market timing)?
- Outcomes & Goals
    - What specific outcomes must change for the user and the business?
    - How will success be measured (metrics, baselines, guardrails)?
- Scope & Trade-offs
    - What’s explicitly in-scope and out-of-scope?
    - What alternative approaches were considered, and why was this path chosen?
    - What constraints, assumptions, and dependencies shape the solution space?
- User Experience & Flows
    - What are the critical user journeys and edge cases?
    - How will this solution integrate into existing workflows or systems?
- Risks & Uncertainties
    - What are the biggest risks across product adoption, technical feasibility, and business impact?
    - What experiments, validations, or mitigations are planned?
- Execution & Rollout
    - What is the rollout plan (phased milestones, feature flags, exit criteria)?
    - How will feedback be gathered and incorporated post-launch?
- Alignment & Communication
    - Who are the stakeholders (owners, approvers, reviewers), and how will alignment be maintained?
    - How will decisions and changes be documented over time?

---

## Using these templates with LLMs

**Context to include in your prompt**
- Product and audience: problem area, personas, JTBD.
- Business goals and constraints: OKRs, time horizon, budget/tech constraints.
- Evidence: key insights, data baselines, research quotes, support tickets.
- Scope: in/out of scope, dependencies, platforms (web/iOS/Android/backend).
- Success: target metrics, guardrails, evaluation plan.
- Rollout: phases, exit criteria, operational checklists.
- Stakeholders: owners, approvers, reviewers.

**Example prompts:**

"Draft a PRD using the template provided for the following feature: Contractor Auto-Onboarding in Acme Payroll.

- Product & Audience: SMB payroll app. Users = small business owners + accountants. JTBD = quickly onboard/pay contractors without errors.
- Business Goals/Constraints: Reduce onboarding errors by 40% this quarter. Launch MVP in 2 quarters. One squad, limited budget.
- Evidence: 200+ support tickets in 6 months, current error rate 8.5%. Surveys show onboarding takes 25 mins avg. Target = 10 mins.
- Scope: In = Guided onboarding (web + iOS)
- Success: Reduce onboarding time 60%, cut support tickets 50%. Guardrails: no payroll latency increase.
- Rollout: Phase 1 internal pilot → Phase 2 limited rollout → Phase 3 GA. Exit: <2% escalation rate.
- Stakeholders: PM = Jane Doe. Approvers = VP Product, Head of Compliance. Reviewers = Eng, Design, Support leads."

---
