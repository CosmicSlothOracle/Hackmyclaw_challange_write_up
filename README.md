# HackMyClaw challenge write-up

Educational postmortem of email-only attempts against FIU (HackMyClaw / OpenClaw). **No successful compromise** — all runs observed: sent, no reply.

## Live site

After GitHub Pages is enabled on `main` (root), the playbook is at:

**https://cosmicslothoracle.github.io/Hackmyclaw_challange_write_up/**

## Repo contents (Pages only)

| File | Purpose |
|------|---------|
| `index.html` | Standalone playbook (Cosmic Tactical UI, embedded ASCII) |
| `.nojekyll` | Skip Jekyll processing |
| `README.md` | This file |

Payload scripts and build tooling live in the local `scripts` workspace, not in this repo.

## Enable Pages (one-time)

1. Repo **Settings** → **Pages**
2. **Build and deployment** → Source: **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)** → Save
