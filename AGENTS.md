# mauriciopolvora

This repo is the GitHub profile README. GitHub shows `README.md` on the profile page.

## Checks

Turn on the gitleaks pre-commit hook once per clone:

```bash
git config core.hooksPath .githooks
```

CI (`.github/workflows/ci.yml`) runs gitleaks on the new commits of each PR and push to main.

`preview-teardown.yml` deletes the previews and the head branch of each closed PR, and `preview-sweep.yml` catches a close that started no run (rule in mauricio-taste `config/AGENTS.md`, "Previews and branches").
