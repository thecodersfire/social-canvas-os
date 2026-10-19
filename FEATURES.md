# Built-in features for social-canvas-os

Purpose: social media content planning

1. **prepare a creative project** — run social-canvas-os-workspace. It creates ~/Documents/social-canvas-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run social-canvas-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/social-canvas-os-session-plans/.
3. **check project and export readiness** — run social-canvas-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/social-canvas-os-workspace features/social-canvas-os-plan features/social-canvas-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for social media content planning:

1. **Inkscape** — org.inkscape.Inkscape
2. **Krita** — org.kde.krita
3. **Kdenlive** — org.kde.kdenlive

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for social media content planning:

1. **Blender** — create 3D assets and animations (org.blender.Blender)
2. **Audacity** — edit audio recordings (org.audacityteam.Audacity)
3. **Ardour** — record and mix multitrack audio (org.ardour.Ardour)
4. **darktable** — develop RAW photos (org.darktable.Darktable)
5. **Scribus** — lay out print-ready publications (org.scribus.Scribus)
6. **VLC** — review media files (org.videolan.VLC)
7. **Mixxx** — prepare and mix DJ sets (org.mixxx.Mixxx)
8. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
9. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
