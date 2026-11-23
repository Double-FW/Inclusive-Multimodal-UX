# Multimodal UX Agent Prompt Guide

Use these prompt components to ask an AI system for structured design support. A generated response is a hypothesis or draft, not user research, technical verification, or evidence of conformance.

## Shared instruction

> Design for varied sensory, motor, cognitive, language, and contextual needs. Start from the person’s task and intended outcome. Identify suitable input and output methods, preserve meaning and state when a mode changes, provide user control and recovery, and state assumptions, evidence, and limitations. Do not assume a disability group has one preference. Do not present synthetic personas or simulated tasks as research.

Add the following task-specific prompt only when relevant.

## Content, semantics, and navigation

> Review the information structure. Propose a clear heading hierarchy, meaningful groupings, orientation cues, and route-change feedback. Explain how the relationships remain understandable without relying on visual placement. Refer to the semantic-structure module for detailed guidance.

## Input flexibility

> Map each important action to suitable supported input methods. Identify precision, speed, gesture, focus, or timing assumptions. Suggest alternatives and recovery paths without claiming the platform supports a method unless confirmed.

## Touch and physical interaction

> Review target size, spacing, reach, posture, accidental activation, and gesture dependency in the stated device context. Identify what should be tested with people using varied motor methods.

## Keyboard, switch, and focus

> Describe a logical interaction order, clear current-focus feedback, operation without a pointer, and recovery from unexpected content or focus changes. Identify any assumptions about switch or assistive-input support.

## Voice and conversation

> Design clear choices, concise prompts, confirmation, interruption, repetition, and recovery from misrecognition. Provide a non-voice route for important tasks where the service supports one. Explain memory and privacy demands.

## Icons and visual symbols

> Identify where an icon may be unfamiliar, culturally ambiguous, or insufficient without a label. Keep essential meaning available through text or another suitable cue.

## Feedback and recovery

> Map success, error, progress, warning, and transition states. Show how each state is communicated through suitable channels without overloading the user. Include a clear next step and a way to recover.

## Context and modality choice

> Review how lighting, noise, motion, fatigue, stress, interruption, and shared use could affect the task. Offer user-controlled alternatives and identify which conditions need research rather than assuming automatic adaptation.

## Interaction traps

> Inspect dialogs, overlays, embedded controls, and sequential flows for ways a person could become stuck. Describe an accessible exit, retained context, and a return path for each relevant state.

## Research and evaluation

> Propose realistic tasks for evaluating the design across relevant modes and contexts. Separate observed evidence, source-based claims, inference, and hypotheses. Identify participant groups and situations that are missing; do not invent research findings.

## Routing for specialist topics

- TV, streaming, playback controls, media access services, and physical/connected product control: use [Inclusive Media Interfaces](https://github.com/Double-FW/Inclusive-Media-Interfaces).
- Cognitive accessibility and detailed form journeys: use [Cognitive UX Design](https://github.com/Double-FW/Cognitive-UX-Design).
- Immersive and spatial interaction: use [VR/XR/AR Accessibility](https://github.com/Double-FW/VR_XR_and_AR_Accessibility).
- Wider design philosophy and paired perspectives: use [Inclusive Product Design Principles](https://github.com/Double-FW/Inclusive-Product-Design-Principles).

For a multimodal review, ask the agent to return: task and context; input/output map; meaning and state risks; possible changes; evidence needed; assumptions and limitations; and specialist sources consulted.
