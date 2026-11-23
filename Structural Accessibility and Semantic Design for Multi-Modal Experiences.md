# Structural Accessibility and Semantic Design for Multi-Modal Experiences

## Purpose and relationship to multimodal UX

This module covers how information structure communicates meaning, hierarchy, location, and available actions. It focuses on headings, grouping, landmarks, navigation, roles, states, and semantic relationships that remain understandable beyond visual presentation.

For general input/output modality choice, transitions, sensory feedback, and experience quality, use [Inclusive Multimodal UX Design](Multimodal_UX_Design.md). This file keeps the detailed semantic-structure guidance in one place and avoids repeating the general multimodal framework.

## 1. Structure communicates meaning and orientation

A useful structure helps someone understand what an experience is about, where they are, what parts exist, how those parts relate, and what they can do next. People may encounter structure visually, sequentially, through assistive technology, or through a combination of methods.

Plan information architecture before visual styling. Start with a conceptual outline, assign each page or screen a clear purpose, group related information, and introduce complexity progressively. The visual grouping and the semantic grouping should express the same relationships where possible.

A practical check is to ask whether someone unfamiliar with the interface can predict where information belongs and how to find it.

## 2. Headings and content hierarchy

Headings are both labels and navigation. They should describe the section that follows and reflect relationships between ideas, not just preferred visual sizes.

- Build a logical outline from main topics to subtopics.
- Use concise, descriptive headings.
- Avoid skipping levels when it misrepresents the content relationship.
- Test the outline by reading only the headings. They should communicate the experience’s structure and purpose.

## 3. Containers, regions, and grouping

A container should represent a meaningful area, such as navigation, main content, supporting information, or actions—not merely a visual box. Group related items and make boundaries between unrelated tasks clear.

Define major regions before detailed layout. Keep the purpose of each area consistent across screens. Use nested groupings only when they clarify task flow rather than add extra navigation or complexity.

## 4. Landmarks and orientation

Landmarks act as signposts that help people move between major areas and skip repeated material. Establish a small, clear set of regions, use them consistently, and identify the primary content area. Avoid creating several indistinguishable regions with the same purpose.

An orientation map can record each region’s purpose and where it appears across the experience. Test whether users can locate major areas without relying on visual scanning alone.

## 5. Navigation and route changes

Navigation should communicate location, context, and progression. When a route or screen changes, provide clear confirmation through the user’s available channels and preserve relevant context.

- Keep navigation patterns predictable.
- Indicate current location and available next steps.
- Preserve task state where possible.
- Provide a return or recovery route.
- Ensure a change is communicated even when visual transition effects are unavailable.

Treat a journey as continuous, not as unrelated screens.

## 6. Roles, states, and interaction meaning

People need to know what an element is, what it does, its current state, and what will happen after activation. Keep visual presentation, labels, programmatic meaning, state, and result aligned.

Use familiar interaction patterns unless there is a clear reason to depart from them. Make selected, expanded, disabled, loading, and other relevant states perceivable through suitable cues. A useful design activity is to map each control’s purpose, role, available action, state, and feedback.

## 7. Structure across modalities

Do not make visual position, colour, or grouping the only way to understand relationships. Ensure that reading order, labels, headings, regions, and interaction sequence communicate the same structure when the visual arrangement is unavailable or encountered sequentially.

Use [Inclusive Multimodal UX Design](Multimodal_UX_Design.md) for guidance on sensory equivalents, input flexibility, feedback channels, and mode transitions. This module addresses the structural relationships those channels need to convey.

## Design and agent review prompts

When reviewing or generating a design, ask:

- What is the main purpose of this screen or page?
- Do headings alone reveal a useful outline?
- Do groupings and regions express real relationships?
- Can a person locate the main content and understand where they are?
- Do route changes preserve context and announce the new location?
- Do controls communicate their role, state, action, and result?
- Would the structure still make sense without visual placement or styling?

An AI agent should identify which claims come from the source, which are design inferences, and what should be tested. Do not claim that a semantic outline alone proves accessibility or conformance.

## Source note

This module consolidates the structure-specific material from `Structural Accessibility and Semantic Design for Multi-Modal Experiences.md` in [Inclusive and Effective Design](https://github.com/Double-FW/Inclusive_and_Effective_Design). General multimodal principles and repeated prompt templates are routed to the companion guide and agent prompt resource.
