# Pet the Cat Online

A minimal guide to **Pet the Cat** — a free browser-based cat-petting simulator with no download, no account, and no goals.

> Play it here: **https://petthecatonline.com/**

---

## What this is

Pet the Cat Online is a cozy interactive toy, not a game with a score. A hand follows your mouse or finger, and a photographic-style cat responds to how you move over it. You can stay for three strokes or for a long quiet break — nothing tracks your time.

- Built with WebGL, runs directly in the browser
- 8 cats × 3 poses = 24 combinations
- Free, no registration, no download

## Quick start

1. Open https://petthecatonline.com/
2. Move your pointer gently across the cat — that alone is the whole interaction
3. Click or touch the cat once to enable sound (sound starts muted by design)
4. Pick a different cat or pose from the menu above the scene whenever you feel like it

On a phone, turn the device sideways — the scene is landscape-first and the controls move to the left edge.

## How to play

### 1. Choose a companion

The **Cat** menu switches between the eight cats:

| Cat | Look |
| --- | --- |
| Marmalade | Orange tabby, sleepy expression (default) |
| Mochi | Blue British Shorthair, round cheeks |
| Patches | Calico |
| Coco | Siamese |
| Luna | Silver tabby |
| Onyx | Black cat |
| Maple | Maine Coon |
| Cloud | Ragdoll |

Switching cats keeps the same controls — there is no separate ruleset per breed.

### 2. Choose a pose

| Pose | Description |
| --- | --- |
| **Side** | Curled up, resting side view |
| **Sprawl** | Stretched out, viewed from above |
| **Belly** | Relaxed, belly-up |

Each pose is a separate image rather than a rotated camera, so the body shape and the areas you can reach actually change.

### 3. Pet with movement, not clicks

This is the core mechanic: **the cat responds to a moving hand.** Contact position, direction and speed all shape the reaction. The surface right under your hand shifts softly while distant areas stay steady, and the impression fades as you move away.

- Short, small circles around the head or cheeks
- Long slow passes from shoulder to back
- Slow down between strokes and watch the body settle before starting again

There is no hidden target to hit and no correct sequence. Deliberate motion beats frantic motion.

### 4. Play with the tail

Press or touch the tail, drag it gently, then release. It stretches only so far and springs back. If a gesture gets stuck mid-drag — rotating the phone or resizing the window does this — use **Start fresh** to restore the starting position.

### 5. Tune sound and breathing

- **Sound** — follows your strokes only. Enabling sound permits audio; it does not loop a soundtrack while you are idle. Lift your hand and playback stops.
- **Breathing** — a slow rise and fall around the torso, independent of your hand. Toggle it off for a completely still scene. If your system asks for reduced motion, breathing starts disabled.
- **Fullscreen** — native fullscreen where supported, page-filling fallback otherwise. Escape exits.

Your breathing preference is remembered in the browser (via local storage).

## Things worth knowing

- **Not a 3D model.** The cats are generated photographic images with interactive motion layered on top — no free camera rotation, no live feed.
- **No fail state.** No points, timers, streaks or rewards. Faster is not better.
- **Mobile gestures stay in the scene.** Sliding inside the play area pets the cat instead of scrolling the page; scroll outside the scene to read further.
- **Troubleshooting.** A "cozy spot needs WebGL" message means hardware acceleration is off or the browser is too old. No sound usually means sound was never enabled, no stroke was made after enabling, or the tab or device is muted.

## Repository purpose

This repo documents how Pet the Cat works so players can get past the "what am I supposed to do?" moment. It is a guide, not the game's source code.

Official site: **https://petthecatonline.com/**
