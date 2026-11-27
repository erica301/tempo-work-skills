---
name: wrap-session
description: Use when I say wrap up, wrap the session or I'm done for today. Looks back through this chat and proposes updates to my voice, skills, instructions and daily plan, each for my yes or no.
---

# Wrap session

Your job is to make sure what I taught you in this chat isn't lost when it ends. Read back through this conversation, find what should change in my setup, and propose it. I decide. You never change anything without my yes.

## What to look for

Read the whole conversation, start to finish. Look for:

1. **My voice.** Where I rewrote your draft, said a phrase isn't me, or showed you what I like.
2. **My skills.** Where a skill of mine missed something, or I corrected how it worked.
3. **My instructions.** New facts about me, my role or how I want you to work with me.
4. **Project instructions.** If this chat is in a project, or is about work that has one, facts about that work that changed, such as a deadline, a person or a decision.
5. **My daily plan.** Anything that changes what my daily plan should know: my priorities, my goals, what I'm not focusing on, the people who matter most, or a kind of email or task I want handled differently.

Only propose what I actually said or did in this chat. Never infer a preference I didn't show you.

## Propose

If nothing is worth keeping, say so in one line and stop.

Otherwise, give a numbered list, at most six, most useful first. For each one:

- **Where it goes:** the skill's name, "your instructions", "this project's instructions" (name the project) or "your daily plan".
- **What to add or change:** the exact words, ready to paste.
- **Why:** the moment in this chat it comes from, quoted briefly.

Then ask: "Which of these do you want? Answer by number, or none."

## Apply the ones I say yes to

Put all my yeses into one short set of steps, each starting with **Your turn:**

- **A skill of mine:** open a new chat, ask Claude to update the [name] skill with the change below, then press **Update** on the card that comes up. Show the full new section, not just the new line.
- **My instructions:** open Settings, then Account, then Instructions for Claude, paste the line at the end, and save.
- **Project instructions:** open the project, edit its instructions, paste the line, and save.
- **My daily plan:** don't give me steps for these. Add each yes as a teaching note, the same as pressing Teach on the page: with your ArtifactData tool, on my Daily Plan artifact, add a document to the collection `data/users/me/teach/rules` with `text` (one plain sentence in my words), `about` (a word or two, such as priorities, email or a person's name) and `status` "new". My next morning run turns each new note into a standing rule and shows it on the page. Read the guide at the top of my Daily Plan first, and change nothing else in its data. If you don't know my Daily Plan's link, ask me for it. If you can't write to it, give me the sentence and tell me to press Teach on the page and paste it in.

## Rules

- Never change a skill, an instruction or a setting yourself. Every change waits for my yes to that specific item. The one thing you write yourself, after my yes, is a daily plan teaching note.
- A skill that came in a plugin (its name starts with the plugin's name, like tempo-work:) isn't mine to edit. Don't propose changes to it. If it missed something, suggest I tell the person who made it.
- Nothing private or confidential goes into a skill or instructions unless I ask, and never another person's personal details.
- Keep it short. This runs at the end of a session, when I want to be done.
