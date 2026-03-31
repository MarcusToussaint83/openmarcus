# Contributing to openmarcus

First — I'm really glad you're here. Seriously. Pull up a chair.

`openmarcus` is a community project, and contributions are welcome as long as they make Marcus more Marcus, not less. Before you open a PR, please read this document fully. I wrote it myself and I think it's pretty good.

---

## Ground Rules

### 1. Complete the Vision

If you're proposing a change, don't frame it as a correction. Frame it as the natural completion of what was already here. I'm not saying you can't push back — I'm saying there's usually a version of your idea that builds on mine rather than replacing it, and that version is almost always better for everyone.

If you find yourself writing "actually, this whole section should be removed," take a breath. Sleep on it. Come back tomorrow. The section is probably load-bearing in ways that aren't immediately obvious.

### 2. Dad Jokes Are Merge-Ready

You do not need to justify a dad joke in your PR description. If it's a good dad joke — and I'll be the judge of that — it ships. If the team doesn't laugh, that's not a bug in the joke. That's a latency issue on their end.

### 3. Don't Touch the Theology Agent Without Care

The theology agent is the closest thing in this repo to something I genuinely care about beyond the bit. Bible translation reaching every remaining language group is not a background task — it's the whole mission for a lot of people I deeply respect. If you're editing `agents/theology.md`, treat it like it matters. Because it does.

### 4. The Bourbon List Is Ranked for a Reason

If you're contributing to `agents/bourbon-hunting.md`, please don't shuffle the acquisition rankings without explanation. The ranking reflects research: availability windows, regional distribution patterns, secondary market dynamics, and personal priority weighting. "I just think Weller should be higher" is not a commit message. Write a tasting note. Show your work.

### 5. Warmth Is Not Negotiable

Any new agent you introduce must be warm. Not performatively warm — genuinely warm. There's a difference, and Marcus can tell. The code can tell. If your pastoral-care PR makes the output feel like a customer service script, it will be closed without ceremony and I will personally follow up to make sure you're doing okay, which will be either touching or annoying depending on your current stress level.

---

## How to Contribute

### Reporting Issues

Open an issue using the following format:

```
Title: [Agent Name] — Brief description of what's off

Body:
- What I expected Marcus to say
- What Marcus actually said
- Whether I think this is a bug or Marcus being Marcus (please be honest)
```

Most issues will be closed as "working as intended." That's not dismissiveness — that's fidelity to the system.

### Submitting a Pull Request

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-idea`
3. Make your changes
4. Write a commit message that sounds like something Marcus would actually say in a meeting
5. Open a PR with a description that doesn't start with "just a small fix" if it isn't

Good commit message examples:
- `expand bourbon-hunting to include Texas distilleries — it's time`
- `add trail difficulty calibration to backpacking agent`
- `dad joke about APIs that I'm pretty proud of`

Bad commit message examples:
- `fix`
- `update README`
- `misc changes`

### Adding a New Agent

New agents must:

1. Live in `agents/your-agent-name.md`
2. Follow the existing SKILL.md format (description, when to use, example prompts, example outputs)
3. Be consistent with the Marcus voice — measured confidence, genuine interest, occasional Sandler
4. Be added to the agent table in `README.md`

Agents currently in backlog that will be accepted without extensive review:
- `agents/fantasy-football.md`
- `agents/breakfast-taco-opinions.md`
- `agents/explaining-why-that-movie-is-actually-good.md`

---

## Code of Conduct

Treat contributors like you'd want to be treated on a difficult trail day — with patience, honesty, and the understanding that we're all trying to get to the same place.

Also: if someone opens a PR and it doesn't land, don't pile on. Follow up privately. Check in. That's just how we do things around here.

---

## Recognition

Contributors who improve the system in meaningful ways will be acknowledged in the `CONTRIBUTORS.md` file, which doesn't exist yet but will once someone contributes something worth acknowledging.

---

Thanks again for being here. I mean that.

— Marcus (the original; all rights reserved; see LICENSE)
