# Prototype Screen Pack v1 — SignalForge

## Purpose
Define the first three in-product screens in a concrete, prototype-ready format.

These screens are:
1. Projects Home
2. Create Project
3. Input Workspace

The goal is to make the first product prototype easier to build with realistic content, actions, and states.

---

# 1. Projects Home

## Screen goal
Give the user a lightweight operational entry point into SignalForge.

The screen should help the user:
- create a new project
- open an existing project
- resume work from the last stage

## Page title
Projects

## Page subtitle
Manage active product workflows from feedback to PRD and execution-ready tasks.

## Primary CTA
Create project

## Secondary CTA
Resume latest project

## Top-level actions
- Create project
- Open project
- Resume project

## Main sections
1. Page header
2. Primary action row
3. Project list
4. Optional empty state

## Suggested layout
Top to bottom:
- title and subtitle
- primary CTA row
- project cards grid or list
- optional empty state if no project exists

## Demo data for project cards

### Project card 1
Project name: Match Experience Improvement  
Initiative: Improve match discovery, join flow, and reminder experience  
Current stage: Insights  
Last updated: Today  
Status cue: In progress

### Project card 2
Project name: Player Search Quality Review  
Initiative: Improve search relevance and filtering experience  
Current stage: Report  
Last updated: Yesterday  
Status cue: Review ready

### Project card 3
Project name: Session Visibility Update  
Initiative: Make upcoming and past sessions easier to access  
Current stage: PRD  
Last updated: 2 days ago  
Status cue: Draft in progress

## Project card fields
- project name
- initiative name
- current workflow stage
- last updated
- status cue

## Project card actions
Primary action: Open project  
Secondary action: Continue workflow

## Empty state copy
### Empty state title
No projects yet

### Empty state subtitle
Create your first SignalForge project to move from raw feedback to structured insight, PRD drafts, and task outputs.

### Empty state CTA
Create first project

## UX notes
- Keep this screen light
- Avoid heavy dashboard patterns
- It should feel operational, not analytical
- The user should know what to do immediately

---

# 2. Create Project

## Screen goal
Collect enough context to begin a meaningful workflow.

## Page title
Create a new project

## Page subtitle
Define the context for your analysis before turning feedback into insights, PRDs, and tasks.

## Primary CTA
Create project

## Secondary CTA
Cancel

## Main sections
1. Page header
2. Project setup form
3. Optional context guidance
4. Action row

## Form fields

### Field 1
Label: Project name  
Type: text input  
Required: yes  
Placeholder: Match Experience Improvement

### Field 2
Label: Feature or initiative  
Type: text input  
Required: no  
Placeholder: Improve match discovery, join flow, and reminder experience

### Field 3
Label: Background context  
Type: textarea  
Required: no  
Placeholder: Recent user feedback suggests friction across the match experience. Users report confusion when finding past sessions, too many steps to join matches, and weak reminder timing.

### Field 4
Label: Analysis goal  
Type: textarea  
Required: yes  
Placeholder: Turn recent user feedback into structured product insight, a draft PRD, and a task breakdown for product planning.

## Demo content for filled state

### Project name
Match Experience Improvement

### Feature or initiative
Improve match discovery, join flow, and reminder experience

### Background context
Recent user feedback suggests friction across the match experience. Users report confusion when finding past sessions, too many steps to join matches, and weak reminder timing.

### Analysis goal
Turn recent user feedback into structured product insight, a draft PRD, and a task breakdown for product planning.

## Validation rules
- project name is required
- analysis goal is required

## Validation messages

### Missing project name
Project name is required.

### Missing analysis goal
Analysis goal is required.

## Empty state guidance
Add enough context so SignalForge can generate more relevant outputs.

## UX notes
- This screen should feel fast and simple
- Use a single-column form
- Do not over-design it like admin software
- Make the primary CTA obvious

---

# 3. Input Workspace

## Screen goal
Allow the user to provide the raw product inputs that SignalForge will analyze.

## Page title
Add product inputs

## Page subtitle
Paste feedback, notes, table-like content, or upload a CSV file to begin analysis.

## Primary CTA
Generate insights

## Secondary CTA
Clear input

## Main sections
1. Page header
2. Input guidance block
3. Main raw input area
4. Optional structured input area
5. CSV upload area
6. Action row

## Input guidance block

### Guidance title
Supported input types

### Guidance content
SignalForge v1 accepts:
- raw user feedback
- interview notes
- support patterns
- survey responses
- structured text blocks
- CSV input

### Guidance note
The prototype does not require perfect formatting. The goal is to help the user understand what kinds of data can enter the workflow.

## Main raw input area

### Section title
Raw feedback

### Section subtitle
Paste user comments, support excerpts, survey responses, or product notes.

### Demo input
- The app is useful but finding past sessions is confusing.
- I want an easier way to reschedule matches.
- Notifications are helpful, but there are too many of them.
- It takes too many steps to join a match.
- I would love better filters for searching players.
- Match reminders sometimes come too late.
- I’m not always sure whether a match is confirmed or not.
- It would help if I could quickly see my upcoming matches in one place.
- Search results are okay, but filtering by skill level would help a lot.
- Sometimes the notification arrives after I have already missed the session.

## Optional structured input area

### Section title
Structured notes

### Demo content
Source mix:
- in-app feedback
- support messages
- survey responses

Feedback period:
Last 30 days

## CSV upload area

### Section title
CSV upload

### Helper text
Upload a CSV file if your feedback is already stored in a spreadsheet-like format.

### Prototype note
In the first prototype, CSV upload can be shown as a simulated upload area rather than a fully working parser.

## Input helper messages

### Empty state
No feedback has been added yet.

### Draft state
Input added. Review or edit your content before generating insights.

### Ready state
Your input is ready for analysis.

### Error state
The uploaded file could not be read. Please check the format and try again.

## Action row

### Primary action
Generate insights

### Secondary action
Clear input

### Optional tertiary action
Use demo content

## UX notes
- The input area should be large and central
- The screen should reduce uncertainty about acceptable input
- The primary CTA should feel like the natural next step
- This should feel like a working product surface, not just a form

---

# Navigation behavior across these screens

## From Projects Home
Create project → goes to Create Project

## From Create Project
Create project → goes to Input Workspace

## From Input Workspace
Generate insights → goes to Insights View

## Back navigation
- Create Project can return to Projects Home
- Input Workspace can return to Create Project if needed

---

# Prototype build notes

## Build these first
1. Projects Home
2. Create Project
3. Input Workspace

## Why
These three screens establish:
- project-based workflow
- context setup
- input-to-analysis flow

They make the product feel real before downstream outputs are built.

## Prototype priority
The first clickable prototype should allow a viewer to:
- land on Projects Home
- create or open a project
- review project context
- add input
- move toward insight generation
