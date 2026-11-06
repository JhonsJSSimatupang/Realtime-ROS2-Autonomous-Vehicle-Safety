# 🤝 Contributing Guidelines

Thank you for your interest in contributing to this project!

This document describes the workflow and guidelines for contributing to the Real-Time Collision Avoidance for Autonomous Driving project.

## 1. Development Workflow

We use Git and GitHub to manage collaboration and track project changes.

The general workflow is:

1. Clone the repository.
2. Create a new branch for your task.
3. Implement your changes.
4. Test your implementation.
5. Commit and push your changes.
6. Open a Pull Request for review.

## 2. Branch Naming Convention

Use descriptive branch names based on the development task.

| Prefix | Purpose | Example |
|---|---|---|
| `feature/` | New functionality | `feature/obstacle-detection` |
| `fix/` | Bug fixes | `fix/sensor-data-error` |
| `docs/` | Documentation | `docs/system-architecture` |
| `test/` | Testing development | `test/latency-evaluation` |
| `refactor/` | Code improvement | `refactor/ros2-node` |

## 3. Commit Message Convention

Write clear and meaningful commit messages.

Examples:

```bash
git commit -m "feat: implement obstacle detection"
git commit -m "fix: resolve ROS 2 communication issue"
git commit -m "docs: update system architecture"
git commit -m "test: add latency evaluation"
```

Recommended prefixes:

- `feat:` New functionality.
- `fix:` Bug fixes.
- `docs:` Documentation changes.
- `test:` Testing-related changes.
- `refactor:` Code restructuring.
- `chore:` Maintenance tasks.

## 4. Pull Request Guidelines

Before submitting a Pull Request:

- Ensure the code follows the project structure.
- Test the changes when applicable.
- Update relevant documentation.
- Explain the purpose of the changes.
- Include screenshots or experimental results when useful.

## 5. Code and Documentation Guidelines

- Use descriptive file and variable names.
- Keep functions and modules focused.
- Avoid committing temporary files and unnecessary generated data.
- Document important algorithms and system configurations.
- Do not report unverified experimental results.
- Clearly identify incomplete or experimental features.

## 6. Collaboration Principles

- Communicate before modifying shared components.
- Avoid pushing directly to the `main` branch.
- Review changes before merging.
- Keep commits small and understandable.
- Record important technical decisions.

Thank you for helping improve this project!