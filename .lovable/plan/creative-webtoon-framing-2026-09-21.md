# Creative webtoon framing

## Goal
Make every generated image use story-driven, varied webtoon framing instead of repetitive rectangular panels.

## Changes
- Expand the frame-layout system with asymmetric, offset, overlapping, border-breaking, close-up, and negative-space compositions inspired by the references.
- Give single-frame images their own varied cinematic framing, not only multi-frame pages.
- Select layouts deterministically from each scene so neighboring images vary while retries stay consistent.
- Strengthen prompt-writing rules so camera distance, crop, perspective, subject placement, and visual rhythm differ between consecutive timestamps.
- Keep the existing story accuracy, character continuity, English lettering, speed settings, and image provider unchanged.

## Verification
- Check generated prompt text for several one-, two-, three-, and four-frame plans.
- Confirm the app still loads and the render request receives the new composition instructions.
