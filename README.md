# /yang: research someone before you reach out

Download: [SKILL.md](SKILL.md) · [yang.zip](yang.zip) (for claude.ai)

A Claude skill. Before a call, visit or cold message, ask Claude to run it on a person or business. It researches them from several angles, argues for and against your next move, and gives you one verdict, a specific opening line, one question to ask, and the next step. Every finding comes with a source and a label: what someone said, what a source says, or what Claude inferred.

Based on Jay Yang's do-the-work-first approach, with one rule on top: research sharpens your questions, but their own words decide the fix. Not affiliated with or endorsed by Jay Yang.

## Install

Claude Code (laptop):
1. Download `SKILL.md`.
2. Save it as `~/.claude/skills/yang/SKILL.md` (Windows: `C:\Users\<you>\.claude\skills\yang\SKILL.md`).
3. In Claude Code, type `/yang Jane Doe, ABC Plumbing, Austin`.

claude.ai (upload on a computer, then use it anywhere you're signed in):
1. Download `yang.zip`.
2. On claude.ai go to Customize, Skills, "+", Create skill, Upload a skill, and pick the zip.
3. In any chat, type: "Use the yang skill on Jane Doe, ABC Plumbing, Austin."

Phone only, no install: open `SKILL.md`, copy all of it, paste it into a Claude chat, and add "Run this on: <name>".

## Example (made up)

> Use the yang skill on Maria Lopez, Lopez HVAC, Phoenix. I'm calling her Thursday.

Verdict: call Thursday morning and ask about after-hours calls; don't pitch anything yet.
What we found: the site's contact form says "we respond within 2 business days" (source says, their site, checked today); 3 of the last 10 Google reviews mention waiting for a callback (source says, Google reviews); she may be the one answering after hours (inference, from a review naming her).
Opening line: "I saw your form promises a reply in 2 business days, and a few reviews mention waiting on callbacks."
Question: "When a call comes in after 5, who picks it up today?"

Fake company, fake person. It only shows the shape of the output.

## Cost

In Claude Code, a full run starts 3 to 5 research agents plus one review agent, so it uses a noticeable share of your usage. Fast mode (for a contact within 2 hours) uses less.

Works best with web search on. It never contacts anyone or posts anything, and it sticks to work-related information.
