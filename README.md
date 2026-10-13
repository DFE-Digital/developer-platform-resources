# Developer Platform resources

This repository is intended to provide reusable templates,
infrastructure-as-code snippets, code samples, guidance and standards for
Department for Education (DfE) developer teams. It supports consistent
repository setup and development practices across the Developer Platform.
It is separate from the internal Developer Platform application repository.

## Who this is for

DfE developers and delivery teams looking for reusable starting points,
examples or shared technical guidance.

## What belongs here

- Reusable repository and project templates.
- Small, general-purpose infrastructure-as-code snippets.
- Code samples that demonstrate a pattern without depending on internal
  services or configuration.
- Practical guidance and standards for DfE developer teams.

Do not copy code or configuration from internal repositories. Public examples
must use placeholders and contain no secrets, personal information or internal
operational configuration.

## Repository structure

| Folder                                          | Contents                                              |
| ----------------------------------------------- | ----------------------------------------------------- |
| [`templates/`](./templates/README.md)           | Reusable repository and project templates             |
| [`infrastructure/`](./infrastructure/README.md) | Adaptable infrastructure-as-code snippets             |
| [`examples/`](./examples/README.md)             | Focused, illustrative code samples                    |
| [`guidance/`](./guidance/README.md)             | Shared guidance, standards and repository setup notes |

## Use examples safely

Content here is illustrative, not production-ready by default. Adapt every
example to its intended environment, check it against current DfE and service
requirements, and validate it before use. Review security, privacy, licensing
and operational implications as part of that validation.

## Contributing

Read [CONTRIBUTING.md](./CONTRIBUTING.md) before opening a pull request. Work
follows `US/<ticket-number>` → `dev` → `main` through reviewed pull requests.
The [pull request template](./.github/PULL_REQUEST_TEMPLATE.md) lists the
information and checks contributors must provide.

GitHub repository settings that still need to be verified or configured are
listed in [guidance/repository-setup.md](./guidance/repository-setup.md).
