# Built-in features for social-canvas-os

Purpose: social media content planning

1. **prepare a creative project** — run social-canvas-os-workspace. It creates ~/Documents/social-canvas-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run social-canvas-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/social-canvas-os-session-plans/.
3. **check project and export readiness** — run social-canvas-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/social-canvas-os-workspace features/social-canvas-os-plan features/social-canvas-os-check "$HOME/.local/bin/"
