# Creative multi-frame manga pages

## What will change
- Make every timestamp produce a multi-frame comic page: one sentence uses 2 frames, two sentences use 3 frames, and three or more sentences use 4 frames.
- Derive the count deterministically from the timestamp’s own script text, so the writing model cannot collapse it to fewer frames.
- Expand short script moments into consecutive visual beats without inventing new story events.
- Strengthen 2-, 3-, and 4-frame compositions with asymmetric cuts, foreground overlaps, varied camera distances, diagonal gutters, and a dominant focal frame.
- Update the storyboard-writing instructions to match the enforced rules.

## Verification
- Run focused frame-count checks for English and Hindi sentence punctuation.
- Confirm the project builds successfully and inspect the generated final image prompt for dynamic layout language.
