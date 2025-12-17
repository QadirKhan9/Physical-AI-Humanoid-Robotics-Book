# Style Guide and Terminology Reference

## Overview
This document establishes the style guide and terminology reference for the Physical AI & Humanoid Robotics book. It ensures consistency across all chapters and sections.

## Writing Style

### Tone
- Educational and beginner-friendly
- Technically accurate but accessible
- Clear and concise explanations
- Professional but not overly academic
- Encourage experimentation while emphasizing safety

### Voice
- Use active voice wherever possible
- Address the reader directly using "you"
- Avoid jargon unless clearly defined
- Explain complex concepts with analogies when appropriate

### Structure
- Follow the standard chapter template:
  - # Chapter Title
  - ## Overview
  - ### Concepts
  - ### Steps
  - ### Examples
  - ### Summary
  - ### Exercises
- Include Technical Issues section with:
  - Inputs
  - Outputs
  - Architecture
  - Code
  - Failure Modes
  - Safety Notes

## Formatting Standards

### Headings
- Use sentence case for all headings (capitalize only the first word and proper nouns)
- H1 for chapter titles
- H2 for major sections (Overview, Summary)
- H3 for subsections (Concepts, Steps, Examples)
- H4 for sub-subsections when needed

### Code and Technical Elements
- Use inline code formatting (`code`) for technical terms, file names, and variable names
- Use code blocks for multi-line code examples with appropriate language identifiers
- Numbered lists for sequential steps
- Bulleted lists for non-sequential items or options

### Images and Diagrams
- Include descriptive alt text for all images
- Place images close to the relevant text
- Use captions to explain the significance of diagrams

## Terminology Reference

### Core Terms

#### Physical AI
- Definition: Artificial intelligence systems that interact with the physical world through sensors and actuators
- Usage: Always capitalize as "Physical AI" when referring to the field; lowercase "physical AI" when used as an adjective

#### Humanoid Robot
- Definition: A robot with a human-like body structure, typically featuring a head, torso, arms, and legs
- Usage: Two words, not hyphenated

#### Actuator
- Definition: A component responsible for moving or controlling a mechanism or system
- Plural: actuators

#### Sensor Fusion
- Definition: The process of combining sensory data from multiple sources to improve reliability and accuracy
- Usage: Two words, not hyphenated

#### Degrees of Freedom (DOF)
- Definition: The number of independent movements a mechanical system can make
- Usage: Always abbreviate as "DOF" after the first full spelling in each chapter

#### Control Loop
- Definition: A process that continuously monitors and adjusts a system to achieve desired behavior
- Usage: Two words, not hyphenated

#### Forward Kinematics
- Definition: The calculation of the end-effector position based on known joint angles
- Usage: Two words, capitalized only at the beginning of sentences

#### Inverse Kinematics
- Definition: The calculation of required joint angles to achieve a desired end-effector position
- Usage: Two words, capitalized only at the beginning of sentences

#### Center of Mass (CoM)
- Definition: The point where the total mass of a body is considered to be concentrated
- Usage: Abbreviate as "CoM" after first full spelling in each chapter

#### Balance Control
- Definition: Systems and algorithms designed to maintain a robot's stability
- Usage: Two words, not hyphenated

### Technical Conventions

#### Notation
- Variables: italicized (e.g., *θ*, *x*, *y*)
- Matrices: bold uppercase (e.g., **T**, **J**)
- Vectors: bold lowercase (e.g., **v**, **p**)

#### Units
- Always specify units when mentioning measurements
- Use SI units where possible
- Use consistent notation (e.g., meters as "m", seconds as "s")

#### Algorithms
- Capitalize proper names of algorithms (e.g., PID controller, Kalman filter)
- Use consistent pseudocode formatting

## Cross-Reference Guidelines

### Internal Links
- Link to other chapters using relative paths
- Use descriptive link text rather than generic phrases like "click here"
- Verify all internal links during review process

### Citations
- Use consistent citation format throughout the book
- Include author, title, publication date, and URL when applicable
- Group related citations together when possible

## Quality Assurance Checklist

Before finalizing any content, ensure:
- [ ] All technical terms are defined upon first use
- [ ] Concepts are explained with examples when possible
- [ ] Safety considerations are addressed
- [ ] Code examples are tested and functional
- [ ] All cross-references are valid
- [ ] Figures have appropriate captions
- [ ] Exercises have reasonable difficulty progression
- [ ] Chapter follows the required structure template