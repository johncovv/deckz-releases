# Deckz

A window manager for macOS: workspaces reached with a keystroke, grids that
size themselves to what is open, and a cascade that always leaves an edge to
click.

**[Download the latest version](https://github.com/johncovv/deckz-releases/releases/latest)**
· [deckz.io](https://deckz.io)

## What this repository is

Builds, and somewhere to report problems. The source is private and lives
elsewhere; nothing here is compiled from what you can see.

## Installing

Open the disk image and drag Deckz to Applications.

These are early builds and they are **not notarised by Apple yet**, so macOS
refuses them the first time and says it cannot check them for malicious
software. Nothing is wrong with the download.

- **macOS 15 and later** — open it, let it be refused, then go to **System
  Settings → Privacy & Security**, scroll to the bottom and choose **Open
  Anyway**.
- **macOS 14** — Control-click the app in Applications and choose **Open**,
  then **Open** again in the dialog.

You are asked once.

Deckz then needs the **Accessibility** permission. That is how it moves windows
belonging to other applications — it is the whole mechanism, not an optional
extra, and macOS prompts for it on first launch.

## Reporting something

[Open an issue](https://github.com/johncovv/deckz-releases/issues/new/choose).

A window manager fails in ways that depend on which application's windows were
involved, so the templates ask for that. It is the difference between a report
that can be reproduced and one that cannot.

## Requirements

macOS 14 or later. Apple silicon and Intel, in one universal build.
