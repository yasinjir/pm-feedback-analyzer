# Prototype Screen Pack v3 — SignalForge

## Purpose
Define the final workflow screen and completion layer for the first believable SignalForge prototype.

This pack includes:
1. Task Builder
2. Copy / export behavior
3. Final workflow completion state

These parts complete the full storyline:
feedback → insights → report → PRD → tasks

---

# 1. Task Builder

## Screen goal
Turn the PRD draft into execution-ready work that feels useful for delivery planning and engineering handoff.

## Page title
Task draft

## Page subtitle
SignalForge converted the PRD into execution-ready work items for delivery planning.

## Primary CTA
Copy tasks

## Secondary CTA
Back to PRD

## Optional tertiary CTA
Complete workflow

## Main sections
1. Page header
2. Work buckets
3. Task list
4. User stories
5. Acceptance criteria
6. Action row

---

## Work buckets

### Block title
Work buckets

### Demo content

#### Work bucket 1
Match join flow

#### Work bucket 2
Reminder and confirmation system

#### Work bucket 3
Session visibility

#### Work bucket 4
Search and filtering

---

## Task list

### Block title
Tasks

### Demo content

#### Match join flow
- Audit current join flow steps
- Identify removable or mergeable steps
- Propose simplified join interaction
- Define success and failure states
- Prepare acceptance criteria for streamlined flow

#### Reminder and confirmation system
- Audit current reminder timing logic
- Define improved reminder timing rules
- Add clearer confirmation state messaging
- Define reminder edge cases
- Prepare acceptance criteria for reminder reliability

#### Session visibility
- Design upcoming and past session visibility model
- Define information hierarchy for session hub
- Clarify where match state should appear
- Prepare acceptance criteria for discoverability improvements

#### Search and filtering
- Identify current filter limitations
- Define new filter fields such as skill level
- Improve search result clarity
- Prepare acceptance criteria for filter usage

---

## User stories

### Block title
User stories

### Demo content
- As a player, I want to join a match in fewer steps so I can complete the action faster.
- As a player, I want reliable reminders so I do not miss scheduled sessions.
- As a player, I want to clearly see whether a match is confirmed so I know what to expect.
- As a player, I want better search filters so I can find relevant players more efficiently.

---

## Acceptance criteria

### Block title
Acceptance criteria

### Demo content
- The join flow removes unnecessary steps and keeps the path clear.
- Reminder timing is triggered early enough for user action.
- Match confirmation state is visible in relevant session surfaces.
- Users can filter search results using more specific criteria.

---

## Empty state
Task output has not been generated yet.

## Loading state
Generating task draft...

## Success state
Task draft generated successfully.

## Error state
Task generation failed. Please try again.

## UX notes
- This screen should feel structured and delivery-oriented
- Grouping matters more than density
- The output should feel easy to hand off
- It should look more like planning material than AI output

---

# 2. Copy / Export behavior

## Purpose
Allow the user to quickly reuse SignalForge outputs outside the product.

## Scope for v1
The prototype does not need real export files.
It only needs believable export-ready interactions.

## Supported outputs in prototype
- report text
- PRD text
- task text

## Prototype interaction options
- Copy report
- Copy PRD
- Copy tasks

## Suggested feedback states

### Idle state
Copy action is available

### Success feedback
Copied to clipboard

### Error feedback
Unable to copy. Please try again.

## UX notes
- Copy interactions should feel immediate
- Feedback should be visible but lightweight
- Export should not require a separate complex page in v1

---

# 3. Final workflow completion state

## Purpose
Show that the workflow is complete and the user has reached a reusable output set.

## Completion title
Workflow complete

## Completion subtitle
SignalForge has generated structured insights, a summary report, a PRD draft, and task outputs for this project.

## Completion summary
Your project now includes:
- structured insights
- report draft
- PRD draft
- task draft

## Completion actions

### Primary CTA
Return to project

### Secondary CTA
Create another project

### Optional CTA
Copy final outputs

## UX notes
- This state should feel satisfying but restrained
- It should signal progress, not celebration overload
- The user should know the workflow is reusable

---

# Navigation behavior across this screen

## From PRD Studio
Generate task draft → goes to Task Builder

## From Task Builder
Copy tasks → stays on current screen with success feedback

## From Task Builder
Complete workflow → goes to workflow completion state

## Back navigation
Task Builder can return to PRD Studio

---

# Prototype build notes

## Build order
1. Task Builder
2. Copy feedback behavior
3. Completion state

## Why
These pieces complete the narrative and show that SignalForge produces delivery-ready value, not just analysis.

## Prototype priority
A viewer should finish the walkthrough understanding that:
- the workflow reaches execution
- outputs are reusable
- SignalForge is positioned as a product operations workflow, not a single summarization tool
