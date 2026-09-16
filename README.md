# Ordinary Signals

A small browser experiment. Thirty visual choices, one locked advertising prediction, no microphone access.

The public version is a single file in `out/index.html`. It runs locally in the browser and deploys through GitHub Pages.

## Model

- A small starting prior uses age, region and work.
- Gender and religion have zero direct weight.
- The first 16 reels cover all eight categories twice.
- Later reels maximize expected information gain and contrast between the leading hypotheses.
- A three-state response-bias variable prevents someone who says yes to everything from appearing interested in everything.
- The ranking is SHA-256 hashed before the advertisements appear.

The displayed scores are normalized model estimates, not calibrated purchase probabilities. Human accuracy has not been established.
