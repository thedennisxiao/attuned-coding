# Installing Your Toolkit
## Attuned Code — Pre-Workshop Setup

Welcome. Before our day together, there's a small amount of setup to do
on your laptop. We're doing this beforehand so that when we begin,
we can begin — with presence, not logistics.

**Estimated time:** 15–20 minutes, unhurried.
**Technical skill required:** None.
**If you get stuck:** Email Dennis. Seriously. We'll sort it before the day.

---

## What You'll Have at the End

By the time you're done, your laptop will have:

1. **Claude Code** — a way of talking to Claude that lives on your computer
   and can see your files, not just in a browser window.
2. **A small toolkit of skills** — specialists you can call on during the
   workshop. You don't need to understand what they do yet. You'll meet
   them on the day.

That's it. Two things.

---

## Step 1 — Install Claude Code

Claude Code is a free tool from Anthropic (the company that makes Claude).
It's a small program you install on your laptop.

### If you're on a Mac

1. Open the app called **Terminal**.
   (It's in Applications → Utilities. Or hit `⌘ + Space` and type "terminal".)
2. Copy the line below, paste it into Terminal, and press Enter:

   ```
   [DENNIS: paste the exact one-line Claude Code installer here —
    e.g. the curl command from https://docs.claude.com/en/docs/claude-code]
   ```

3. Follow any prompts. It may ask for your password — this is normal.
4. When it's done, type `claude` and press Enter. If Claude greets you,
   you're in. If not, reach out.

### If you're on Windows

[DENNIS: fill in — Windows instructions, or direct people to email you
if they're on Windows and you'd rather troubleshoot directly.]

### If you've never opened Terminal before

That's completely fine. Terminal is just a text window where you type
instructions to your computer instead of clicking. You won't need to
learn anything about it — we just need it for this one install.

---

## Step 2 — Sign In

The first time you run `claude`, it will ask you to sign in with your
Claude account (the same one you use at claude.ai).

If you don't have a Claude account yet, create one at **claude.ai** first.
Then come back here.

Follow the prompts. It usually opens your browser, asks you to approve,
and then returns you to Terminal.

---

## Step 3 — Install the Workshop Toolkit

We're going to add a small set of "skills" to Claude Code. Think of them as
specialists you can call on by name during the workshop.

In Terminal, with `claude` running, type each of these one at a time
and press Enter after each:

```
[DENNIS: exact /plugin install commands or skill install commands for:
  - compound-engineering
  - impeccable
  - frontend-design
  - every-style-editor]
```

### Then add `/begin` — your starting ritual

`/begin` is a small skill written specifically for this workshop. It walks
you, gently and one question at a time, through setting up the ground for
any new project: who you are, what you're making, and how Claude should
work with you on it. You'll meet it on the day, and you'll have it forever
after, for any project you ever start.

To install it, in Terminal (with `claude` running), type:

```
[DENNIS: the /skill install command pointing at thedennisxiao/attuned-coding-skills,
 once the repo is public. Until then, this can be a manual download + place into
 ~/.claude/skills/begin/ from the .skill file.]
```

If one of them gives an error, don't worry. Email Dennis with the
error message and we'll sort it together.

---

## Step 4 — Check That It Worked

You're almost done. One quick sanity check.

With `claude` running, type:

```
/help
```

You should see a list of commands. Somewhere in there, you'll see the
skills you just installed, including `/begin`. If you see them, you're set.

You can close Terminal now. Everything's saved.

---

## If Something Goes Wrong

Don't sit with it alone. This is normal and expected.

- **Email Dennis:** [DENNIS: your email]
- **Tell me:** what you tried, what you saw, and a screenshot if you have one.
- **I'll write back** with the next step, or we'll hop on a call if it's easier.

There is no version of this where you show up to the workshop having
not managed it and we can't fix it. That's a promise.

---

## A Final Note

If any part of this made you feel like you're "not technical" — please
notice that and set it gently aside. Installing software is a task, not
an identity. People who've never touched a Terminal in their lives have
done this before our first call and arrived feeling quietly capable.

You will too.

See you soon.

— Dennis
