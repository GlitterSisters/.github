# Contributing to GlitterSisters projects

Thanks for sparkling with us! This guide applies to every repository in the organization unless a repo has its own `CONTRIBUTING.md`.

## Workflow

1. **Open or pick an issue** before starting work, so we both know what's in progress.
2. **Branch from `main`**, using a short descriptive name: `feature/cycle-length-plot`, `fix/date-parsing`.
3. **Commit small and often**, with clear messages in the imperative: `Add cycle length histogram`.
4. **Open a pull request** and ask the other person to review it. Link the issue with `Closes #12`.
5. **Merge after approval** (squash merge keeps history tidy).

## Code style

- Python 3.10+
- Format with `black`, lint with `ruff`
- Type hints and docstrings on public functions
- Tests with `pytest` for anything with logic

## Personal data policy

**Real personal or health data never goes into Git**, not even in private repos.

- Keep real data in a local, gitignored `data/` folder
- Commit only synthetic or fully anonymized sample data
- If you accidentally commit data, tell the other person right away so we can clean the history properly

## Be kind

We follow the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/). Be respectful, assume good intent, and celebrate each other's work.
