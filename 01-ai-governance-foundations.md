# AI Governance Foundations
> The conceptual foundation for understanding responsible AI governance before applying the RBI FREE-AI framework.

## What is AI Governance?

AI governance is the set of structures, responsibilities, processes and controls that guide how an organisation develops, deploys, uses, monitors and retires AI systems.

## Core areas

Each of these areas represents a different lens on the same underlying question: how does an organisation make AI trustworthy in practice, not just in principle. Together, they form the vocabulary the rest of this repository builds on.

### AI governance vs. Responsible AI vs. AI ethics
These three terms get used interchangeably but mean different things. AI ethics asks what *should* an AI system do — the values and principles at stake (fairness, harm, autonomy). Responsible AI translates those values into design and deployment practices — how a team builds and operates a system in line with those principles. AI governance is the structural layer underneath both: the accountability, decision rights, and controls that make responsible practices enforceable rather than aspirational.

### Why AI governance matters
Without governance, responsible AI principles remain intentions rather than practices — easy to agree with in a meeting, hard to verify in production. Governance is what turns "we care about fairness" into "here is who checks for bias, when, and what happens if they find it." It also gives organisations a defensible position with regulators, customers, and their own boards when an AI system causes harm or produces an unexpected outcome.

### The AI lifecycle
AI governance isn't a one-time gate — it has to operate across the full lifecycle: problem definition and data collection, model design and training, testing and validation, deployment, ongoing monitoring, and eventual retirement or replacement. Each stage carries different risks and needs different controls; a system that was fair and accurate at launch can drift as data, usage, or context changes, which is why monitoring and retirement are as much a governance concern as the initial build.

### Roles, accountability and human oversight
Someone has to be answerable when an AI system gets something wrong — governance fails when responsibility is diffuse ("the model did it") rather than assigned to a person or function. This includes defining who approves an AI use case before launch, who monitors it in production, and where a human is required to review or override a decision, particularly for higher-stakes outcomes.

### AI risk management
AI introduces risk types that traditional risk frameworks weren't built for — model drift, hallucination, adversarial manipulation, emergent behaviour in agentic systems. Effective risk management means classifying AI use cases by risk level (a chatbot answering FAQs is not the same risk as a credit-decisioning model) and applying proportionate controls, rather than a single blanket policy across every use case.

### Data governance
AI systems are only as trustworthy as the data they're trained and operated on. This covers how data is sourced, consented to, labelled, stored, accessed, and eventually deleted — and matters doubly for AI because poor data governance doesn't just create bad outputs, it can silently encode bias or leak sensitive information into a system's behaviour.

### Transparency and explainability
Transparency is about disclosure — do the people affected by an AI system know it's being used, and know enough about how it works to make informed decisions. Explainability is narrower — can a specific output be justified in terms a human can understand and act on. Both matter, but they solve different problems: transparency builds trust in the system generally, explainability builds trust in a specific decision.

### AI evaluation, monitoring and incident management
Testing an AI system before launch is necessary but not sufficient — governance requires ongoing evaluation against real-world performance, defined thresholds for when something counts as an incident, and a clear escalation path when those thresholds are breached. Without this, organisations discover problems from customers or regulators instead of from their own monitoring.

### Third-party and vendor governance
Most organisations don't build their AI systems entirely in-house — they rely on vendor models, APIs, and pre-trained components. Governance doesn't stop at the organisation's own boundary; it has to extend to vetting vendors' data practices, understanding what a third-party model was trained on, and clarifying liability when a vendor-supplied system causes harm.

### Governance as an enabler of responsible AI adoption
Governance is often framed as a brake on AI adoption — a set of hurdles that slow things down. In practice, well-designed governance does the opposite: clear approval paths, defined risk thresholds, and known accountability give teams the confidence to move faster, because they're not guessing at what's allowed or improvising controls under pressure. The absence of governance doesn't mean less friction — it usually means the friction shows up later, and more expensively, after something has already gone wrong.

## The central idea

Responsible AI principles become meaningful when they are translated into **clear ownership, risk-based controls and repeatable organisational practices**.

The next section examines how these ideas are reflected in the RBI FREE-AI Committee Report.
