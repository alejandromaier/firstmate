=== Rendered 'Project memory' section of a real ship brief (fm-brief.sh ws3-live-demo --mode no-mistakes) ===
# Project memory
If `AGENTS.md` or `CLAUDE.md` already exists, or if this task produced durable project-intrinsic knowledge, run `/Users/sistemas/.no-mistakes/worktrees/087e5452ff4f/01M34EWGDNRE25KQBG3EQSP2HD/bin/fm-ensure-agents-md.sh --no-promote .` in the worktree.
Record the knowledge in whichever memory file that command leaves in place, and never change which file this project uses as a side effect of this task; switching it is its own separate change.
Record only project knowledge useful to almost every future session.
For anything the codebase already shows, prefer a pointer to the authoritative file, command, or doc over copying the detail.
If you touch a project `AGENTS.md`, follow `/Users/sistemas/.no-mistakes/worktrees/087e5452ff4f/01M34EWGDNRE25KQBG3EQSP2HD/bin/fm-ensure-agents-md.sh`'s self-governance contract in the same pass; a `CLAUDE.md` the helper left in place owes no self-governance section.
Keep it proportionate: skip memory-file edits entirely for trivial tasks that produced no durable project knowledge.

# Definition of done
Delivery contract: mode=no-mistakes
The task is complete only when committed on your branch.
When you believe it is complete, append `done [at=<epoch>]: {summary}` to the status file and stop.
Firstmate will then instruct you to run /no-mistakes to validate and ship a PR.
