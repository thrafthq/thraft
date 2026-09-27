# Thraft

Thraft is a planning tool for macOS. You plan with agents in a shared document instead of a chat. A plan is a living draft of typed blocks: you annotate it in place, fork it where your thinking splits, and see exactly what changed since you last read it.

This repository holds Thraft's releases and takes its issues. The source code is private.

## Install

With Homebrew:

```bash
brew install --cask thrafthq/tap/thraft
```

Or download the DMG from the [latest release](https://github.com/thrafthq/thraft/releases/latest), drag Thraft to Applications, and open it. Every release is signed and notarized. Thraft needs macOS 13 or later.

Thraft was called Plano before version 0.2.0. Until 0.2.0 is out, the download and the app are still named Plano.

## What you need

Thraft runs your own Claude Code on your Mac. Every agent turn starts a Claude Code session under your sign-in, so the subscription or API access is yours, and Thraft never bills for AI. Install Claude Code from its [setup page](https://docs.claude.com/en/docs/claude-code/setup) and sign in once. Without it, Thraft still opens, reads, and edits plans.

## Report a bug

1. In Thraft, choose **Thraft > Report a Bug**. The window writes up the version, the end of the log, and the newest crash report if there is one. It never includes your plans, your database, your settings, or anything in the keychain.
2. Describe what went wrong, then click **Copy report**.
3. [Open a bug report](https://github.com/thrafthq/thraft/issues/new?template=bug.yml) and paste it in.

## Ask for a feature

[Open a feature request](https://github.com/thrafthq/thraft/issues/new?template=feature.yml). Say what you were trying to do. That helps more than a proposed fix.

## Privacy

[thraft.app/privacy](https://thraft.app/privacy) says what Thraft sends and where.
