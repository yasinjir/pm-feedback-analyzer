# Component Map v1 — SignalForge

## Global components

### 1. Top navigation
Used on:
- Landing Page
- App screens

Purpose:
- show workflow position
- allow movement across available steps

### 2. Page header
Used on:
- Create Project
- Input Workspace
- Insights
- Report
- PRD Studio
- Task Builder

Purpose:
- display page title
- display page subtitle
- display status if needed

### 3. Primary CTA button
Used on all core screens

Purpose:
- move the workflow forward

### 4. Secondary CTA button
Used on all core screens

Purpose:
- support editing, going back, or refining

### 5. Status badge
Used on:
- Insights
- Report
- PRD
- Tasks

Purpose:
- show state such as draft, generated, current step

---

## Screen-specific components

## Create Project

### Components
- text input
- textarea
- form section label
- validation message
- action row

### Required fields
- Project name
- Analysis goal

---

## Input Workspace

### Components
- input guidance block
- large textarea
- upload area
- supported input examples
- analysis CTA row

### Notes
The textarea is a core surface and should be visually prominent.

---

## Insights View

### Components
- summary insight card
- section cards
- insight list blocks
- priority signal block
- re-run / refine action row

### Required sections
- Themes
- Pain points
- Feature requests
- Repeated signals
- Priority cues
- Summary insight

---

## Report View

### Components
- executive summary block
- finding cards or sections
- problem list
- opportunity list
- recommended focus block
- action row

### Notes
This page should use a reading-oriented layout.

---

## PRD Studio

### Components
- document section block
- section title
- editable text block
- draft status indicator
- action row

### Required document blocks
- Problem statement
- Goals
- Target users
- Scope
- Non-goals
- Success metrics
- Risks
- Open questions

---

## Task Builder

### Components
- work bucket group
- task block
- user story block
- acceptance criteria list
- copy/export row

### Notes
This screen should optimize for clarity and handoff.

---

## Utility components

### 1. Empty state block
Purpose:
- explain what is missing
- guide the next action

### 2. Loading state block
Purpose:
- show generation in progress

### 3. Error state block
Purpose:
- explain failure simply
- allow retry

### 4. Copy block
Purpose:
- let user quickly copy output text

### 5. Section divider
Purpose:
- separate output groups clearly

---

## Priority components for MVP
These components should be designed first:

1. Page header
2. Large input area
3. Insight section card
4. PRD document block
5. Task group block
6. Action row
7. Empty state block
8. Loading state block

## Design principle
Every component should reinforce the feeling that SignalForge is a workflow system, not just a content generator.
