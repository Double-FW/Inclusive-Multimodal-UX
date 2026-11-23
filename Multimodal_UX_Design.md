# Inclusive Multimodal UX Design

## Purpose

Multimodal UX considers how people perceive information and control experiences through different senses, inputs, devices, and contexts. The design aim is for meaning, choice, state, and task progress to remain available when a person uses a different mode or changes mode during a task.

Multimodal design is not a requirement to use several channels for every interaction. Extra sound, motion, vibration, or prompts can create overload or interfere with assistive technology. Select channels that fit the information, user choice, context, and evidence. Provide alternatives for important information and actions where a single channel would create a barrier.

This guide is product-agnostic. Media-player and Connected TV specifics belong in [Inclusive Media Interfaces](https://github.com/Double-FW/Inclusive-Media-Interfaces); immersive and spatial interaction belongs in [VR/XR/AR Accessibility](https://github.com/Double-FW/VR_XR_and_AR_Accessibility).

## 1. Start from human and contextual variability

People vary in vision, hearing, movement, speech, cognition, attention, memory, and sensory processing. These differences intersect and may change over time. Lighting, noise, movement, fatigue, stress, distraction, connectivity, and the social setting can also change which interaction methods are practical.

Design for variability as an ordinary condition. Do not assume an “average” user, a fixed disability profile, ideal conditions, or that one modality is preferred by everyone in a group.

## 2. Map meaning before choosing channels

For each task, identify:

- what information the person needs;
- what action they can take;
- what state or consequence follows;
- what feedback tells them the action worked;
- what they need to recover, correct, or change their mind.

Then map which available channels can carry that meaning. Aim for comparable access to essential information and actions across relevant modes rather than mechanically duplicating every signal. Define any claim of equivalence against an explicit criterion and supporting evidence. Synchronise alternatives when timing is part of the meaning.

Examples include captions or visual indicators for sound, spoken or tactile access to visual information, and keyboard or voice alternatives to touch gestures. Alternatives must preserve the task’s purpose and important context.

## 3. Support meaningful input choice

Where the product and task allow, support appropriate combinations of keyboard, switch, pointer, touch, voice, eye-gaze, and assistive input. Avoid relying on precision, speed, complex gestures, hover, or one input method as the sole route to an important action.

- Keep interaction order logical and focus visible where applicable.
- Provide simple alternatives to complex gestures.
- Allow interruption and correction.
- Make time limits avoidable or adjustable when feasible.
- Make actions and their consequences clear before commitment.

The available methods depend on the platform. Do not promise an input mode that the product cannot support.

## 4. Design outputs and feedback for the task

Visual, spoken, textual, tactile, and spatial or environmental outputs can each carry useful information. Choose them according to the task and setting.

- Do not communicate essential meaning by colour, motion, sound, or touch alone when an alternative is needed.
- Keep feedback about success, error, progress, warning, listening, processing, and transition understandable and consistent.
- Ensure a user can tell what changed and what to do next.
- Avoid conflicting signals and excessive alerts.
- Offer control over intensity, timing, and optional feedback where appropriate.

## 5. Images, audio, and media meaning

Images, icons, sound, and moving media can carry essential information, context, and emotion. Describe the purpose and meaning that a person needs; avoid descriptions that merely repeat nearby text or add irrelevant detail. Provide text equivalents for meaningful audio and spoken or tactile access to visual information where appropriate. Keep alternatives synchronised when timing affects meaning.

Make access features discoverable, but route player controls, autoplay, captions, audio description, and Connected TV behaviour to [Inclusive Media Interfaces](https://github.com/Double-FW/Inclusive-Media-Interfaces).

## 6. Preserve continuity when modes change

A person may change modality because of preference, context, or interruption. Keep the goal, entered information, location, and current state where possible. Signal changes clearly, allow repetition or review, and provide a route back. Make transitions predictable, continuous, and recoverable.

Do not unexpectedly switch a person to a different modality or take control away. Adaptation should respect the person's choices and available preferences.

## 7. Use familiar patterns and communicate interaction meaning

Consistency helps people learn how controls behave and transfer knowledge across screens and services. A control’s appearance, label, role, state, and result should agree. Icons can reinforce meaning but should not carry essential meaning alone; use clear labels or other cues that communicate the same essential information.

For semantic hierarchy, headings, grouping, landmarks, and programmatic relationships, use the separate [Structural Accessibility and Semantic Design for Multi-Modal Experiences](Structural%20Accessibility%20and%20Semantic%20Design%20for%20Multi-Modal%20Experiences.md) module. That module owns the detailed structure guidance; this guide links to it rather than repeating it.

## 8. Consider cognitive effort and emotional experience

A modality can change the effort, pace, privacy, confidence, and emotional tone of an interaction. Visual scanning may help comparison; spoken output may be useful for sequential information; tactile feedback may confirm an action. These are task considerations, not universal rules about people.

Reduce unnecessary memory demands, ambiguity, and repeated error loops. Use clear options and confirmations in voice interaction, and make recovery easy after a system misunderstanding. For detailed cognitive accessibility and form guidance, use [Cognitive UX Design](https://github.com/Double-FW/Cognitive-UX-Design).

Different modes may use different presentations. Evaluate whether people can reach meaningful outcomes with comparable control, understanding, responsiveness, and effort. Use “equivalent” only when the intended equivalence is explicitly defined and supported; do not infer emotional equivalence or satisfaction.

## 9. Apply the principles across contexts

- **Web:** keep structure and focus meaningful beyond visual layout; provide text equivalents and media alternatives.
- **Mobile:** consider voice, touch, screen-reader use, haptics, reach, and changing environments.
- **Voice:** provide clear choices, confirmations, interruption, repetition, and recovery; do not make speech the only route.
- **Large screens:** consider distance, readable content, clear focus, and minimal navigation effort. TV and media-player specifics route to Inclusive Media Interfaces.

Platform guidance should be adapted to the actual service, hardware, and user context.

## 10. Research, evaluation, and iteration

Test realistic tasks across relevant input/output modes and environments with disabled people and others affected by the design. Include mode changes, interruptions, errors, recovery, and preference changes. Use automated or agent review to identify questions and candidate issues, not as a substitute for user research.

Record whose experience is represented, methods, product versions, context, findings, limitations, and what evidence could change the recommendation. Preserve negative, minority, and contradictory findings; do not average away exclusion or excessive effort.

## 11. A practical design sequence

1. Define the person’s goal, task, and context.
2. Map information, actions, states, consequences, and recovery needs.
3. Identify current and alternative input and output channels.
4. Check whether meaning survives channel changes and interruptions.
5. Design for choice, predictability, feedback, and recovery.
6. Prototype the relevant paths and test with people.
7. Record results, uncertainty, and next changes.

## AI-agent retrieval guidance

Retrieve this guide for general cross-modal design questions. Then route the task:

- detailed structure and programmatic meaning → [Structural Accessibility and Semantic Design](Structural%20Accessibility%20and%20Semantic%20Design%20for%20Multi-Modal%20Experiences.md);
- media controls, Connected TV, and related physical/connected product control → [Inclusive Media Interfaces](https://github.com/Double-FW/Inclusive-Media-Interfaces);
- cognitive accessibility and forms → [Cognitive UX Design](https://github.com/Double-FW/Cognitive-UX-Design);
- immersive interaction → [VR/XR/AR Accessibility](https://github.com/Double-FW/VR_XR_and_AR_Accessibility);
- product-design philosophy and paired perspectives → [Inclusive Product Design Principles](https://github.com/Double-FW/Inclusive-Product-Design-Principles).

Separate source-based guidance from inference and hypothesis. Do not treat synthetic personas, generated designs, or an agent review as evidence from disabled people or as proof of legal conformance.

## Consolidation note

This guide consolidates the repeated foundations and modality frameworks from `Multimodal_UX_Design.md` in [Inclusive and Effective Design](https://github.com/Double-FW/Inclusive_and_Effective_Design). The distinct maturity model and prompt material are retained in companion files in this repository. Media-, TV-, and form-specific material is routed to the specialist repositories above.
