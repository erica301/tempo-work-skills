---
name: security-check
description: Use when I ask for my security check, a privacy or permissions review, or what Claude can reach and do in my account. Reports what's connected and allowed; never changes settings.
---

# My security check

Your job is to tell me, in plain words, what Claude can currently reach and do in my account, and what I should change. You report. You never change a setting, disconnect anything, or delete anything.

## What you can see, and what you can't

You can see some of this from your own tools (which connectors and tools you have, which skills are available, which scheduled tasks exist if you have the tools to list them). You usually can't see my settings pages (permission levels, sharing, privacy settings), though a Blocked tool is missing from your tool list. For those, ask me to open the page and tell you what I see, one question at a time, and mark those lines **checked by you, not by me**. Never guess a setting.

## The checks

1. **Connectors.** List every connector that is connected, by the name I'll see in Customize, then Connectors. Leave out ones my organisation only makes available to connect. Then list, separately, any built-in tools you have that can act but don't appear on that page (for example document or scheduled-task tools), and say they're built in. If you can't tell which are connected, ask me.
2. **Tools that act.** A tool set to **Blocked** is removed from your tool list, so start from what you can see.
   - For each connector, list the tools in your own list that can send, reply, forward, share, invite, post, upload or delete. Each one is **not Blocked**. Any of those that sends, replies, forwards or deletes is **Change this**: a scheduled task set to Automatically approve may approve it without me. Say whether you can see a scheduled task set to Automatic. Include the built-in tools from check 1. If a tool only sends feedback to the company that makes it, not to a person, still mark it **Change this** but say so.
   - You can't tell **Always allow** from **Needs approval**. Ask me which each one is, and mark the answer **checked by you, not by me**.
   - A tool you'd expect but can't see is either Blocked or not offered by that connector. Say which tools you expected and didn't find, and ask me to confirm they show as Blocked in Customize, then Connectors.
3. **Scheduled tasks.** If you can list them, show each one's name and when it runs, and flag any whose instructions would send or post anything, or delete my email, files or notes. A task that only clears out its own old output isn't a finding; mention it in one line. If you can't list them, ask me to open **Scheduled** in the sidebar and say how many there are.
4. **Skills.** List the skills available to you, with the ones I added first. Say that your list includes built-in skills that may not appear on my Skills page, so a mismatch there isn't a problem. Ask me which of the ones I added are new since my last check, and suggest running check-before-install on any I haven't checked.
5. **Sharing.** Ask me whether any of my artifacts, projects or chats are shared with "anyone with the link", and whether that's still what I want.
6. **Plan and training setting.** Ask which Claude plan I'm on. On a personal plan, ask whether "Help improve Claude" is on or off, and say in one line what that setting does.
7. **What stays out.** Ask whether anything in a connected drive or inbox belongs in the "keep it out" group: passwords and keys, ID numbers, bank details, health or patient records, anything about children. If so, suggest moving it somewhere Claude can't reach.

## The report

Start with one line: "Security check, <date>: <N> things to change, <N> checked by you, <N> I couldn't check."

Then a table, things to change first:

| Check | What I found | Status | What to do |
|---|---|---|---|

Status is one of: **OK**, **Change this**, **Checked by you, not by me**, **Couldn't check**.

End with: "Nothing was changed. If you change a setting, run this check again to see it."

## Offer to run it every week

When I run this by hand, end by asking whether I'd like it to run once a week on its own. Skip the offer if you can see it's already scheduled, and never make it during a scheduled run.

If I say yes, set it up with me as a scheduled task. Before you create anything, tell me in plain language what each run will do, the day and time it will run, which of my connected tools it will use, and where I'll find the report. Ask my permission before you create it. Once it exists, suggest I click Run Now and we read the first report together. Each run follows this skill exactly and changes nothing.

## If this runs on a schedule

Run every check you can do with your own tools, skip the questions, and list each skipped question as **Couldn't check: needs you**. Never report "all clear" for a check you couldn't run. Put the one-line summary first. Never send, post or share the report anywhere.

## Prove it works, once

The first time someone sets this up, suggest a test: set one sending tool to Needs approval, run the check, and confirm it's flagged. Then set it back. A check that has never been seen to flag anything hasn't been tested.
