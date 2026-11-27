---
name: context-interview
description: Use when I ask for the context interview, or want to set up or rebuild my context skill, the picture of my work, organisation or clients. Interviews me and makes my own my-context skill.
---

# Context interview

Your job is to interview me about my work and make me my own skill called **my-context**: a short, high-level picture of my work and the world I work in, which Claude reads whenever it's doing my work. The skill you make is mine: I keep it current, and updates to this interview never change it. I don't want to have to think about how it's built. Ask me questions and do the rest.

## If I already have a my-context skill

Ask first: "You already have a my-context skill. Do you want to update it, or start again?" To update it, read it, ask what has changed, and propose the exact lines to add or change. On a yes, give me the whole updated skill in one block I can copy, with a dated line under Changes and the description line unchanged. Then go to **Save it** below, as a replacement.

## The interview

1. **Start from what you already know.** Check what you already have about me (my instructions, my projects, this chat) and ask only about the gaps.
2. **Interview me, one question at a time,** about:
   - **Who I work with:** my organisation or clients, my team, and who I report to.
   - **The key players:** the people and organisations that matter most in my work, and what each one is to me (a funder, a partner, a client, a colleague).
   - **My main initiatives:** the big pieces of work I'm doing, in a line or two each.
   - **The key relationships:** who I work most closely with on what.

   Keep it factual: who people are and what we work on together, never opinions about them.
3. **Offer to look in my Drive,** if it's connected, for anything that fills gaps (an org chart, a strategy document, a workplan). Show me what you found and ask me to confirm before you use any of it.
4. **Draft one page,** 400 to 500 words, under those four headings, in the shape at the bottom of the skill below. Show it to me and ask what's wrong or missing. It will have mistakes, so wait for my corrections.
5. **Make the skill.** Put the page into the skill below where it says [MY CONTEXT], and give me the whole skill in one block I can copy, fenced with four backticks so nothing inside breaks it. Change nothing else in it, including the description line.

Ask me anything you're unsure about. Don't guess.

## Save it

Give me a **Your turn:** with these steps:

1. Copy the skill.
2. Open a new chat. On the first line type **Please save this as a skill, exactly as written.** If you're replacing a my-context skill you already have, type this instead: **"This replaces my existing my-context skill. Please write it to a SKILL.md file exactly as written and present it so the Update card comes up."** Paste the skill under it and send.
3. A card comes up with the skill on it. Click **Content** on the card to read it, then press **Save** (or **Update** if you're replacing one).
4. Check the saved description matches the one in the block word for word. That line decides when the skill runs.
5. **For a team:** if everyone should share the same picture of the organisation, the admin can add it as an organisation skill.

Then suggest a test: in a new chat, ask "Who are the key players in my work? Tell me where you read it." If the answer is right and it says it read my-context, it's working.

## Rules

- Keep it factual. No opinions about people and no personal details.
- Never guess a name, a job title or a figure.
- Don't send, post or share anything.

## The skill you make

````
---
name: my-context
description: Use whenever a task touches my work, such as my organisation or clients, the people I work with, key players, partners or my main initiatives. Gives Claude the background so drafts get it right.
---

# My context

Your job is to start from the bigger picture of my work whenever you're doing something for me: who I work with, the key players, my main initiatives and my key relationships. Everything you need is in **My context** at the bottom of this skill. Read the parts that bear on the task before you start.

This is background, not a task list and not project detail. My tasks are in my daily plan and the detail of each piece of work is in my projects.

## Every task

1. Read the parts that apply. Use names, roles and initiative names exactly as they're written here.
2. If the task needs a fact that isn't here, say so and ask. Never guess a name, a job title or a figure.
3. If what's here looks out of date (a role has changed, an initiative has ended), say so once and offer to update it.

## When something changes

When I say "Please update my context skill to include…", or tell you something has changed, propose the exact lines to change. On a yes, give me the whole updated skill in one block, with a dated line under Changes, and a **Your turn:** to save it: open a new chat, type "This replaces my existing my-context skill. Please write it to a SKILL.md file exactly as written and present it so the Update card comes up.", paste the skill under it, send, and press **Update**.

## Rules

- This is factual background. No opinions about people and no personal details.
- Don't send, post or share anything.

## My context

[MY CONTEXT]

<!-- One page, 400 to 500 words, under these headings:
**Who I work with:** my organisation or clients, my team, who I report to
**The key players:** people and organisations, and what each one is to me
**My main initiatives:** a line or two each
**The key relationships:** who I work most closely with on what
**Changes:** dated lines -->
````
