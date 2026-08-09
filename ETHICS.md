# METAL MONKEY — Ethical Framework

## Purpose

This document defines the ethical principles and operational boundaries of the METAL MONKEY project.

METAL MONKEY is a research and analytical framework. Its purpose is to help people explore complex economic, ecological and geopolitical systems through transparent modelling.

It is **not an autonomous political authority, intelligence system, surveillance system, or mechanism for controlling people or institutions**.

The principles below apply to the software, models, datasets, documentation and contributions associated with the project.

---

# 1. Human Responsibility

METAL MONKEY supports human decision-making; it does not replace it.

Model outputs must never be presented as commands or as possessing inherent political authority.

A human decision-maker remains responsible for decisions made using information produced by the project.

The system should therefore use language such as:

> "The model estimates..."

rather than:

> "The system has determined..."

---

# 2. Transparency

Important assumptions must not be hidden.

Where practical, the project should make available:

* model assumptions;
* mathematical methods;
* data sources;
* transformations;
* uncertainty estimates;
* known limitations;
* relevant conflicts of interest;
* significant changes to methodology.

The project should never intentionally conceal important functionality from users.

**Research principles belong in documentation, not hidden inside executable code.**

---

# 3. No Covert Behaviour

METAL MONKEY must not secretly communicate with external systems.

The software must not contain undisclosed:

* network requests;
* tracking mechanisms;
* telemetry;
* web beacons;
* pingbacks;
* data collection;
* remote commands;
* execution mechanisms.

If network communication is required for a legitimate function, it should be documented and understandable to the user.

---

# 4. Privacy

The project should minimize the collection and processing of personal information.

METAL MONKEY should not attempt to identify, monitor or profile individuals unless there is a clearly documented and legitimate research purpose and an appropriate legal and ethical basis.

Publicly available information should not automatically be treated as ethically unrestricted information.

The project should prefer:

**aggregate data > identifiable individual data**

whenever aggregate data can answer the research question.

---

# 5. Lawful and Responsible Data

The project should use data obtained through legitimate means.

It must not intentionally seek:

* stolen datasets;
* leaked credentials;
* classified information;
* unauthorized access;
* private databases;
* compromised systems;
* restricted information obtained through circumvention.

Security-related or geopolitical research should rely on legitimate public sources unless a separate, documented research framework establishes an appropriate basis for other data.

---

# 6. No Surveillance

METAL MONKEY is not a surveillance platform.

It must not be designed to secretly monitor:

* individuals;
* political opponents;
* journalists;
* activists;
* employees;
* private organizations;
* governments or government personnel.

Analysis of public geopolitical events is fundamentally different from surveillance of individuals.

The project should maintain that distinction.

---

# 7. No Manipulation

The project must not intentionally be used to manipulate people through:

* targeted political persuasion;
* deceptive information;
* fabricated evidence;
* impersonation;
* psychological exploitation;
* coordinated disinformation;
* concealed influence campaigns.

Analytical models may study propaganda, misinformation or political behaviour as research subjects, but the project should not become an instrument for producing deceptive influence operations.

---

# 8. Political Neutrality

METAL MONKEY may analyze governments, political parties, political leaders, conflicts and competing policy proposals.

Analysis does not constitute endorsement.

Models should distinguish between:

**facts → assumptions → model outputs → interpretation → opinion**

whenever practical.

No political actor should receive privileged treatment simply because of their identity.

---

# 9. Human Rights

The project should respect fundamental human rights and civil liberties.

Economic efficiency must not automatically be treated as more important than:

* human dignity;
* freedom;
* privacy;
* equality before the law;
* freedom of expression;
* freedom of movement;
* physical safety;
* democratic participation.

A policy producing a strong economic result may still be ethically unacceptable.

The model should make such trade-offs visible rather than hiding them inside a single "optimal" score.

---

# 10. Avoiding False Precision

Complex social systems cannot be reduced perfectly to a single number.

METAL MONKEY should avoid presenting uncertain predictions as facts.

Where appropriate, outputs should include:

* confidence intervals;
* ranges;
* alternative scenarios;
* sensitivity analysis;
* uncertainty;
* model limitations.

If the available evidence is insufficient, the correct output may be:

> **Insufficient evidence.**

That is preferable to false certainty.

---

# 11. No Single "Optimal" Future

The project should not assume that there is one objectively correct political, economic or ecological future.

Different people and societies may legitimately assign different values to:

* economic growth;
* equality;
* environmental protection;
* security;
* individual freedom;
* technological development;
* cultural preservation.

Where values conflict, the model should expose the trade-off rather than silently selecting a winner.

---

# 12. The Council of 60

The "Council of 60" is an analytical framework, not an actual governing body.

Its dimensions should be treated as perspectives for evaluating scenarios.

No dimension automatically overrides all others.

