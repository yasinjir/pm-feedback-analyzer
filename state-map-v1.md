# State Map v1 — SignalForge

## 1. Landing Page

### Default state
- product overview is visible
- user can understand the core value
- user can start the workflow

### CTA state
- primary CTA leads to project creation
- secondary CTA leads to current module or example

---

## 2. Create Project

### Empty state
- all fields are empty
- user is prompted to define project context

### Filled state
- required fields are completed
- user can continue to input workspace

### Error state
- required fields are missing
- user sees validation feedback

---

## 3. Input Workspace

### Empty state
- no feedback has been added yet
- user sees supported input methods

### Draft state
- user has entered or uploaded content
- user can still edit before analysis

### Ready state
- enough input exists to run insight generation

### Error state
- invalid or unreadable CSV
- unsupported structure
- empty submission

---

## 4. Insights View

### Loading state
- system is generating insight output

### Success state
- themes are shown
- pain points are shown
- feature requests are shown
- repeated signals are shown
- priority cues are shown
- summary insight is shown

### Weak-output state
- output exists but appears low-confidence or incomplete
- user may need to improve input

### Empty state
- no analysis has been generated yet

### Error state
- generation failed
- user can retry

---

## 5. Report View

### Empty state
- report has not been generated yet

### Loading state
- report generation in progress

### Success state
- executive summary visible
- key findings visible
- top problems visible
- suggested opportunities visible
- recommended focus visible

### Error state
- report generation failed

---

## 6. PRD Studio

### Empty state
- PRD has not been generated yet

### Loading state
- PRD generation in progress

### Success state
- PRD draft is visible
- sections are structured
- output is readable and reusable

### Editable state
- user can edit sections manually

### Error state
- PRD generation failed

---

## 7. Task Builder

### Empty state
- tasks have not been generated yet

### Loading state
- task generation in progress

### Success state
- work buckets are visible
- tasks are visible
- user stories are visible
- acceptance criteria are visible

### Error state
- task generation failed

---

## 8. Export / Copy

### Ready state
- user can copy structured output
- user can export outputs

### Success state
- copy/export action confirmed

### Error state
- export failed or output unavailable

## State design principle
At every stage, the user should know:
- where they are
- what has already been generated
- what they can do next
