# Decision With Data Example

## Situation

You need to decide whether to extend a pricing experiment or end it now.

## Messy Input

```text
Thread notes:
- The launch ticket says the experiment ran long enough for a signal, but not long enough for full confidence.
- Slack says product wants to keep it open one more week.
- Hex export shows the lift is positive but the sample is still noisy.
- Finance asked whether we need a clearer stop rule.
- Nobody has written down the reversal cost if we change course.
```

## What The Skill Notices

- The decision is about confidence and timing, not just the chart.
- The evidence points in one direction, but it is not yet clean.
- The stop rule is missing.
- Reversal cost is not captured, so the risk is incomplete.

## Clean Output

- Decision snapshot: the experiment is pointing positive, but the confidence is still noisy.
- Recommendation: extend one more week if the team wants higher confidence, but write down the stop rule first.
- Options: stop now or extend for one week.
- Trade-offs: stopping now is faster; extending gives cleaner evidence.
- Evidence: Hex shows positive lift; the ticket says the signal is promising but noisy.
- Risks: no written stop rule and no reversal-cost estimate.
- Next step: agree on the stop rule and the reversal cost before changing course.

## Why This Is Better Than A Generic AI Reply

- It distinguishes evidence from decision readiness.
- It makes the missing stop rule visible.
- It avoids turning the output into a polished memo when a quick decision snapshot is enough.

## Source Gaps

- The reversal cost is not specified.
- The exact stop rule is not captured in the context.