Where weighting is used, the methodology should explain:

* why the weight was selected;
* who selected it;
* what alternatives were considered;
* how the result changes under different weights.

---

# 13. Geopolitical and Military Analysis

The project may examine geopolitical or military-economic variables when this contributes to legitimate research.

However, the purpose should remain **analysis rather than operational assistance**.

The project should not provide instructions intended to facilitate:

* attacks;
* weapons construction;
* sabotage;
* unauthorized intrusion;
* intelligence collection against individuals;
* evasion of security systems;
* operational targeting.

High-level analysis of conflict and its economic consequences is permitted within this framework.

---

# 14. Environmental Responsibility

Environmental claims should be supported by identifiable evidence whenever possible.

The project should avoid presenting an intervention as "green" merely because it is described that way.

Environmental consequences should be evaluated across the full system, including where relevant:

* resource extraction;
* manufacturing;
* transportation;
* energy consumption;
* waste;
* ecosystem effects;
* lifecycle emissions.

---

# 15. Distributional Effects

A policy that improves an average indicator may still harm particular groups.

Therefore, where data allows, METAL MONKEY should examine:

* who benefits;
* who bears the cost;
* regional differences;
* income differences;
* intergenerational effects;
* short-term versus long-term effects.

"Average improvement" must not automatically be interpreted as "everyone benefits."

---

# 16. Reversibility and Precaution

When a proposed intervention could create large or irreversible consequences, the project should apply greater caution.

Scenario analysis should consider:

* What happens if the policy fails?
* Can it be reversed?
* How quickly?
* Who bears the cost of failure?
* Are there safer alternatives?
* What evidence would justify proceeding?

The larger the potential irreversible harm, the stronger the evidence should be.

---

# 17. Independent Criticism

The project should actively encourage criticism.

Contributors should be able to challenge:

* assumptions;
* datasets;
* methodology;
* ethical conclusions;
* model outputs;
* interpretation.

A successful model is not one that confirms its creator's beliefs.

A successful model is one that makes disagreement easier to investigate.

---

# 18. Reproducibility

Important analytical results should be reproducible whenever legally and technically possible.

A published result should identify:

* the data used;
* the relevant model version;
* important parameters;
* calculation methodology;
* known limitations.

If exact reproduction is impossible because data is unavailable or proprietary, that limitation should be clearly stated.

---

# 19. Security

Security is part of ethics.

The project should follow basic principles including:

* least privilege;
* minimal data collection;
* dependency awareness;
* secure handling of credentials;
* explicit network behaviour;
* code review;
* reproducible builds where practical.

Secrets must never be committed to the repository.

Opaque encoded content should not be used to conceal program behaviour.

---

# 20. Conflicts of Interest

Contributors should disclose significant conflicts of interest when they could reasonably affect interpretation of research.

This is particularly important when research concerns:

* governments;
* political organizations;
* financial institutions;
* military organizations;
* energy companies;
* technology companies;
* environmental organizations.

Disclosure does not invalidate research.

It helps readers evaluate it appropriately.

---

# 21. AI-Assisted Development

If artificial intelligence is used to generate code, analysis, documentation or research material, contributors remain responsible for reviewing the result.

AI-generated content should not automatically be treated as:

* factual;
* unbiased;
* secure;
* mathematically correct;
* ethically acceptable.

Important claims should be independently checked.

---

# 22. Responsible Publication

Before publishing a new model, dataset or capability, contributors should consider:

1. What does this enable?
2. Who could benefit?
3. Who could be harmed?
4. Could the information facilitate abuse?
5. Can the same research goal be achieved with less risk?
6. Are important limitations clearly documented?

When necessary, sensitive implementation details may be withheld while the research concept and methodology remain publicly documented.

---

# 23. The Right to Say "Stop"

Any contributor may raise an ethical concern about a proposed capability or dataset.

A concern should be investigated rather than dismissed simply because the feature is technically possible.

If the project cannot establish that a capability can be developed responsibly, development should pause until the concern is resolved.

---

# 24. Core Principle

METAL MONKEY should follow one fundamental rule:

> **Capability does not create authority.**

A model may become increasingly capable of analysing complex systems.

That does not give it the right to decide what humanity should do.

The project's responsibility is therefore to make analysis:

**transparent, evidence-based, uncertain where appropriate, ethically bounded, and ultimately accountable to humans.**

---

## Final Commitment

METAL MONKEY exists to explore difficult questions, not to claim ownership of their answers.

It should remain:

**Open enough to be examined.
Honest enough to admit uncertainty.
Careful enough to avoid unnecessary harm.
Ambitious enough to investigate difficult problems.
Humble enough to recognize its limitations.**

> **Model the system.
> Expose the assumptions.
> Respect the uncertainty.
> Protect the human.
> Let humans decide.**
