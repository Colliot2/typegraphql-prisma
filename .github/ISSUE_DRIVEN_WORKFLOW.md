# Issue-Driven Development Workflow

## Rules
1. All work starts from an Issue.
2. One PR should map to one primary Issue.
3. PR title should reference Issue number (`#123`).
4. Do not start implementation without acceptance criteria.

## Status labels
- `status/triage`
- `status/ready`
- `status/in-progress`
- `status/blocked`
- `status/done`

## Priority labels
- `priority/p0` to `priority/p3`

## Recommended execution loop
1. Create issue with template.
2. Triage + label priority.
3. Break into sub-tasks/checklist.
4. Implement in branch + tests.
5. PR with checklist evidence.
6. Merge and close issue.
