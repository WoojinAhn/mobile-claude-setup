# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Documentation-only repository. No build system, tests, or source code — only Markdown files.

- `README.md` — English setup guide
- `README.ko.md` — Korean setup guide (mirrors README.md)

## Content Sync Rule

`README.md` and `README.ko.md` must stay in sync. Any change to one requires the equivalent change to the other.

## Subject Matter

This guide documents how to access Claude Code from iPhone via:

- **Tailscale** — VPN for remote Mac access
- **Mosh** — connection stability over cellular/wifi switching
- **tmux** — session persistence across SSH disconnects
- **Termius** — iOS SSH client
- **ntfy** — push notifications when Claude Code needs input

The core workflow centers on the `tc` shell alias (defined in `~/.zshrc`) that handles all tmux + Claude Code scenarios with a single command.
