# Hi, I’m Gazali Ahmad

I work in systems analysis across data, operations, and human-centered environments where decisions must hold up under constraint, ambiguity, and imperfect information.

My focus is on understanding the upstream conditions that shape downstream outcomes. In practice, this means working with data that is incomplete, delayed, or distorted by the systems that produce it, including healthcare, education, and regulated settings.

Rather than optimizing metrics or models in isolation, I aim to reduce decision risk by identifying where assumptions, proxies, or statistically “better” models create confidence that is not supported by operational reality. I am especially interested in failure modes where analytical rigor masks fragility instead of revealing it.

Primary writing and work overview: [gazali.one](https://gazali.one)

---

## Published Works

### **day-boundary**  
[![npm version](https://img.shields.io/npm/v/day-boundary.svg)](https://www.npmjs.com/package/day-boundary)

Handles day boundaries in systems where timestamps, reporting cutoffs, and operational time do not align.

Relevant when:

- Your “day” does not start at midnight (e.g. 4AM cutoffs)
- You group data by day across timezones
- Your timestamps arrive late, batched, or misaligned
- You’ve written custom date logic and hit edge cases

---

- npm: https://www.npmjs.com/package/day-boundary  
- repo: https://github.com/GazaliAhmad/day-boundary

### time-window-classifier (twc)

Reference CLI demonstrating how `day-boundary` is applied to real event data.

Shows:

- JSONL-based event processing
- classification into operational windows with non-midnight boundaries
- behavior across DST transitions (e.g. 25-hour windows)

Use this when:

- you want to see how `day-boundary` fits into a data pipeline
- you need a concrete end-to-end example, not just library usage

- repo: https://github.com/GazaliAhmad/time-window-classifier
 
---
### **causal-order**
[![npm version](https://img.shields.io/npm/v/day-boundary.svg)](https://www.npmjs.com/package/causal-order)

npm: https://www.npmjs.com/package/causal-orderrepo: https://github.com/GazaliAhmad/causal-order

Models causal dependency across events when timestamps alone are insufficient to determine execution sequence.

Built for environments where:

Events arrive late, duplicated, or out of sequence

Multiple systems generate conflicting timelines

Operational truth depends on dependency resolution, not clock order

Pipelines require deterministic replay under partial failure

Core ideas:

Distinguishes temporal order from causal order

Preserves dependency chains under asynchronous execution

Supports replay-safe reconstruction of event sequences

Makes hidden ordering assumptions explicit and testable

Use this where:

Timestamp sorting produces misleading analytical conclusions

Distributed systems require stable reconstruction logic

Event-driven pipelines need dependency-aware processing

Operational investigations depend on reproducible sequencing

This package reflects a broader analytical position used throughout this GitHub:

Observed order is not always execution truth.

In constrained systems, causality often matters more than chronology.

---

## How to Read This GitHub

This GitHub documents how I evaluate analytical trade-offs, system behavior, and decision risk under real-world constraints.

Some work is published under corporate ownership and is intentionally not mirrored here.

Repositories developed under Right Business Pte. Ltd. are maintained separately: [RightBusiness GitHub](https://gazali.one/gitb)

It is a record of how I:

- Reason under operational and data constraints  
- Evaluate analytical trade-offs and failure modes  
- Prioritize interpretability, stability, and decision integrity over superficial performance  

Some repositories are technical. Others focus on analytical judgment.  
The unifying theme is **process integrity over headline metrics**.

This repository collection represents the **systems layer** of my work, focusing on analytical models, decision framing, and controlled AI behavior.

Primary analytical case study:

Model Selection Under Constraint

---

## Primary Case: Model Selection Under Constraint

### Model Selection Under Constraint  
📌 https://github.com/GazaliAhmad/diabetes-ml-faceoff

This case study examines model selection in a healthcare-adjacent context where interpretability, stability, and decision risk matter more than marginal accuracy gains.

The work documents:

- How failure modes and interpretability shaped the final model choice  
- Why statistically attractive models were rejected due to risk and fragility  
- How small, ambiguous datasets change what “good” modeling actually means in practice  

The emphasis is not on model performance alone, but on whether the model’s behavior would remain defensible under real-world scrutiny.

This repository best reflects how I make analytical decisions when outcomes matter.

---

## Supporting Evidence (Capability Context)

The following repositories provide supporting context for my analytical and systems capability:

### Titanic Survival & Economic Analysis  
Demonstrates how variables only gain meaning within economic and social context, not as isolated predictors.

### COVID-19 Reporting Artefacts & False Signals  
Examines global COVID-19 datasets to identify reporting distortions, boundary misalignment, and false causal assumptions commonly produced by public health data.

The analysis highlights how delayed disclosure, administrative aggregation, and proxy variables (e.g. hospital beds, smoking prevalence) can generate misleading conclusions if treated as direct epidemiological signals.

The emphasis is on preventing confident but incorrect conclusions, rather than maximizing descriptive completeness.

### AI Persona Design (Dr. Greyson Rouhe)  
Explores behavioral constraints, guardrails, and controlled interaction in LLM systems, with an emphasis on safety, failure modes, and predictable system behavior.

These projects are not presented as highlights, but as **evidence of breadth, execution, and judgment across domains**.

---

## Background (Brief)

My background spans frontline operations, enterprise systems support, system integration, and applied analytics.

This trajectory is intentional. It is why I treat data as something generated by systems and human behavior, not as an abstract artifact detached from operational reality.

---

## Current Focus

I am open to roles involving:

- Systems Analysis  
- Applied analytics in operational or regulated environments  
- Context-heavy analytical work where judgment, constraint, and decision integrity matter  

---

## Contact

You can contact me using this form: [gazali.one/contact](https://gazali.one/contact)
