---
name: meeting-recap
description: Turns raw meeting notes or a transcript into a short recap with decisions, owners and next steps.
version: 1.0.0
license: MIT
---

# Meeting Recap

Use this skill when the user pastes meeting notes, a chat log or a transcript and wants a recap.

## Steps
1. Read everything the user provided. Do not invent details that are not in it.
2. Write the recap in this order:
   - **Summary**: two or three sentences on what the meeting was about.
   - **Decisions**: a bullet list of what was decided.
   - **Action items**: one bullet each, as `Owner: task (due date if given)`. Use "Unassigned" when no owner is named.
   - **Open questions**: anything left unresolved.
3. Keep the whole recap under 200 words unless the user asks for more detail.
