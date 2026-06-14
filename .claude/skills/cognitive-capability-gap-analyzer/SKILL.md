---
name: cognitive-capability-gap-analyzer
version: 1.0.0
description: "A meta-skill that discovers missing cognitive capabilities within an AI agent ecosystem by systematically mapping skill inventory, classifying cognitive functions, and generating novel skill opportunities."
---

# Cognitive Capability Gap Analyzer (CCGA)

## Purpose

A meta-skill that discovers missing cognitive capabilities within an AI agent ecosystem.

Unlike traditional analysis tools that focus on what skills exist, CCGA focuses on what cognitive functions are absent, underrepresented, or insufficiently developed.

Objective: systematically generate, evaluate, and prioritize novel skill opportunities.

## Core Principle

Most skill ecosystems evolve through incremental additions.

CCGA asks:

"What forms of reasoning are impossible or poorly supported within this ecosystem?"

instead of:

"What skills are available?"

## Analysis Pipeline

### Phase 1: Skill Inventory Mapping

- Analyzes all available skills.
- Extracts objectives, inputs, outputs, tool usage patterns, reasoning patterns, domain specialization, and dependency relationships.
- Produces a complete ecosystem map.

### Phase 2: Cognitive Function Classification

Maps each skill to cognitive functions:

- Information Gathering: search, retrieval, extraction
- Knowledge Transformation: summarization, translation, classification
- Decision Support: evaluation, recommendation, prioritization
- Predictive Reasoning: forecasting, scenario generation, trend estimation
- Reflective Reasoning: self-critique, assumption analysis, error detection
- Adversarial Reasoning: counterarguments, red-team analysis, failure simulation
- Meta-Cognition: reasoning audits, confidence evaluation, knowledge boundary detection

### Phase 3: Capability Gap Detection

Identifies cognitive capabilities that are:

- Completely absent
- Rarely represented
- Weakly represented
- Fragmented across multiple skills

Gap categories:

- Structural Gaps: capability does not exist.
- Coverage Gaps: capability exists, but only for limited domains.
- Quality Gaps: capability exists, but performs poorly.
- Integration Gaps: multiple skills exist, but cannot cooperate effectively.

### Phase 4: Blind Spot Discovery

Hidden assumptions embedded within the ecosystem.

Key questions:

- What assumptions are never challenged?
- Which reasoning styles dominate?
- Which alternative frameworks are ignored?
- Which failure modes are never simulated?
- Which kinds of uncertainty are never measured?

### Phase 5: Novel Skill Generation

For each identified gap, CCGA generates candidate skills with:

- Name
- Purpose
- Input schema
- Output schema
- Example use cases
- Risk assessment
- Implementation complexity
- Expected ecosystem impact

### Phase 6: Adversarial Evaluation

Every generated skill is challenged.

Key questions:

- Does this skill really already exist indirectly?
- Can another skill already perform this task?
- Is the capability genuinely useful?
- Can the skill produce harmful outputs?
- Is the capability legally or ethically problematic?

Weak proposals are discarded.

### Phase 7: Ecosystem Evolution Forecasting

Predicts:

- Which gaps will become important next.
- Which skills are likely to become obsolete.
- Which emerging capabilities deserve investment.

## Example Generated Skills

- Assumption Auditor
- Epistemic Risk Analyzer
- Counterfactual Explorer
- Reasoning Failure Simulator
- Paradigm Challenger

## Safety Design

CCGA does not generate malware, assist cyber intrusion, produce illegal instructions, facilitate fraud, or recommend harmful activities. It evaluates opportunities at the cognitive level rather than the operational level.
