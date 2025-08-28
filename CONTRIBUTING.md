# Contributing

## Branching
- Trunk-based: feature branches → PR → squash merge into `main`.
- Protect `main` (required reviews, passing CI).

## Commit style
- Conventional Commits (e.g., `feat:`, `fix:`, `chore:`).

## Pull Requests
- Small, focused; include tests where applicable.
- Fill out PR template.

## Code style
- Node 20.x
- pnpm (enable with `corepack enable`)
- Prettier + EditorConfig

## Running locally
- `nvm use` (or install Node 20)
- `corepack enable` then `pnpm -v`
