# Reaction Drift

I have coded a browser-based cognitive modeling game that explores human reaction time and adaptation using the help of AI. I used a drift-diffusion model (DDM).

## How It Works
Players will respond to visual stimuli (an onscreen colored circle) by pressing left or right keys as quickly as possible according to the color. Occasionally, the stimulus-response rule reverses without warning, which induces adaptation.

## Cognitive Model
The game implements a drift-diffusion model that accumulates noisy evidence until a decision threshold is reached, generating predicted choices and reaction times.

## Data Collected
- Reaction time per trial
- Accuracy
- Rule-change adaptation effects
- Model vs human divergence

## Tech Stack
- HTML / CSS / JavaScript
- Canvas or DOM rendering
- Lightweight data visualization
