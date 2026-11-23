# Inclusive Multimodal UX

Guidance for designing experiences that people can perceive, understand, and control across relevant input and output modes, devices, and contexts.

## Purpose and scope

This repository supports designers, researchers, product teams, engineers, accessibility specialists, and AI agents working under human authority. It helps teams consider modality choice, continuity, sensory and interaction flexibility, semantic structure, and inclusive experience.

Multimodal design does not mean adding several channels to every interaction. It means ensuring that important meaning, choice, state, and task progress remain available through suitable methods. People’s preferences and contexts vary; extra sound, motion, vibration, or prompts can create overload or conflict with assistive technology.

This material is design guidance. It is not a legal interpretation, accessibility conformance scheme, validated maturity score, or evidence that a product works for a population.

## Repository contents

| File | Purpose |
|---|---|
| [Multimodal_UX_Design.md](Multimodal_UX_Design.md) | Main guide to modality choice, meaning, input/output options, feedback, transitions, context, research, and iteration. |
| [Structural Accessibility and Semantic Design for Multi-Modal Experiences.md](Structural%20Accessibility%20and%20Semantic%20Design%20for%20Multi-Modal%20Experiences.md) | Detailed guidance on information hierarchy, grouping, landmarks, navigation, roles, states, and semantic relationships. |
| [Multimodal_Design_Maturity_Model.md](Multimodal_Design_Maturity_Model.md) | Reflection and planning prompts for organisational capability; not a validated instrument. |
| [Multimodal_UX_Agent_Prompt_Guide.md](Multimodal_UX_Agent_Prompt_Guide.md) | Reusable prompt components for design review and research planning. AI output remains a draft or hypothesis. |
| [AGENTS.md](AGENTS.md) | Metadata and operating rules for AI agents: evidence, terminology, scope, privacy, and human authority. |
| [LICENSE](LICENSE) | The repository’s MIT licence. |

## How to use this guidance

Start with the main guide for cross-modal questions. Use the semantic module for detailed structure and programmatic relationships. Use the maturity model to structure discussion, not to claim measured organisational performance. Treat prompt-guide output as a hypothesis to be checked.

For a design or research question:

1. Define the person’s goal, task, context, and stakes.
2. Map the meaning, actions, state, consequences, feedback, and recovery the task requires.
3. Identify which modes the actual service supports and which are relevant.
4. Check that choices, essential information, and task progress remain available when a person changes mode or context.
5. Record evidence, assumptions, limitations, missing perspectives, and the next useful evaluation.

Research and design review should include relevant disabled people and their usual interaction methods when decisions depend on those experiences. Synthetic personas, simulated tasks, checklists, and automated reviews can help generate questions; they are not participant evidence and do not establish conformance.

## Language, comparison, and evidence

Use [Double-FW Terminology and Principles](https://github.com/Double-FW/Terminology-and-Principles), starting with [its current position](https://github.com/Double-FW/Terminology-and-Principles/blob/main/START_HERE.md), for current term scope and status. Glossary entries have individual review states; do not assume every entry is adopted.

Keep “comparable” and “equivalent” distinct. Describe what is being compared and how. Do not claim equivalence unless the criterion is defined and the evidence supports it. Different modes may use different presentations while supporting meaningful access to the task.

Separate source guidance, participant report, observed behaviour, quantitative result, interpretation, hypothesis, and synthetic planning material. State the method and context. Do not infer an individual’s feelings or preferences, a disability group’s preferences, or population prevalence from a design model or a small number of observations.

## Specialist Double-FW repositories

These linked repositories were checked as public:

- [Inclusive Media Interfaces](https://github.com/Double-FW/Inclusive-Media-Interfaces) for TV, streaming, playback, media access services, and connected physical control.
- [Cognitive UX Design](https://github.com/Double-FW/Cognitive-UX-Design) for cognitive accessibility and detailed form journeys.
- [VR/XR/AR Accessibility](https://github.com/Double-FW/VR_XR_and_AR_Accessibility) for immersive and spatial interaction.
- [Inclusive Product Design Principles](https://github.com/Double-FW/Inclusive-Product-Design-Principles) for design philosophy, paired perspectives, and research governance.
- [QA Accessibility Testing](https://github.com/Double-FW/QA_Accessibility_Testing) for requirements-based testing and QA evidence.
- [Terminology and Principles](https://github.com/Double-FW/Terminology-and-Principles) for terminology and recorded review status.

Use the specialist source for its detailed guidance; do not duplicate a complete specialist guide here. Verify specific linked files when adding deep links.

## Source and consolidation

The main guide consolidates overlapping multimodal frameworks and repeated prompt templates from the [original source path in Inclusive and Effective Design](https://github.com/Double-FW/Inclusive_and_Effective_Design/blob/main/Multimodal_UX_Design.md). That source path is now a migration pointer to this repository. The distinct maturity-model and prompt content remains in companion files. Semantic structure remains a separate module, linked from the main guide rather than repeated there. Its source path is the [semantic-structure migration pointer](https://github.com/Double-FW/Inclusive_and_Effective_Design/blob/main/Structural%20Accessibility%20and%20Semantic%20Design%20for%20Multi-Modal%20Experiences.md).

Preserve provenance when revising consolidated content. Linked and quoted source material remains subject to its own attribution and licence terms; this repository’s MIT licence does not change those terms.

## Licence

This repository uses the MIT licence, as stated in [LICENSE](LICENSE).
