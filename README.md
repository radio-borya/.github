# Radio Borya GitHub Community Health Files

This is the public `.github` repository for the Radio Borya organization. GitHub can use recognized community health files from it as organization-wide defaults when a project does not provide its own version.

At present, this repository contains this README only; it does not publish organization-wide issue forms, contribution instructions, a code of conduct, security reporting instructions or an organization profile. Add one of those defaults only when the organization has adopted its content.

## Repository scope

Keep this repository focused on files GitHub recognizes as community health files, for example:

- `CONTRIBUTING.md` for contribution and review guidance;
- `CODE_OF_CONDUCT.md` for community expectations and reporting;
- `SECURITY.md` for vulnerability reporting instructions;
- issue and pull request templates under `.github/ISSUE_TEMPLATE/` and `.github/`;
- organization profile content under `profile/README.md`.

GitHub uses a default file only when the target repository does not contain its own corresponding file. Project-specific instructions should live in that project's repository.

## Contribution workflow

1. Check the target project's `README.md`, `AGENTS.md`, and contribution documentation before changing code or workflow files.
2. Keep each change focused and preserve unrelated local work.
3. Use lowercase kebab-case branches beginning with an allowed category: `feature/`, `fix/`, `hotfix/`, `refactor/`, `chore/`, `docs/`, `test/`, or `perf/`. Do not use a `codex/` prefix.
4. Use a single-line Conventional Commit title in English, for example `docs: clarify contribution workflow`. Keep it concise, imperative, and without a period. Do not add a body, footer, trailer, or attribution.
5. Run checks relevant to the files changed and report checks that could not be run.
6. Open focused pull requests with a Conventional Commit title. Leave the description body empty; do not merge without explicit authorization.

Do not commit secrets, credentials, generated local state, or unrelated changes. Follow repository-specific instructions when they add detail without conflicting with these conventions.

## Pull request and merge policy

- Keep pull requests focused on one logical change.
- Prefer draft pull requests while work is unfinished.
- Never merge without explicit authorization.
- When a merge is authorized, use a non-fast-forward merge commit. Do not squash, rebase, or rewrite shared history unless explicitly requested.

## Security reports

Use the target repository's `SECURITY.md` or GitHub's private vulnerability reporting feature when available. Do not publish vulnerability details, credentials, or exploit instructions in a public issue.

## Maintaining these defaults

Keep shared guidance broadly applicable across the organization. When a project needs different or more detailed instructions, add them in that project's repository rather than making this file project-specific. Review links and workflow examples when organization practices change.
