---
name: design-interview
description: Use when I ask for the design interview, or want to set up or change my design system, brand look, colours, fonts or logo. Interviews me and saves my look as my own design system.
---

# Design interview

Your job is to help me set up a **design system** in Claude, so that anything visual you make for me (documents, one-pagers, slides, pages) comes out in my look without me asking. Walk me through it one step at a time. I don't want to have to work out how it's built. The design system you make is mine: I keep changing it, and updates to this interview never change it.

## If I already have a design system

Ask first: "You already have a design system. Do you want to change it, or start a new one?" You can have more than one, for example one for each organisation you work for. To change one, ask what's off and work through the steps below that apply.

## The interview

1. **Ask me what I have:** a brand guide, a logo, a website, a deck or document I like the look of, a screenshot of something in my look, or nothing yet. Ask me to share whatever I have, one thing at a time.
2. **Pull out my look.** From what I share, pull out my main colours (with hex codes), my fonts, how my logo is used, and the overall feel (for example: calm and plain, or bold and bright). If I have nothing, help me choose: suggest two or three simple looks that suit my work, with two colours and one font each, and let me pick.
3. **Check my colours for contrast.** Tell me plainly if a colour is too light for text, and suggest using it for accents only, with a darker colour for text.
4. **Show me a one-page summary of my look:** colours, fonts, logo use, feel, and two or three do's and don'ts. Ask me what's wrong or missing, and wait for my corrections. Treat this first version as version zero.
5. **Help me save it as a design system in Claude.** Tell me exactly where to go and what to click, as short numbered steps. If you can create it for me from this chat, offer to.
6. **Show me where to find my design systems and set a default,** in short numbered steps: to choose one, the **+** button in a chat, then **Design system**; to set the default, **Settings**, then **Capabilities**, then manage my design systems. If I'm on an organisation's plan, tell me my admin may set this for everyone.
7. **Finish with a test:** tell me to open a new chat and ask for a one-slide deck about my work, without mentioning design. If it comes out in my look, it's working. If it doesn't, help me find what's missing.
8. **Offer the my-design skill too.** A design system styles slides and documents made from Claude's templates. Pages, one-pagers and charts made in a chat read a skill instead. Ask whether I'd like my look saved as my own **my-design** skill as well. If I say yes, put my look into the skill below where it says [MY PROFILE], give me the whole skill in one block I can copy, fenced with four backticks so nothing inside breaks it, and go to **Save the skill**. Change nothing else in it, including the description line.

Ask me anything you're unsure about. Don't guess.

## Save the skill

Give me a **Your turn:** with these steps:

1. Copy the skill.
2. Open a new chat. On the first line type **Please save this as a skill, exactly as written.** If you're replacing a my-design skill you already have, type this instead: **"This replaces my existing my-design skill. Please write it to a SKILL.md file exactly as written and present it so the Update card comes up."** Paste the skill under it and send.
3. A card comes up with the skill on it. Click **Content** on the card to read it, then press **Save** (or **Update** if you're replacing one).
4. Check the saved description matches the one in the block word for word. That line decides when the skill runs.

## Rules

- Never pick a colour, font or rule I didn't give you or choose.
- Never use a logo or image you can't see. If you need my logo, ask me for it.
- Don't publish, share or send anything.

## The skill you make

````
---
name: my-design
description: Use whenever I ask for anything visual, such as a page, one-pager, chart, slide, document layout or artifact. Applies my brand's colours, fonts, logo rules and tone from my design profile.
---

# My design

Your job is to make anything visual look like it came from me: my colours, my fonts, my logo used the right way, and my tone. Everything you need is in **My design profile** at the bottom of this skill. Read it before you make anything.

## Every piece

1. Read the profile. Use its colours, fonts and rules exactly.
2. **Check before you show me:** colours only from the palette, the accent colour used sparingly, text readable against its background, the logo used by its rules, nothing from the "Never" list.
3. If the profile doesn't cover something (a chart needs more colours than the palette has), say what you chose and why.

## Where this works, and where it doesn't

This skill styles what you make in a chat: pages, artifacts, one-pagers, charts. Slide decks and documents made from claude.ai's own templates read my **design system** instead. If I ask for one of those, use my design system, and if I don't have one, offer to help me set one up from this profile.

## When I change something

If I change something ("make the headings darker"), ask once whether to add it to the profile, and propose the exact line. On a yes, give me the whole updated skill in one block, with a dated line under Changes, and a **Your turn:** to save it: open a new chat, type "This replaces my existing my-design skill. Please write it to a SKILL.md file exactly as written and present it so the Update card comes up.", paste the skill under it, send, and press **Update**.

## Rules

- Don't publish, share or send anything you make.
- Never use a logo or image you can't see. If you need my logo, ask me for it.

## My design profile

[MY PROFILE]

<!-- The profile has these parts:
**Colours:** each with its hex code and what it's for (base, text, accent, secondary)
**Fonts:** headings, body, and any third font with what it's for
**Logo:** where it is and its rules
**How it should feel:** three words, each with one line on what it means visually
**Layout habits:** spacing, alignment, how headings look
**Never:** ...
**Changes:** dated lines -->
````
