# AGENTS.md: chorebot-web

Read [`chorebot-docs/PLAN.md`](https://github.com/LOR-Robotics/chorebot-docs/blob/main/PLAN.md) first. It is the only steering file.

## Rules

1. Write code, tests and sim work before documents. A new doc needs a human to ask for it.
2. Add no new research, compliance or evidence files before Gate 1 (1 Nov 2026) unless a human asks.
   The barn risk assessment and insurance checklist already exist; use them in Phase 2.
3. `PLAN.md` is the one steering file. Update it by PR instead of writing status docs.
4. Evidence goes in the PR description as a log excerpt and a clip link, not in a new folder of files.
5. Commit under a bot identity with a `Co-Authored-By:` trailer that names the agent. Never commit as a human.
   A human approves every merge.
6. Safety contract: the LLM, phone and cloud never publish `/cmd_vel`. Motion goes
   skill JSON → executor → Nav2 → twist_mux. E-stop and geofence win over any skill.
7. Public copy (chorebot-web, chorebot-handbook) carries no internal gate codes and no product name
   until the rename. Never use "droid" (a Lucasfilm trademark).

## This repo

The public brochure site (Cloudflare Pages, deployed from `main`, no build step). Keep the copy plain,
describe work in development honestly, and ship no unreleased video. The product has no public name yet.
