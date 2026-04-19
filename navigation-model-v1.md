# Navigation Model v1 — SignalForge

## Navigation principle
Navigation in SignalForge v1 should support progression, clarity, and continuity.

The user should always know:
- where they are
- what has been completed
- what the next step is

## Recommended navigation model

### Level 1: Global navigation
Used for:
- moving between Projects Home and a selected project

### Global nav items
- Projects
- Current Project

## Level 2: In-project workflow navigation
Used inside a single project workspace

### In-project steps
1. Project
2. Inputs
3. Insights
4. Report
5. PRD
6. Tasks

## Navigation behavior

### Current step
- clearly highlighted
- visually distinct
- shown in header or workflow bar

### Completed steps
- accessible
- marked as completed or available

### Future steps
- visible
- disabled until prerequisites are complete if needed

## Preferred navigation UI
Horizontal workflow step bar

Example:
Project → Inputs → Insights → Report → PRD → Tasks

## Why this model works
- matches the product promise
- supports linear progression
- reduces cognitive load
- feels enterprise-ready
- keeps the workflow transparent

## Projects Home navigation

### Main actions
- Create project
- Open existing project
- Resume last active project

### Project card data
Each project card may show:
- project name
- initiative name
- current workflow stage
- last updated time

## In-project page structure

### Top bar
- SignalForge logo
- current project name
- optional status indicator

### Workflow nav
- visible on every project screen
- shows current stage
- allows back navigation to completed steps

### Main page content
- screen-specific working area

### Action row
- primary next-step action
- secondary back/refine action

## Navigation rules

### Rule 1
The primary CTA should move the workflow forward.

### Rule 2
The secondary CTA should support editing, refining, or going back.

### Rule 3
Users should never lose access to already generated outputs.

### Rule 4
Users should not be taken to unrelated areas during the workflow.

## Dashboard decision
A full dashboard is not required for v1.

Instead, use:
- Projects Home as a lightweight entry screen
- Project Workspace as the main app environment

## Future navigation expansion
Later versions may add:
- templates
- team collaboration
- integrations
- reporting center
- settings

But these should not shape v1 navigation.

## Navigation design principle
SignalForge should feel like a guided product workflow system, not a generic SaaS dashboard.
