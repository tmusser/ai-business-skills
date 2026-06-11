# Gmail Buried Obligation Example

## Situation

An email chain looks like a casual request for thoughts, but it actually needs a decision by Friday.

## Messy Input

```text
Email chain:
- Subject: "Thoughts on the partner proposal?"
- "Could you share any thoughts when you have a second?"
- "We may need a firm answer by Friday if we want to keep the slot."
- "The partner is asking whether we are in or out."
- "If helpful, I can send the draft response."
```

## What The Skill Notices

- This is a buried obligation, not a casual thoughts request.
- The implied ask is a decision by Friday.
- The timing matters more than the soft language in the subject line.
- A response draft should acknowledge the real deadline.

## Clean Output

- Clean ask: decide whether we are in or out on the partner proposal by Friday.
- Audience: the partner contact and the internal owner.
- Owner: missing from the chain and should be named before replying.
- Deadline / timing: Friday.
- Decision needed: commit to the slot or decline.
- Missing info: who owns the final call and whether the draft response should be warm or direct.
- Potential misread: this reads like a low-priority thoughts request, but it is actually a deadline-driven decision.
- Why this ask is clearer: it exposes the real obligation hidden inside polite language.
- Suggested message: "Thanks for sharing this. I want to make sure I understand the timing correctly: are we aiming for a yes/no decision by Friday to keep the slot open? If so, who should own the final call on our side?"

## Why This Is Better Than A Generic AI Reply

- It separates the stated ask from the implied ask.
- It makes the deadline visible.
- It gives you a reply that protects the timeline instead of softening it away.

## Source Gaps

- The internal owner is not named.
- The chain does not say whether the final response should be sent now or held until Friday.
