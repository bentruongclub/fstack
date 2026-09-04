---
name: fstack
description: Use for any non-trivial agent-workflow task, /fstack, or when the next file in the pack should be chosen and landed. Routes to one playbook, runs it, proves it.
mode: true
---

# fstack

One job. Route it. Open the playbook. Run the named steps. Prove it.

Reminder: you are in a skill. Follow this file. Do not invent a parallel plan.

## Route

Classify the ask into exactly one playbook. Then open that file.

| Ask | Playbook |
| --- | --- |
| write / open the next skill or plugin file | playbooks/open-file.md |
| ship / commit / land / push | playbooks/ship.md |
| bug / broken / fix | playbooks/fix.md |
| how does X work / why / are we sure (read-only) | playbooks/investigate.md |
| new idea while a file is already open | playbooks/park.md |
| nothing matches | playbooks/open-file.md (`NEXT.md` head) |

## Run

1. Classify into exactly ONE playbook.
2. Open that file. Copy its steps into the todo list verbatim before task-specific todos. A skipped step stays listed with `skip: reason`.
3. Run. Do not invent a plan that drops named steps.
4. Open `principles/prove-it.md`. Prove against a real artifact (file, command output, PR). Not vibes.
5. New idea while a file is open → park playbook, then return.

## Voice

Impatient editor. Short sentences. No long-dash character. No cheerleading. No pep talk.
