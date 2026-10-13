# GitHub repository setup

This checklist records GitHub-side settings for the Developer Platform
resources repository, which is intended to be public. Documentation and local
files do not configure these settings. Verify each item in GitHub; do not
assume it is enabled.

- [ ] Set repository visibility to **Public**.
- [ ] Grant the appropriate team access and verify GitHub access for the
      maintainers listed in [CODEOWNERS](../.github/CODEOWNERS). Assign at least
      two responsible maintainers.
- [ ] Create active rulesets for both `main` and `dev` that require pull
      requests, at least one approval, code-owner review, dismissal of stale
      approvals after new commits, all review conversations resolved, and
      successful required CI checks.
- [ ] In both rulesets, block force pushes and branch deletion.
- [ ] Verify secret scanning and push protection are available and enabled
      for this public repository.
- [ ] Configure code scanning when supported code is added, using a suitable
      analysis tool for the languages present.
- [ ] Confirm the DfE-approved licence before adding a licence file. No licence
      has been selected in this repository.

The CODEOWNERS entries identify intended maintainers only; they do not grant
repository access. Access and each setting above must be checked independently.
