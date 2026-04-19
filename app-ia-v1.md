# App IA v1 — SignalForge

## IA principle
SignalForge v1 should be organized as a project-based workflow system.

The structure should help the user move from feedback input to execution-ready output without unnecessary branching or navigation complexity.

## Primary product model
Project-centered workflow

Each project contains a linear progression:
1. Project setup
2. Inputs
3. Insights
4. Report
5. PRD
6. Tasks

## Top-level app structure

### 1. Projects Home
Purpose:
- show existing projects
- allow project creation
- let the user continue existing work

### 2. Project Workspace
Purpose:
- contain the full end-to-end workflow for one project

## Project Workspace structure

### A. Project
Define project context

### B. Inputs
Add feedback and source material

### C. Insights
Review structured insight output

### D. Report
Review stakeholder-friendly summary

### E. PRD
Review and edit PRD draft

### F. Tasks
Review and copy execution-ready work

## Recommended top-level navigation

### Global level
- Projects
- Current Project

### Inside a project
- Project
- Inputs
- Insights
- Report
- PRD
- Tasks

## Not recommended for v1
- analytics dashboard
- complex admin area
- multi-level menu trees
- settings-heavy navigation
- deep sidebars with many branches

## Rationale
The product promise is linear:
feedback → insight → PRD → execution

The information architecture should reflect that promise directly.

## Entry points

### Primary entry point
Projects Home

### Secondary entry point
Direct project continuation

For example:
A returning user should be able to re-enter an existing project and continue from the last completed step.

## Object model

### Main object
Project

A project contains:
- project context
- raw inputs
- generated insights
- report output
- PRD output
- task output

## IA design principle
The user should always feel they are inside one coherent project workflow, not jumping between unrelated tools.
