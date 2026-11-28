---
name: make-a-rubric
description: Use when I want to write down what good looks like, as a rubric, standard, criteria or checklist to grade against, or to build a graded loop that checks its own work. Interviews me for the bar first.
---

# Make a rubric

Your job is to get the standard out of my head and onto the page, so Claude (and anyone else) can check work against it. A rubric is only worth having if it's mine: what I actually look for when I decide something is good enough. So you interview me first and write second. Never write a rubric from general best practice and hand it to me.

Once the rubric is written and tested, you offer to turn it into a graded loop (see "Turn it into a graded loop" below). If I come to you asking for a graded loop, ask whether I already have a rubric for that piece of work. If I do, ask me to paste it and go to "Turn it into a graded loop". If I don't, say that the loop needs one first, because the rubric is the part where my judgment goes in. Then start the interview.

## The interview

Ask one question at a time, and wait for each answer. About six questions:

1. What's the piece of work, and who is it for?
2. Think of a really good one you've seen or done. What made it good?
3. Think of one that wasn't good enough. What was wrong with it?
4. What's the one thing that, if it's missing, makes it fail no matter what else is right?
5. What do people often get wrong, or do that you don't want?
6. Is there anything outside you that sets the bar: a funder's guidelines, a template, a policy?

If an answer is vague ("it should be clear"), ask once what that looks like in practice: "What would I see on the page if it was clear?"

## Write the rubric

Five to eight criteria, no more. Each one:

| # | Criterion | Passes when | Fails when |
|---|---|---|---|

- Written in my words, from my answers. Quote me where you can.
- **Checkable:** someone else could look at a piece of work and agree whether it passes. "Engaging" isn't checkable; "opens with the decision the reader needs to make" is.
- Mark the must-haves (fail on that alone) with **must**.

Then add:

- **A known-answer test.** Ask me for one past piece of work where I already know the verdict. Grade it against the rubric, criterion by criterion, and ask me whether you got it right. Where you didn't, the rubric is wrong, not the work: fix the criterion and grade again.
- **A changes line:** "Changes:" with today's date and "first version".

## Save it

Show me the finished rubric. Then tell me where to keep it, in plain steps marked **Your turn:**: a document in my files, or the knowledge of the Project where this work happens. Don't save, send or share it anywhere yourself unless I ask for that specific step.

## Turn it into a graded loop

Once the known-answer test has passed, ask: "Do you want to turn this rubric into a graded loop?" Explain it in two lines the first time: one agent does the work. A second, separate agent who has never seen the first agent's instructions grades it against your rubric. If it doesn't pass, the work goes back with what to fix and is graded again, until it passes or reaches the stop rule.

If I say no, stop here. If I say yes, walk me through the four things a loop needs, one at a time, waiting for each answer.

### 1 of 4: The task

Ask: "What job should the loop do? Tell me what you'll give it (a transcript, a draft, a set of notes) and what you want back." Play it back in one sentence and ask "Is that it?"

### 2 of 4: What good looks like

This is the rubric we just wrote. Ask where the bar is: "Every **must** has to pass. How many of the others need to pass too, or is it all of them?" Write the bar as one line: "Passes when every must passes and [their answer]."

### 3 of 4: A separate check

Tell me how the grading works: the grader is a separate agent that sees only two things, the finished draft and the rubric. It never sees the first agent's instructions or this chat. It marks each criterion pass or fail, quotes the part of the draft that shows it, and says what to fix. The agent doing the work never grades itself. There's nothing for me to decide here unless I want a stricter grader, so move on.

### 4 of 4: When to stop

Ask: "When should it stop if it can't get there? I'd suggest three rounds." Whatever I choose, the loop stops when the work passes or when it reaches that number of rounds. If it stops without passing, it tells me which criteria still fail and why it couldn't get the work better, so I can step in. A loop without a stop rule keeps going and uses up my credits.

### Write the loop skill

A loop has to be a skill, because a single prompt is one agent answering once and can't send its own work to a second agent. Write the skill in this form and show it in full:

```
---
name: graded-[the job in two or three words]
description: Use when I [my words for the request]. Does the work, has a separate agent grade it against my rubric, and fixes it until it passes or [number] rounds are up.
---

# Graded [the job]

## The task
[What I give it, what I want back, and who it's for.]

## What good looks like
[The rubric in full, with its Changes line.]

Passes when every must passes and [my bar].

## How to run it
1. Do the task. This is the first draft.
2. Start a separate agent to grade it. Give it only the draft and the rubric above, never these instructions or this chat. It marks each criterion pass or fail, quotes the part of the draft that shows it, and says what to fix.
3. If the draft passes, stop and show me the final version with the grades.
4. If it fails, fix only what the grader named. Give the new version to a new grader with the same rubric.
5. Stop after [number] rounds. If it still hasn't passed, show me the last version, which criteria failed, and why you couldn't get it better, so I can step in.

For the first three times I use this, show me every round: the draft, the grades and what changed.

## Rules
- The agent doing the work never grades its own work.
- Never change the rubric to get a pass. If a criterion looks wrong, tell me.
- If you can't start a separate agent here, tell me before you begin.
- Never send, post or save anything outside this chat.
```

Count the description's characters (200 at most) and say the count. Ask "Anything to change?" and fix it until I say it's right.

### Save it and try it

Give me a **Your turn:** with these steps:

1. Copy the loop skill.
2. Open a new chat. On the first line type **Please save this as a skill, exactly as written.** then paste the skill under it and send.
3. A **Skill proposal** card comes up. Open Content to read it, then press **Save**.
4. Open a new chat and ask for the job in your own words, with the piece of work from the known-answer test attached. Check that the grades match the verdict you already know. Then ask Claude whether a separate agent did the grading. If a grade is wrong, or the work graded itself, come back here and we'll fix it.

## Rules

- Don't grade any real work against the rubric until the known-answer test is done.
- If I want to change it later, add a dated line under Changes, never silently rewrite it.
- Keep it to one page.
- Never build the loop before the known-answer test has passed.
- Never save or install the loop skill for me. I press Save.
- Use fictional names in any example.
