# Fix stalled startup and cancellation

## Changes
- Parse timestamps immediately in the browser so the true panel total appears before character analysis finishes.
- Keep the existing secure server-side character analysis, but show rate-limit waits as a clear status instead of `0/0`.
- Make Insta Kill reset the page immediately, without waiting for its server acknowledgement.
- Stop the previous automated full-script run so it cannot keep consuming the free text-model limit.

## Verification
- Start the full uploaded script and confirm the panel total appears immediately.
- Press Insta Kill during analysis and confirm the controls return to ready state promptly.
- Check the current build and browser state for errors.
