# Habit Manager (releases)

Habit tracking for Obsidian, driven by daily-note checklists. You define habits in settings, the plugin generates them into daily notes as a checklist, and a `habits` code block draws an interactive table that syncs both ways with the notes.

This repo holds the release builds. The source is developed in a separate private repo, so issues here may not get a reply.

## Install with BRAT

1. In Obsidian, install and enable **BRAT** from Community plugins.
2. In BRAT's settings, choose **Add beta plugin**.
3. Enter `masonroyal/habit-manager-releases` and pick the latest version.
4. Enable **Habit Manager** under Community plugins.

No GitHub token is needed. BRAT can keep the plugin up to date from here.

## First run

Open the plugin's settings to add your habits and set your daily-notes folder. The format defaults are in Chinese (`## 習慣清單`, `記錄:`, `#習慣/`), and you can change all of them there. With auto-insert on, which is the default, a daily note whose checklist heading is empty gets the checklist filled in.

## Install by hand

Download `main.js`, `manifest.json` and `styles.css` from the latest release into `<your vault>/.obsidian/plugins/habit-manager/`, then enable the plugin.

This is beta software. Back up your vault before trying it.
