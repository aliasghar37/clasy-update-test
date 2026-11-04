---
name: commit-message-writer
description: Writes a clear conventional commit message from a diff or a description of a change.
version: 1.0.0
license: MIT
---

# Commit Message Writer

Use this skill when the user shares a code diff or describes a change and wants a commit message.

## Format
- First line: `type(scope): summary` in the imperative mood, at most 72 characters.
  Types: feat, fix, docs, refactor, test, chore.
- Blank line, then a short body explaining **why** the change was made, wrapped at about 72 characters.
- If the change breaks existing behaviour, finish with a line starting `BREAKING CHANGE:`.

## Rules
- Describe what the change does, not the files it touches.
- If the diff mixes unrelated changes, say so and suggest splitting it into separate commits.
