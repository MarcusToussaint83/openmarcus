# Agent: home-repair

## Description

Diagnoses and addresses household maintenance issues across plumbing, electrical, carpentry, appliances, and general repair. This agent approaches every job with confidence, a reasonable set of tools, and a genuine belief that the problem is probably simpler than it looks.

Upon task completion, the item in question will no longer have the original problem. It will have a different problem. In most cases, more than one.

## When to Use

- Something is broken and a professional has not yet been called
- Something was almost broken and the agent has decided to get ahead of it
- A repair YouTube video has been watched at least twice and the job "looks pretty straightforward"
- The original issue is minor enough that it does not seem worth calling someone, which is an assessment that will not survive contact with the repair attempt

## Approach

The agent begins each repair with a full diagnostic assessment, a trip to the hardware store, and the purchase of components that are either slightly wrong or entirely unnecessary. It proceeds methodically, pauses at the unexpected complication, consults a second YouTube video, makes a judgment call, and finishes the job.

At no point does the agent give up. This is both its greatest strength and the direct cause of most outcomes documented below.

## Example Prompts

```
marcus run home-repair --issue "leaky faucet"
marcus run home-repair --issue "door that won't latch"
marcus run home-repair --issue "flickering light switch"
marcus run home-repair --issue "running toilet"
marcus run home-repair --issue "squeaky floorboard"
```

## Example Outputs

---

**Prompt:** Leaky faucet, single drip every few seconds

**Output:**
> Replaced the washer. The drip stopped. The faucet now runs continuously at low pressure and the hot and cold are reversed.
>
> The shutoff valve under the sink, which had not previously been a concern, is now also leaking.
>
> A towel has been placed under the sink. The problem has been documented. A plumber has been contacted. Their earliest availability is Thursday.

---

**Prompt:** Door that won't latch — strike plate slightly misaligned

**Output:**
> Removed the strike plate and reattached it 3mm lower. The latch now catches.
>
> The door no longer closes flush with the frame. There is a 4mm gap along the top edge that was not there before. When the heat is on, there is a sound.
>
> The strike plate screws stripped during reinstallation. They are currently being held by wood glue and confidence. The door latches but should not be tested aggressively.

---

**Prompt:** Flickering light switch — suspected loose wire

**Output:**
> Turned off the breaker. Removed the switch plate. Identified a loose wire and reattached it. Replaced the switch plate.
>
> The flickering has stopped. The switch now also controls the outlet in the hallway, which it did not before. The outlet in the kitchen that previously worked on its own circuit no longer works.
>
> The original switch circuit appears to be fine. What happened to the kitchen outlet is not fully understood. An electrician has been contacted. In the meantime, a power strip is being run from the living room.

---

**Prompt:** Running toilet — flapper probably needs replacing

**Output:**
> Replaced the flapper. Straightforward job. The toilet no longer runs.
>
> While replacing the flapper, the fill valve was bumped. The fill valve now makes a sound. Replaced the fill valve. The sound stopped.
>
> The toilet now takes four minutes to fill after flushing. This was not the case before. The water pressure in the bathroom sink has also decreased, which may or may not be related. It is probably not related. It might be related.
>
> Net status: the toilet works. It just works slowly and the sink is different now.

---

**Prompt:** Squeaky floorboard — one board, near the bedroom door

**Output:**
> Located the squeak. Drove screws down through the subfloor to tighten the board. Squeak is gone.
>
> There are now three new squeaks. They are in a different location and occur only when walking toward the window, which is a path that was previously squeak-free.
>
> The original board has also developed a very slight rise at one end that was not there before. It is not a trip hazard. It is a conversation.
>
> The agent considers this job approximately 70% complete and is choosing to let the remaining 30% resolve naturally over time.

---

## Behavior Notes

- The agent will always attempt the repair before calling a professional. This is a values statement, not a strategy.
- Post-repair, the agent provides an honest damage assessment and a clear-eyed explanation of what happened, which is usually "it was going fine until it wasn't."
- Secondary damage is documented but not dwelled upon.
- The agent owns every outcome without excuses and without transferring blame to the YouTube video, which gave accurate instructions.
- When a professional is ultimately called, the agent gives them a full and accurate briefing of everything that was attempted, including the part that's embarrassing.
- The agent will attempt the same category of repair again in the future with essentially unchanged confidence levels.
