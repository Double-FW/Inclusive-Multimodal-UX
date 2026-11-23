---
title: "Agent Guidance: Inclusive Multimodal UX"
version: "1.0.0"
author: "Double FW"
date: "2026-11-23"
license: "MIT"
language: "en-GB"
repository: "https://github.com/Double-FW/Inclusive-Multimodal-UX"
artifact_type: "agent-governance"
use_case: "Guide AI-assisted retrieval, design analysis, research planning, review, and maintenance of this repository."
status: "active"
review:
  status: "owner_review_required"
  owner: "Repository maintainer"
  trusted_for_agent_use: "after_owner_review"
license_source: "LICENSE"
conceptual_entities:
  task_context: "A person's goal, task, environment, device, interaction methods, and constraints."
  modality: "A way information is perceived or an action is performed; not a fixed trait of a person."
  evidence: "Sourced or observed information distinguished from report, interpretation, inference, hypothesis, and synthetic material."
  design_decision: "A human-owned choice with rationale, trade-offs, evidence, and follow-up."
agent_policy:
  required:
    - "Read README.md and the relevant source file before making repository-specific claims."
    - "Use terminology according to the scope and status recorded in Terminology and Principles."
    - "Keep sourced guidance, observed evidence, participant reports, interpretation, hypotheses, and synthetic material distinct."
    - "Preserve choice and individual variation; do not infer one modality preference for a disability group."
    - "Route specialist questions to the owning public Double-FW repository."
    - "State assumptions, uncertainty, evidence limits, and what would change the recommendation."
  human_authorization_required:
    - "Contact participants, deploy research, or run live-user experiments."
    - "Access or publish identifiable or sensitive research/customer data."
    - "Change a live product, make a consequential product decision, or make a legal/conformance claim."
---

# Agent Guidance: Inclusive Multimodal UX

## Purpose and source routing

Use this repository for general design questions about experiences across sensory, input, and output modes, devices, and contexts. It is design guidance, not a legal interpretation, conformance result, or substitute for research with people.

Read [README.md](README.md), then retrieve the source needed for the task:

- [Multimodal UX Design](Multimodal_UX_Design.md): general modality choice, continuity, input/output flexibility, feedback, and evaluation.
- [Structural Accessibility and Semantic Design](Structural%20Accessibility%20and%20Semantic%20Design%20for%20Multi-Modal%20Experiences.md): detailed hierarchy, grouping, landmarks, navigation, roles, states, and relationships.
- [Multimodal Design Maturity Model](Multimodal_Design_Maturity_Model.md): an unvalidated reflection and planning model.
- [Multimodal UX Agent Prompt Guide](Multimodal_UX_Agent_Prompt_Guide.md): reusable prompt components; generated output is a draft, not evidence.

For current Double-FW terminology, consult [Terminology and Principles](https://github.com/Double-FW/Terminology-and-Principles), beginning with [START_HERE.md](https://github.com/Double-FW/Terminology-and-Principles/blob/main/START_HERE.md). Check each relevant entry's status and scope. Approval of selected decisions is not blanket approval of all glossary wording.

## Evidence and terminology

- Begin with the person’s goal, task, context, and the decision the work needs to support.
- Label sourced guidance, participant reports, observed behaviour, quantitative results, interpretation, hypotheses, and synthetic examples distinctly.
- Never present generated personas, simulated tasks, automated reviews, or checklists as evidence from disabled people.
- Do not infer emotion, disability, preference, comprehension, or population impact from behaviour alone.
- Preserve distinctions between user, customer, and participant; need and preference; observation, estimate, and hypothesis; and comparable and equivalent.
- Describe the intended comparison when using “comparable” or “equivalent”; do not treat them as synonyms or assert equivalence without a defined criterion and supporting evidence.
- Do not turn design guidance into a legal, regulatory, or conformance conclusion.

## Review method

For a task or journey:

1. Identify the goal, stakes, context, and relevant interaction methods.
2. Map information, actions, state, consequences, feedback, and recovery.
3. Identify which modes are supported, required, optional, or unavailable in the actual product.
4. Check transitions, interruptions, errors, correction, privacy, retained context, and user control.
5. Check semantic structure and programmatic relationships separately from visual appearance.
6. Compare task outcomes, control, effort, and understanding across relevant modes without averaging away barriers.
7. Recommend the smallest useful next step and state how it could be evaluated.

Do not add sensory channels automatically. Choose alternatives according to the meaning, task, context, user control, platform support, and evidence. Avoid overload, conflicting signals, and unexpected mode changes.

## Scope routing

Use these public specialist repositories for detailed guidance:

- TV, streaming, playback, media access services, and connected physical controls: [Inclusive Media Interfaces](https://github.com/Double-FW/Inclusive-Media-Interfaces).
- Cognitive accessibility and form journeys: [Cognitive UX Design](https://github.com/Double-FW/Cognitive-UX-Design).
- Immersive and spatial interaction: [VR/XR/AR Accessibility](https://github.com/Double-FW/VR_XR_and_AR_Accessibility).
- Design philosophy, paired perspectives, and research governance: [Inclusive Product Design Principles](https://github.com/Double-FW/Inclusive-Product-Design-Principles).
- Requirements-based testing and QA evidence: [QA Accessibility Testing](https://github.com/Double-FW/QA_Accessibility_Testing).

Retrieve the owning source rather than copying its full specialist guidance here.

## Human authority, privacy, and maintenance

Agents may retrieve sources, structure questions, draft options, and analyse evidence supplied for the task. A human must authorise participant contact, research deployment, live-user experiments, access to identifiable or sensitive data, production changes, acceptance of material risk, and publication of consequential claims.

Keep personal data, credentials, identifiable customer records, raw recordings, and transcripts out of this public repository. Minimise and de-identify evidence; use approved access-controlled storage where necessary.

Before proposing an edit, check for broken or non-public links, duplicated or contradictory material, unsupported universal or causal claims, truncation, and provenance. Preserve attribution and source-specific licence terms; this repository’s MIT licence does not relicense linked content. Keep audit and test reports out of the repository unless explicitly requested.
