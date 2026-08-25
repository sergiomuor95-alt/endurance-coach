# endurance-coach

Shared source of truth for Sergio's London Marathon 2027 training.

- [`plan.md`](plan.md) — the 20-week training plan (phases, weekly volume, long runs, pacing/fueling notes).
- [`running-log.md`](running-log.md) — automated log of post-run feedback, one entry per analyzed activity.

This repo is read by a Claude Code Routine connected to Strava. After each new activity, the Routine compares it against `plan.md`, appends a short feedback note to `running-log.md`, and commits the change. No manual upkeep needed beyond updating `plan.md` when the plan changes.
