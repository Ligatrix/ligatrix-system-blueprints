# AI Retrofit Blueprint

An AI retrofit adds useful AI behavior to an existing operation without replacing
the business system underneath it.

## Useful When

- The company already has tools but no reliable way to use AI inside them.
- Work requires triage, summarization, classification, drafting, or routing.
- Leaders need proof of what worked, not vague automation claims.
- Teams need guardrails before AI reaches customers or production workflows.

## Retrofit Layers

1. Intake - capture the task, user, input, and goal.
2. Context - retrieve approved business context.
3. Execution - call models, tools, or workflows under constraints.
4. Verification - score, review, or gate the output.
5. Escalation - route uncertain work to a person.
6. Records - log inputs, outputs, checks, and approvals.

## Release Gate

An AI workflow should not ship until it has:

- a defined owner;
- known failure modes;
- test cases;
- human override;
- logs;
- cost visibility;
- rollback path.
