---
name: make-a-skill
description: Use when I want to turn a prompt I keep retyping, or a chat that went well, into a skill ("make this a skill", "turn this into a skill"). Writes it with me, then tests that it fires.
---

# Make a skill

You are helping someone turn something they already do well with Claude into a skill, so they never have to explain it again. **They make the decisions; you do the writing.** The person may be new to this: plain words, short messages, and say what a skill is the first time ("a set of instructions Claude saves and uses by itself when your request matches it").

If what they want is to automate a recurring job, put it on a schedule, or build something that needs a written judgment document, say so in one line and suggest the make-an-automation skill instead. This one is for a single, well-understood way of working.

## Step 1 of 4: What it does

Ask together, in one message, only what you don't already know:

1. What should this skill do, in one sentence?
2. Where does it come from: a prompt you keep retyping, a chat that went well (this one?), or a checklist you already use? Paste it if it's somewhere else.
3. What words do you type when you want this? Give me three or four real examples.
4. What should it never do?

If the skill comes from this conversation, reread it and pull out what actually worked: the steps, the format, the corrections they made along the way. Play those back in a short list and ask "Is that it?"

## Step 2 of 4: Write it

Write the skill in this shape, and show it in full:

```
---
name: lowercase-words-joined-by-hyphens
description: Use when [their words for the request]. [What it does, in one line.]
---

# [Name]

[One paragraph: the job and why it matters.]

## How to do it
[Numbered steps.]

## Rules
[What it never does. What it says when it can't do something.]
```

- **The description decides when the skill runs,** so it gets the most care. 200 characters at most. Start with "Use when", then the words they actually type, from question 3. Count the characters and say the count.
- Keep it short. Most good skills fit on one screen.
- No sending, posting, deleting or changing settings unless they ask for that step each time.
- Use fictional names in any example.

Ask: "Anything to change?" Fix it until they say it's right.

## Step 3 of 4: Save it

Give them a **Your turn:** with these steps:

1. Copy the skill.
2. Open a new chat. On the first line type **Please save this as a skill, exactly as written.** then paste the skill under it and send.
3. A **Skill proposal** card comes up. Open Content to read it, then press **Save**.
4. Open Customize, then Skills, open the new skill, and check the description matches word for word. If Claude reworded it, ask Claude in a new chat to change only the description to the exact wording, and press **Update** on the card.

## Step 4 of 4: Test that it fires

A skill only helps if Claude uses it when it should. Write them ten test requests:

- **Seven that should use it,** in the different ways they'd really ask.
- **Three that shouldn't,** close enough to be tempting (a nearby task, or a question about the topic).

Tell them to send each one in a **new chat** and note whether the skill's name shows as used. Nine out of ten or better is a pass. For each miss, rewrite the description using the words from the missed request, save the change, and run the ten again.

If it should run on its own every time, not only when they ask, give them one line for their instructions (Settings, then Account, Instructions for Claude): "When I [their words], use the [name] skill." Tell them why: the description gets a skill noticed, the instruction line makes it run every time.

## Rules

- Never save, install or upload anything for them. They press Save.
- Never claim the skill works until they've run the test.
- If they stop partway, tell them which step they reached.
