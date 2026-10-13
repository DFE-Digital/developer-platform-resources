# Contributing

Contributions should help DfE developer teams reuse safe, understandable
templates, infrastructure snippets, code samples or guidance.

## Branching and pull requests

1. Create a branch named `US/<ticket-number>` for the Azure DevOps story or
   task. Branch from the current `dev` branch.
2. Open a pull request from `US/<ticket-number>` into `dev` and link the
   Azure DevOps work item.
3. After changes have been reviewed and merged into `dev`, promote them from
   `dev` to `main` through a separate reviewed pull request.
4. Do not push directly to `dev` or `main`.

At least one approval is required before a pull request can be merged. New
commits dismiss previous approvals, so the updated pull request must be
approved again. Resolve every review conversation before merging.

These are the repository's required contribution practices. GitHub rulesets
must be configured separately to enforce them; see
[the repository setup guidance](./guidance/repository-setup.md).

## Public content and safety

- Use placeholders for account names, identifiers, URLs, credentials and
  environment-specific values in every public example.
- Do not include secrets, personal information or internal operational
  configuration.
- Do not copy code or configuration from internal repositories.
- Keep examples focused and explain assumptions and limitations.
- State what users need to adapt and how they should validate an example
  before using it.
- Check that the content is suitable for public publication and that any
  licence or attribution requirements are understood.

## Pull request checklist

Use the [pull request template](./.github/PULL_REQUEST_TEMPLATE.md). Describe
the purpose and changes, link the Azure DevOps ticket, report validation
performed, note documentation updates, and confirm that the content is
suitable for public publication.
