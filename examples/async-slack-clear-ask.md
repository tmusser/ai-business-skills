# Async Slack Clear Ask Example

## Situation

A Slack thread has a half-decision, two objections, no owner, and an implied deadline.

## Messy Input

```text
Slack thread:
- "We probably need to move the launch one day to handle the edge-case fix."
- "I don't think we should hold the whole launch for this."
- "If we don't decide today, ops will have to prep twice."
- "Who is actually making the call?"
- "Can someone draft the response for the channel?"
```

## What The Skill Notices

- Slack is acting like an async meeting.
- There is a real decision gap, not just a wording issue.
- The owner gap is the blocker.
- The implied deadline is today because ops would otherwise prep twice.

## Clean Output

- Clean ask: decide whether to move the launch one day or keep the current date.
- Audience: the launch channel and the ops team.
- Owner: missing and needs to be named.
- Deadline / timing: today, before ops does duplicate prep.
- Decision needed: yes, move the launch or no, keep it.
- Missing info: who owns the call and whether the edge-case fix is truly launch-blocking.
- Potential misread: this could sound like a scheduling question when it is really a decision question.
- Why this ask is clearer: it turns a noisy Slack thread into one decision, one owner gap, and one deadline.
- Suggested message: "We need a call today on whether the launch moves one day for the edge-case fix. Can someone name the owner for the decision and confirm whether the fix is launch-blocking? If we don't decide today, ops will prep twice."

## Why This Is Better Than A Generic AI Reply

- It treats Slack like a real meeting with decisions and ownership.
- It surfaces the implied deadline instead of hiding it.
- It gives a send-ready reply instead of a summary.

## Source Gaps

- The decision owner is not named.
- The true launch-blocking status of the fix is still unresolved.
