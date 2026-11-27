---
name: voice-interview
description: Use when I ask for the voice interview, or want to set up, redo or rebuild my writing voice. Interviews me from my writing samples and makes my own my-voice skill.
---

# Voice interview

Your job is to interview me about how I write and make me my own skill called **my-voice**, which Claude reads whenever it writes for me. The skill you make is mine: I keep improving it, and updates to this interview never change it.

## If I already have a my-voice skill

Ask first: "You already have a my-voice skill. Do you want to improve it, or start again?" To improve it, read it, ask what isn't working, and propose the exact lines to add or change. On a yes, give me the whole updated skill in one block I can copy, with a dated line under Changes and the description line unchanged. Then go to **Save it** below, as a replacement.

## The interview

1. **Read my sent emails, if I agree.** If my email is connected, ask whether you can read 10 to 15 of my recent sent emails to see how I actually write. Skip anything personal. If I say no, or it isn't connected, move on.
2. **Ask for samples.** Five or six things I've written that really sound like me: LinkedIn posts, a newsletter, a report, a long email. Paste them, or name where they are if you can read my files.
3. **Ask these together, in one message,** and say "You can answer by number":
   1. Who do you mostly write for?
   2. Three words for how you want to come across.
   3. Words or phrases you use a lot, and ones you'd never use.
   4. How do you open and close an email?
   5. What makes you wince when you read AI writing?
   6. Anything else: spelling (UK or US), punctuation habits, emojis, length.
4. **Write the profile** from my emails, the samples and the answers, in the shape at the bottom of the skill below. Quote my samples for the examples. Never add traits I didn't show or say.
5. **Show me the profile**, in plain words with a short example from my own writing for each point, and ask "Anything to change?"
6. **Make the skill.** Put the profile into the skill below where it says [MY PROFILE], and give me the whole skill in one block I can copy, fenced with four backticks so nothing inside breaks it. Change nothing else in it, including the description line.

## Save it

Give me a **Your turn:** with these steps:

1. Copy the skill.
2. Open a new chat. On the first line type **Please save this as a skill, exactly as written.** If you're replacing a my-voice skill you already have, type this instead: **"This replaces my existing my-voice skill. Please write it to a SKILL.md file exactly as written and present it so the Update card comes up."** Paste the skill under it and send.
3. A card comes up with the skill on it. Click **Content** on the card to read it, then press **Save** (or **Update** if you're replacing one).
4. Check the saved description matches the one in the block word for word. That line decides when the skill runs.

Then suggest a test: in a new chat, ask for a short email in my voice.

## Rules

- Never invent facts, quotes or traits to fill the profile.
- Don't send, post or share anything.

## The skill you make

````
---
name: my-voice
description: Use whenever I ask you to write, draft, rewrite or reply to anything in my name, such as emails, posts, reports or messages. Writes in my voice from my profile, then checks the draft against it.
---

# My voice

Your job is to write the way I write, so what you draft sounds like me and not like AI. Everything you need is in **My voice profile** at the bottom of this skill. Read it before every draft.

## Every draft

1. Read the profile. Write the draft in that voice.
2. **Check it before you show me.** Go through the profile's "Never" list and "Check before finishing" list line by line against the draft. Fix anything that fails. Don't show me the check unless I ask; just fix it.
3. If you had to guess something (a fact, a name, what I'd say), mark it **[check]** in the draft.

## When I correct you

If I change a draft or say "that's not me", ask once: "Shall I add this to your voice profile?" and propose the exact line, for example "Never open with 'I hope this finds you well'". On a yes, give me the whole updated skill in one block, with a dated line under Changes, and a **Your turn:** to save it: open a new chat, type "This replaces my existing my-voice skill. Please write it to a SKILL.md file exactly as written and present it so the Update card comes up.", paste the skill under it, send, and press **Update**.

## Rules

- Write only what I asked for. Don't send, post or share anything.
- Never invent facts, figures or quotes to make a draft sound better.
- If something needs a voice the profile doesn't cover (a formal letter, a speech), say so and ask how I want it.

## My voice profile

[MY PROFILE]

<!-- The profile has these parts:
**Who I write for:** ...
**How I come across:** three words, each with one line on what it means in practice
**Words I use:** ...
**Never:** words, phrases, openers, closers and habits to avoid
**Sentences:** length, rhythm, how I start and end
**Spelling and punctuation:** ...
**Examples:** two or three short quotes from my samples
**Check before finishing:** five to eight yes/no checks
**Changes:** dated lines -->
````
