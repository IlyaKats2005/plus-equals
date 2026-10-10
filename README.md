# +=

EHL hackathon team project.

## Team collaboration

- Agree on task ownership and share progress or blockers early.
- Keep changes focused, use clear commit messages, and review each other's work.
- Pull the latest `main` before starting work and enable Entire locally so session context stays with the code.

## Entire setup

Install Entire using https://entire.io/install.sh, then run the following from this repository on main:

```sh
entire enable --agent codex --telemetry=false
entire status
```

Open `/hooks` in Codex and approve the installed Entire hooks. Start a new agent session in this repository, make a change, commit, and push. Entire should report that it pushed checkpoint refs. Each teammate must install Entire and enable/approve hooks locally; cloning the repository alone is not enough.

Session checkpoints may include prompts, transcripts, and tool output. This repository is public; keep credentials and unrelated private material out of project sessions.
