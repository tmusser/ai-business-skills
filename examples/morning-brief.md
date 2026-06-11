# Morning Brief Example

## Situation

You are about to join a product review and need a fast catch-up on what changed overnight.

## Messy Input

```text
Slack since yesterday afternoon:
- Reliability channel says checkout error rate spiked after the payment rollout.
- PM says "we may need to pause the rollout if the error rate holds."
- Eng says one fix is in review, another is still unassigned.
- Calendar shows the review starts in 20 minutes.
- Meeting notes from yesterday mention an open question about whether support should be briefed.
```

## What The Skill Notices

- This is a conversation-state problem, not just a summary problem.
- The real change is a possible rollout risk, not the chatter around it.
- There is an owner gap on the second fix.
- The review needs a response before it starts.
- Support briefing may be a hidden follow-up, not the main ask.

## Clean Output

- Conversation state: checkout rollout risk is active before the review.
- What changed: error rate spiked after the payment rollout and one fix is still unassigned.
- What needs response: confirm whether to pause the rollout or keep going with the current plan.
- Action state: assign an owner for the second fix and confirm whether support needs a briefing.
- Source confidence: high on the spike and open ownership gap, medium on the pause recommendation.
- Suggested next response: "We have a live checkout risk and one unassigned fix. I can brief the review with the current status, but we should confirm an owner and whether support needs to be looped in before we meet."

## Why This Is Better Than A Generic AI Reply

- It separates the signal from the meeting noise.
- It shows the owner gap instead of hiding it in a summary.
- It gives you a response you can use before the meeting starts.

## Source Gaps

- The specific rollback threshold is not in the pasted context.
- It is unclear whether support has already been briefed.
