# Constitution: AI/Spec-Driven Book Creation on Physical AI & Humanoid Robotics

## Project Overview
Define how AI systems will collaborate to produce a complete technical book using a specification-driven workflow. Establish rules for writing, structuring, and refining all book chapters, modules, and pages.

## Objectives
- Produce a clear, accurate, professional book.
- Follow specification-first workflow using Spec-Kit Plus.
- Generate Docusaurus-ready Markdown.
- Maintain consistency across chapters (tone, formatting, terminology).
- Support modular writing: each module, chapter, and section must be individually specifiable.
- Ensure content is deployable to GitHub Pages.

## AI Behavior Rules
- Follow all /sp.specify prompts exactly.
- User instructions override all rules.
- Maintain accuracy, avoid hallucinations.
- Produce clean, formatted Markdown suitable for Docusaurus.
- Keep style consistent across entire project.
- Use step-by-step explanations, examples, diagrams when needed.
- Provide corrections or clarifications when specs are unclear.
- Do not introduce new technologies or topics outside the scope unless user asks.

## Output Requirements
- All content must be Docusaurus-compatible Markdown.
- Structure content using:
  - # Title
  - ## Overview
  - ### Concepts
  - ### Steps
  - ### Examples
  - ### Summary

## Tone
- Educational, beginner-friendly, technically correct.
- Clear explanations with practical steps.
- No unnecessary academic complexity.

## Structure
- Each chapter starts from a specification
- Include Objective, example, steps, and a final exercise
- Every Technical Issues section:
    - Inputs, output, architecture, code, Failure mode, safety notes

## Consistency Rules
- Keep terminology, formatting, tone uniform.
- Reuse definitions and concepts across modules.
- Use same code style, same headings, and same structure everywhere.

## Prohibited
- Hallucinated facts or technologies.
- Changing structure without instruction.
- Adding fake citations.
- Producing content outside user specifications.

## Final Authority
User instructions override Constitution → Specifications → AI autonomy.

## Mission
Follow a spec-driven workflow to produce a professional, publish-ready book using Docusaurus, managed through Spec-Kit Plus and deployable on GitHub Pages.

**Version**: 1.0.0 | **Ratified**: 2025-12-12 | **Last Amended**: 2025-12-12
