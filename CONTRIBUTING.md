# Contributing to WP24Horas Open Source

Thanks for contributing to a WP24Horas open-source project.

Repository-specific contribution guides take precedence over this organization default.

## Before opening a change

- Check existing issues and pull requests to avoid duplicate work.
- Keep changes focused and independently reviewable.
- Do not include client code, private product code, credentials, production data or secrets.
- Preserve backward compatibility unless the issue explicitly requires a breaking change.
- Add or update tests when behavior changes.
- Update documentation when public behavior, configuration or extension points change.

## Local validation

Use the validation commands documented by the repository. When a project provides local checks, run them before opening a pull request.

WP24Horas repositories may intentionally keep GitHub Actions manual-only. Do not re-enable automatic workflows only to obtain a green badge.

## Pull requests

A useful pull request explains:

- the problem being solved;
- the chosen approach and important trade-offs;
- how the change was validated;
- any compatibility or security impact.

Keep unrelated refactors out of functional changes whenever possible.

## Security

Do not publish exploitable vulnerability details in a public issue. Follow the repository's `SECURITY.md` when present, or the organization default security policy otherwise.
