# Prototype Screen Pack v2 — SignalForge

## Purpose
Define the next three core workflow screens in a prototype-ready format:

1. Insights View
2. Report View
3. PRD Studio

These screens prove the core value of SignalForge:
raw feedback → structured insight → management summary → product requirements draft

---

# 1. Insights View

## Screen goal
Turn raw feedback into structured product insight that feels organized, readable, and decision-ready.

## Page title
Structured insights

## Page subtitle
SignalForge analyzed the input and organized it into actionable product signals.

## Primary CTA
Generate report

## Secondary CTA
Refine input

## Optional tertiary CTA
Re-run analysis

## Main sections
1. Page header
2. Summary insight block
3. Themes block
4. Pain points block
5. Feature requests block
6. Repeated signals block
7. Priority cues block
8. Action row

## Summary insight

### Block title
Summary insight

### Demo content
Users clearly value the match experience, but friction appears across discoverability, join flow, reminder timing, and search quality. The strongest product opportunities are simplifying the join flow, improving reminders, and making session information easier to access.

## Themes

### Block title
Themes

### Demo content
- Navigation and discoverability
- Match join flow
- Scheduling and rescheduling
- Notifications and reminder timing
- Search and filtering

## Pain points

### Block title
Pain points

### Demo content
- Users struggle to find past and upcoming sessions
- Joining a match feels too complex
- Reminder timing is unreliable or too late
- Match confirmation is not always clear
- Search filters are not specific enough

## Feature requests

### Block title
Feature requests

### Demo content
- Easier rescheduling
- Better player filters
- Central view for upcoming matches
- Clearer match confirmation state
- Improved reminder timing

## Repeated signals

### Block title
Repeated signals

### Demo content
- Join flow complexity
- Reminder timing issues
- Session discoverability
- Search filtering limitations

## Priority cues

### Block title
Priority cues

### Demo content
- High: simplify match join flow
- High: improve reminder timing and confirmation clarity
- Medium: improve session discoverability
- Medium: improve filtering for player search

## Empty state
No insights have been generated yet.

## Loading state
Generating structured insights...

## Weak-output state
The output may be incomplete. Add more specific input or improve the source quality.

## Error state
Insight generation failed. Please review the input and try again.

## UX notes
- This screen should feel analytical and trustworthy
- Labels should be explicit
- The structure should be highly scannable
- Summary should sit above details

---

# 2. Report View

## Screen goal
Present a concise, stakeholder-friendly summary of the insight output.

## Page title
Insight report

## Page subtitle
A concise summary of findings for product review and stakeholder communication.

## Primary CTA
Generate PRD draft

## Secondary CTA
Back to insights

## Optional tertiary CTA
Copy report

## Main sections
1. Page header
2. Executive summary
3. Key findings
4. Top problems
5. Suggested opportunities
6. Recommended focus
7. Action row

## Executive summary

### Block title
Executive summary

### Demo content
SignalForge identified consistent user friction in the end-to-end match experience. The most urgent issues relate to joining matches, receiving timely reminders, and understanding session status. Secondary opportunities include improving discoverability and search quality.

## Key findings

### Block title
Key findings

### Demo content
- The match join flow feels heavier than expected
- Notification timing creates reliability issues
- Users need stronger visibility into upcoming and past sessions
- Search and filtering need more precision

## Top problems

### Block title
Top problems

### Demo content
1. Joining a match requires too many steps
2. Reminder timing is inconsistent
3. Users cannot easily locate relevant session information
4. Match state and confirmation are not always obvious

## Suggested opportunities

### Block title
Suggested opportunities

### Demo content
- Reduce the number of steps in the join flow
- Improve reminder timing logic and visibility
- Add a clearer session hub for upcoming and past matches
- Improve search filters, especially around skill level

## Recommended focus

### Block title
Recommended focus

### Demo content
The team should prioritize workflow simplification and reminder reliability first, then improve discoverability and filtering in a second wave.

## Empty state
A report has not been generated yet.

## Loading state
Generating report...

## Error state
Report generation failed. Please try again.

## UX notes
- This screen should read like a professional summary
- Keep it mostly single-column
- Make it presentation-friendly
- Use strong hierarchy between summary and details

---

# 3. PRD Studio

## Screen goal
Turn validated insights into a structured PRD draft that feels usable and professional.

## Page title
PRD draft

## Page subtitle
SignalForge converted the validated insight into a standardized product requirements document.

## Primary CTA
Generate task draft

## Secondary CTA
Edit PRD

## Optional tertiary CTA
Copy PRD

## Main sections
1. Page header
2. Problem statement
3. Goals
4. Target users
5. Scope
6. Non-goals
7. Success metrics
8. Risks
9. Open questions
10. Action row

## Problem statement

### Block title
Problem statement

### Demo content
Users encounter friction across the match experience, especially when joining matches, understanding match state, finding sessions, and relying on reminders. These problems reduce confidence and increase effort in core product flows.

## Goals

### Block title
Goals

### Demo content
- Reduce friction in the match join flow
- Improve reliability and clarity of reminders
- Make upcoming and past sessions easier to access
- Improve search relevance and filtering

## Target users

### Block title
Target users

### Demo content
- Active players joining matches regularly
- Users rescheduling or tracking upcoming sessions
- Users searching for players or relevant matches

## Scope

### Block title
Scope

### Demo content
- Match join flow simplification
- Reminder timing improvements
- Session visibility improvements
- Better search filters

## Non-goals

### Block title
Non-goals

### Demo content
- Full redesign of the entire match ecosystem
- New social features
- Large-scale ranking system changes

## Success metrics

### Block title
Success metrics

### Demo content
- Reduction in join-flow drop-off
- Increase in successful match joins
- Improvement in reminder engagement
- Increase in session view usage
- Increase in filtered search usage

## Risks

### Block title
Risks

### Demo content
- Improvements may span multiple surfaces in the product
- Reminder improvements may depend on technical delivery constraints
- Search/filter improvements may require additional data quality work

## Open questions

### Block title
Open questions

### Demo content
- Should reminder improvements be product-only or include infrastructure changes?
- Should session visibility live in one hub or multiple surfaces?
- What is the minimum viable improvement for confirmation clarity?

## Empty state
A PRD draft has not been generated yet.

## Loading state
Generating PRD draft...

## Editable state
The user can revise sections manually before moving to tasks.

## Error state
PRD generation failed. Please try again.

## UX notes
- This should feel like a real working document
- Keep sections clearly separated
- Allow the content to feel editable
- Avoid generic AI-summary styling

---

# Navigation behavior across these screens

## From Input Workspace
Generate insights → goes to Insights View

## From Insights View
Generate report → goes to Report View

## From Report View
Generate PRD draft → goes to PRD Studio

## Back navigation
- Report View can return to Insights View
- PRD Studio can return to Report View

---

# Prototype build notes

## Build order for this pack
1. Insights View
2. Report View
3. PRD Studio

## Why
These screens prove the product transformation from input into structured product decision-making artifacts.

## Prototype priority
The viewer should clearly understand:
- how raw input becomes insight
- how insight becomes a summary
- how summary becomes a PRD draft
