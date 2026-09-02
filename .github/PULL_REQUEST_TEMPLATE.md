## What & why
<!-- What changes, and why. The diff shows *what*; say *why*. -->


## Checklist
- [ ] Short-lived, subject-named branch (`feat/…` · `fix/…` · `docs/…`)
- [ ] `docker compose config` succeeds (if compose changed)
- [ ] Healthcheck passes locally (if the service changed)
- [ ] No plaintext secret in the diff — `git diff | grep -iE 'password|secret|key|token'`

<!-- How we ship: branch → PR → review → merge → deploy.
     https://github.com/anam-145/anam145-infra/blob/main/docs/PR_WORKFLOW.md -->
