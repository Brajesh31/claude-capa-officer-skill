# claude-capa-officer-skill

A Claude Code skill for managing Corrective and Preventive Actions (CAPA) within quality management workflows.

## Overview

This skill supports the investigation and resolution of quality events. It helps structure problem statements, assess risk, identify root causes, plan corrective and preventive actions, assign ownership, and verify whether actions have worked.

A CAPA process should address the underlying cause of a problem, not simply document a quick fix.

## Core Capabilities

- CAPA initiation and triage.
- Problem statement development.
- Investigation planning and evidence collection.
- Root cause analysis.
- Risk and impact assessment.
- Corrective action planning.
- Preventive action planning.
- Ownership, due dates, and implementation tracking.
- Effectiveness verification.
- Closure review and continuous improvement.

## CAPA Lifecycle

1. **Initiation:** Record the event, source, scope, and initial impact.
2. **Evaluation:** Determine significance, urgency, and whether a formal CAPA is appropriate.
3. **Investigation:** Gather records, interview relevant personnel, and establish the facts.
4. **Root cause analysis:** Evaluate plausible causes using a structured method.
5. **Action planning:** Define actions that address verified causes.
6. **Implementation:** Assign owners, deadlines, evidence, and completion criteria.
7. **Effectiveness check:** Verify that the actions prevent recurrence over a suitable period.
8. **Closure:** Confirm documentation, evidence, residual risks, and approvals.

## Root Cause Analysis

The skill supports structured analysis methods such as:

- 5 Whys.
- Fishbone or cause-and-effect analysis.
- Process mapping.
- Fault-tree reasoning.
- Evidence-based hypothesis testing.

A method should be selected based on the complexity of the event. Do not treat the first plausible explanation as a confirmed root cause.

## Action Plan Requirements

A useful action should include:

| Field | Description |
|---|---|
| Action | Specific task to be completed |
| Cause addressed | Verified cause the action targets |
| Owner | Person or role responsible |
| Due date | Target completion date |
| Evidence | Records proving implementation |
| Success criteria | Observable completion condition |
| Effectiveness method | How recurrence or risk reduction will be checked |

## Installation

```bash
git clone https://github.com/Brajesh31/claude-capa-officer-skill.git ~/.claude/skills/capa-officer
```

## Usage

Invoke the skill for a CAPA investigation or action plan:

```text
/capa-officer
```

Provide the event description, process area, known evidence, risk context, applicable procedure, and required output format. Remove confidential or personally identifiable information unless it is necessary and authorized for the task.

## Quality and Governance Considerations

- Separate facts, assumptions, and hypotheses.
- Preserve traceability from the event to the root cause and actions.
- Use risk-based prioritization.
- Assign accountable owners.
- Define effectiveness criteria before closure.
- Maintain objective evidence.
- Follow the organization's approved quality procedures and applicable regulatory requirements.
- Do not claim compliance solely because a template has been completed.

## Suggested Deliverables

Depending on the investigation, the skill can help prepare:

- CAPA intake and triage summary.
- Investigation plan.
- Root cause analysis.
- Risk assessment.
- Corrective and preventive action plan.
- Effectiveness verification plan.
- Closure summary.

## Repository Contents

- `SKILL.md`: Main CAPA workflow and decision guidance.
- `README.md`: Lifecycle, action planning, and quality checklist.

## Important Note

This skill provides structured support for quality work. Final decisions, approvals, and regulatory interpretations remain subject to the organization's quality system and authorized personnel.
