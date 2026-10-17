# Recover from a failed agent session

A useful recovery starts with evidence and ends with a bounded next task.

## 1. Read the recorded outcome

Open the project's session context and change review. Look for the agent's summary, changed areas, reported checks, blockers, and decisions. Submitted file diffs can explain the change; a missing check is not a passing check.

## 2. Compare the change with the original decision

In the [public example](https://brainscanner.dev/#recover), moving token refresh into middleware breaks sign-out. The review puts the changed logout behavior beside two failing checks and the earlier decision to keep the cookie path on `/app`.

The question is specific: which change violated the intended behavior, and what should be restored? Ask your agent to verify the record against the current local files before editing.

## 3. Choose one next task

Queue a focused task with the affected area and a completion check. Edit the instructions if the approach changes, or cancel work you no longer want. Ask the connected agent to pick up the task using its existing access and permissions.

The homepage's **Accept and queue / Edit / Reject** controls illustrate this decision using sample data. They do not submit work to an agent. Current projects provide session records and queue controls; execution happens through your connected agent.

## 4. Leave a clear handoff

Record what changed, what was checked, and what remains. A returning or different agent should inspect that history and verify the current files before continuing.

[Try the example](https://brainscanner.dev/#recover) · [Review guide](https://brainscanner.dev/guides/review-agent-changes) · [Handoff guide](https://brainscanner.dev/guides/resume-a-coding-project)
