# Contributing

Thank you for your interest in contributing.

## Before you start
- Check existing issues and discussions.
- Open an issue before large architectural changes.
- Keep changes focused and explain the user problem they solve.

## Engineering expectations
- Prefer documented Windows APIs.
- Keep hardware-specific functionality behind capability interfaces.
- Do not make system changes without validation, user control, and a restoration path.
- Do not terminate user or system processes as a generic optimization strategy.
- Add unit tests for decision logic and tests for state restoration.
- Document the Windows version and hardware used for integration testing.
- Update the README and compatibility matrix when behavior changes.

## Pull requests
Include:
1. A concise description of the change.
2. The problem it addresses.
3. Tests performed and their results.
4. Windows version and hardware details for system-level changes.
5. Known limitations or unsupported devices.

Do not submit secrets, personal data, or unredacted diagnostic logs.
