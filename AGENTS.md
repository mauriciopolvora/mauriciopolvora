# mauriciopolvora

This repo is the GitHub profile README. GitHub shows `README.md` on the profile page.

## Checks

Turn on the gitleaks pre-commit hook once per clone:

```bash
git config core.hooksPath .githooks
```

CI (`.github/workflows/ci.yml`) runs gitleaks on the new commits of each PR and push to main.
