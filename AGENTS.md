# Agent Guidelines

Instructions and operational constraints for AI coding agents working in this repository.

## Workflow Rules

1. **Task Tracking**:
   - Check [`TASKS.md`](TASKS.md) before starting work.
   - Update task status to `In Progress` when starting and `Completed` upon verification.
   - Add newly discovered tasks or subtasks to [`TASKS.md`](TASKS.md).

2. **Code Style & Quality**:
   - Write clean, idiomatic, self-documenting code.
   - Follow the existing formatting and file conventions within the project.
   - Preserve existing comments and docstrings unless explicitly asked to modify them.

3. **Verification**:
   - Always run tests and verify changes before committing.
   - Do not commit broken builds or untested edge cases.

4. **Git Commit Conventions**:
   - Write clear, imperative commit messages (e.g., `feat: ...`, `fix: ...`, `docs: ...`).
   - Sign commits with the configured SSH key.
   - Avoid committing temporary files, secrets, or build artifacts.
