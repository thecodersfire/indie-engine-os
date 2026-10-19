# Built-in features for indie-engine-os

Purpose: game development

1. **prepare racing and game notes** — run indie-engine-os-workspace. It creates ~/Documents/indie-engine-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run indie-engine-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/indie-engine-os-session-plans/.
3. **check game and controller readiness** — run indie-engine-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/indie-engine-os-workspace features/indie-engine-os-plan features/indie-engine-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for game development:

1. **Godot Engine** — org.godotengine.Godot
2. **GIMP** — org.gimp.GIMP
3. **Inkscape** — org.inkscape.Inkscape

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
