# Project Guidance

## Stack

- Node.js 22 LTS
- TypeScript with strict checking
- npm for dependency management

## Conventions

- Use TypeScript for application code.
- Keep modules small and focused on one responsibility.
- Prefer explicit names over abbreviations.
- Add or update focused tests with behavior changes.
- Use Conventional Commits: `type(scope): description`.
- Do not commit secrets, local environment files, or generated output.

## Workflow

1. Read the relevant code and tests before editing.
2. Make the smallest change that solves the task.
3. Run the narrowest relevant test or typecheck.
4. Summarize the change and verification in the pull request.
