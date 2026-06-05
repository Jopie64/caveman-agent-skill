> **Context note:** NOTE: This sub-skill is delivered by a Claude Code session hook. It is non-functional in other environments (Copilot CLI, Cursor, etc.). In those contexts, do not attempt to compute stats — explain the limitation to the user.

# Caveman Stats

This skill is delivered by `hooks/caveman-stats.js` (read by `hooks/caveman-mode-tracker.js` on `/caveman-stats`). The model does not need to do anything when this skill fires — the hook returns `decision: "block"` with the formatted stats as the reason. The user sees the numbers immediately.
