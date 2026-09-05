---
bump: minor
---
Add the changeset release flow: every PR adds `.changeset/<slug>.md`, and CI on main is the only writer of the plugin version and `CHANGELOG.md` (`scripts/release.py`, `scripts/changeset-check.py`, `scripts/selftest-release.py`).
