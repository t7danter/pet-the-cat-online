# Pet the Cat Online

There are two kinds of browser games: the ones that want something from you, and the ones that simply let you sit down for a minute. This page is about the second kind. If you have ever wanted to pet the cat on a screen without installing an app, creating an account, or being told that you failed, the site behind this repository was built for exactly that moment.

The whole experience is one scene. A hand follows your pointer, a cat lies there breathing, and nothing else happens unless you make it happen. No timer runs in the corner. No score climbs. There is no streak to protect and no reason to feel guilty about closing the tab after thirty seconds. That restraint is the point, and it is rarer than it should be.

## What you actually do

You move. That is the entire interaction. Glide the pointer over the head, the back, or the belly, and the surface under your hand shifts softly while the rest of the body stays comparatively still. Move away and the impression fades. The response depends on where you touch, which direction you travel, and how fast you go, so a slow pass feels different from a quick flick even when both cross the same area.

Clicking is not the mechanic. You are not tapping a target to collect a reward, and there is no correct sequence hidden in the scene. People who try to stroke the cat by clicking rapidly tend to conclude the page is broken, when in fact they are simply using the wrong verb. Slow down, drag, and let the motion do the work instead of the pressure.

## The cats and the three poses

Eight cats are available, each with its own coat and face: an orange tabby, a British Shorthair, a calico, a Siamese, a silver tabby, a black cat, a Maine Coon, and a Ragdoll. Switching between them keeps the same controls, so there is nothing new to learn when you change your mind halfway through a visit.

Each cat comes in three resting poses. Side shows a curled animal seen from the side. Sprawl shows a stretched-out cat viewed from above. Belly shows a relaxed, belly-up position with a broad central area to explore. These are separate images rather than one model rotated on an axis, which means the body shape really does change, and so does the part of the animal within reach when you pet the cat in a new pose.

## Sound, breathing, and the option to turn everything off

Audio is off until you enable it, which is deliberate. Once sound is on, it follows your strokes rather than looping in the background: keep moving and you hear it, lift your hand and it stops. If silence is what you came for, leave it alone. Nothing nags you to turn it on, and no prompt appears if you pet the cat in complete quiet for ten minutes.

Breathing is a separate layer, a slow rise and fall around the torso that continues independently of your hand. It can be switched off entirely for a completely still image. Browsers that report a reduced-motion preference start with breathing disabled, and your choice is remembered locally so you do not have to set it again on the next visit.

## Phones, tablets, and small screens

The scene is landscape-first. On a phone, turning the device sideways gives the gestures more room and moves the controls to the left edge. Sliding inside the play area runs your finger over the cat rather than scrolling the page, which is the behaviour you want until you try to read the text below it; scroll outside the scene and the article moves normally. Fullscreen uses the native API where it exists and falls back to a page-filling layout where it does not.

## What it is not

It is not a three-dimensional model you can orbit. It is not a live camera feed of a real animal, and you cannot rotate the scene to reach the cat from an angle the artist never drew. The cats are generated photographic-style images with interactive motion layered on top, and the site says so plainly. Knowing that helps you calibrate: you are not going to find a hidden camera position, and you are not supposed to.

It is also not a game with a fail state. There are no points, no levels, no unlocks, and no daily obligation. The absence of those things is what makes a two-minute visit feel like a break instead of a task with a deadline attached.

## Why a page like this exists

Most of the web is engineered to keep you. Autoplay, badges, countdowns, and notification prompts all assume that attention is a resource to be harvested. A site that asks nothing back is a small corrective. You arrive, you pet the cat a few times, the body settles, and you leave. That is a complete session, and nobody sends you an email about it afterwards.

There is a practical side too. Short, low-stakes interactions are useful for testing a trackpad, checking whether a touchscreen registers gentle drags, or giving a child something harmless to do for a minute. A scene this simple makes those checks obvious rather than buried under menus and settings.

## Getting past the first ten seconds

The most common confusion is not technical. It is simply not knowing how to pet the cat: movement is the input, and clicking is not. The second most common is expecting sound immediately; browsers require a gesture before audio can start, so one click or tap is needed before the first stroke produces anything at all.

If the page reports that the scene needs WebGL, hardware acceleration is probably disabled or the browser is unusually old. If nothing responds, check that you are moving the pointer inside the play area rather than over the surrounding article. And if you switch cats and the picture seems to jump, that is expected: each combination is its own image rather than a continuous camera move.

## A short routine worth trying

Open the page, pick a cat, and choose the side view. Start at the shoulder and draw one long line toward the back, then lift your hand and watch the body settle before starting again. Turn breathing on and repeat the same stroke to feel the difference the extra motion makes. Then switch to the belly view, where the reachable area is much wider, and notice that the same gesture produces a different response simply because the surface underneath has changed.

None of this is required, and there is no wrong way to do it once the basic input is clear. It is just a way to see what the scene can do.

## Questions people ask before trying it

**Does anything happen if I stay long?** No. Duration is not tracked or displayed, and there is no hidden progress bar.

**Can I pet the cat with a trackpad?** Yes, and with a mouse, a stylus, or a finger. The scene reads pointer movement, so precision devices and touchscreens both work; the only requirement is that you pet the cat inside the play area.

**Does it work offline?** Not fully: assets load over the network on first visit, so an initial connection is needed even though the interaction stays light once cached.

**Is there a mobile app?** No. The browser version is the product, so there is nothing to install or update.

**Will it remember my settings?** Display preferences such as breathing and fullscreen behaviour are stored in the browser, so a return visit usually restores the look you left behind.

## Where to find it

The site is free, needs no registration, and runs in any modern browser with WebGL enabled. If you would like to pet the cat yourself, the official page is https://petthecatonline.com/ and it opens straight into the scene with no intermediate screens or sign-up forms.

That is the whole guide. Everything else is a matter of how long you feel like staying.
