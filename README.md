# 🎯 DOUG HUNT

> *An exhaustively researched simulation of the apex predator-prey relationship between you and Doug.*

[![Status](https://img.shields.io/badge/status-OPERATIONAL-brightgreen?style=for-the-badge)]()
[![Doug](https://img.shields.io/badge/doug-AT_LARGE-red?style=for-the-badge)]()
[![Threat Level](https://img.shields.io/badge/threat_level-FLANNEL-orange?style=for-the-badge)]()
[![Made With](https://img.shields.io/badge/made_with-SPITE-purple?style=for-the-badge)]()
[![FLOCO](https://img.shields.io/badge/FLOCO-ENTERTAINMENT-yellow?style=for-the-badge)]()

---

## 📜 PREAMBLE

In the year of our Lord 1984, Nintendo released a game called *Duck Hunt*. It was about ducks. You shot at the ducks. A dog laughed at you. A simpler time.

It is now no longer 1984. The ducks have evolved. They have donned **red checkered flannel**. They have grown **gray crew cuts**. They have memorized **all sixteen Leadership Principles**. They have, against all biological precedent, become **Doug**.

Doug will dive deep on you. Doug has a bias for action. Doug, against your express wishes, is going to disagree and commit.

This repository contains the only known countermeasure.

---

## 🎮 WHAT IS THIS

**DOUG HUNT** is a single-file, fully self-contained, browser-native, mobile-responsive, scanline-saturated, chiptune-scored, pixel-art arcade simulation in which you are tasked with shooting Doug out of the sky.

Doug is a 5'10" man in his mid-40s with a flat-top haircut and an unshakable sense of confidence. He flies through the air. He wears a flannel shirt. He talks smack. He is not your friend.

> *"I made this for my friend Doug."* — the developer, allegedly

---

## ✨ FEATURES

### 🦆 Doug, The Sprite
Hand-crafted from individual pixels using the ancient art of `ctx.fillRect()`. Each Doug is approximately 22 pixels of pure menace, including:

- **Gray flat-top crew cut** with bristly highlight pixels
- **Salt-and-pepper eyebrows** angled at exactly 22.5° of pure disdain
- **Genuine red checkered flannel shirt** (algorithmically woven, see `drawFlannel()`)
- **Tiny white shirt buttons** running down center for that authentic lumberjack-on-vacation aesthetic
- **A frown that goes all the way down to his soul**
- **Full 3-frame wing-arm flapping animation** because Doug, in this universe, has decided to fly

### 💬 Doug Says Things
Doug is equipped with **28 unique trash-talk lines** delivered via authentic 8-bit speech bubbles, all sourced from the corporate liturgy of his and the developer's shared former employer. Categories include:

- **Mid-flight LP evangelism** ("DELIVER RESULTS!", "WHERE'S THE OWNERSHIP?", "DISAGREE & COMMIT", "I'M RIGHT, A LOT")
- **Post-miss performance review** ("NEEDS A PIP", "MISSING THE BAR", "TIER 3 PERFORMER", "ESCALATE TO YOUR SKIP")
- **Triumphant escape** ("PEACE — I'M VESTED", "RTO YOURSELF", "I'LL BE IN MY 1:1", "BACK TO THE DOC MINES")

Speech bubbles follow Doug as he flies and clamp to canvas edges so his insults are always legible. We will not be silencing him. He has too many learnings to share.

### 🐕 The Dog
A separate, non-Doug entity. Sniffs through the grass. Leaps up to flush Doug from cover. Pops up holding a **tiny defeated Doug head with X eyes** when you score a hit. Laughs at you when you don't. The dog is on your side. Probably.

### 🎵 Synthesized Chiptune Soundtrack
Zero audio files. Every sound generated in real-time via the Web Audio API:

- Shotgun blasts (filtered white noise + sawtooth growl)
- Doug's double-quack-but-it's-a-man-noise on spawn
- Whistle-of-doom on every successful hit
- The dog's iconic 6-note staccato laugh
- Round-start fanfare, round-clear jingle, sad-trombone game over
- Bonus: a satisfying *click* on dry-fire so you know you've failed audibly

### 🎯 Reload Crates
Floating gold ammo crates drift across the screen during play. Shoot them — even with zero shots remaining — to refill your magazine. Spawns at a 25% chance from Round 2 onward, never two rounds in a row, blinks red the last 1.5 seconds before despawning. The fairest powerup in gaming.

### 📺 Faithful CRT Aesthetic
- Rolling scanlines at 60Hz
- Subtle phosphor flicker
- Heavy corner vignette
- Pixel-perfect rendering (no anti-aliasing crimes)
- Thick chunky bezel suggesting your TV is sitting on a milk crate

### 📱 Real Mobile Support
Not "we slapped a viewport tag on it" support. **Real** support:

- Full-screen vertical canvas on phones (no letterboxing)
- Sprites scale up so Doug isn't a microscopic dot
- Touch events handled natively, no fake mouse simulation
- iOS Web Audio unlock buffer (the silent buffer trick that took 8 years for the rest of the industry to figure out)
- Apple PWA meta tags so Doug can add this to his home screen and play it without seeing the Safari URL bar judging him
- Safe-area inset padding for notch users

---

## 🕹️ HOW TO PLAY

### The Rules
1. There are **3 rounds**.
2. Each round, **5 Dougs** will appear, one at a time.
3. You must hit **at least 3 of 5** to advance.
4. You get **3 shots per Doug**.
5. Miss with all 3? Doug escapes, mocking you on his way out. Round continues.
6. Clear all 3 rounds and you have **GOT DOUG**. Doug will be sad. FLOCO will be proud.
7. Fail any round and Doug **escapes to mock you another day**. The cycle continues. The Dougs are eternal.

### The Controls
| Action | Desktop | Mobile |
|--------|---------|--------|
| Aim | Move mouse | Drag finger |
| Shoot | Click | Tap |
| Reload | Shoot the gold crate | Tap the gold crate |
| Mute the chaos | Press `M` or click the speaker | Tap the speaker icon |

That's it. There are no other buttons. We did not need them.

---

## 🚀 INSTALLATION

```bash
# Step 1
git clone https://github.com/YOUR_USERNAME/doug-hunt.git

# Step 2
# Open duckhunt.html in any web browser

# Step 3
# Hunt Doug
```

Alternatively, you can download `duckhunt.html` and double-click it. We are not running a server. We are not running a build pipeline. We are not running `npm install` and waiting 14 minutes while it downloads the entirety of the JavaScript ecosystem to render a game about shooting your friend. **There is one file.** It is HTML. It works.

### Hosting on GitHub Pages
1. Rename `duckhunt.html` to `index.html` (or don't, but then you'll need to type `/duckhunt.html` in the URL like a chump).
2. Push to GitHub.
3. Settings → Pages → Source: `main` branch → Save.
4. Wait approximately 90 seconds.
5. Send Doug the link.
6. Wait for him to call you.

---

## 🛠️ TECHNICAL SPECIFICATIONS

| Spec | Value |
|------|-------|
| **Language** | HTML5, CSS3, vanilla JavaScript |
| **Frameworks** | None. We don't need them. We don't want them. We will not be installing them. |
| **Build step** | None. None. Did I mention none? |
| **Dependencies** | Two Google Fonts. That's it. |
| **File count** | One (1) |
| **Bundle size** | Approximately 75 KB. Smaller than the average React project's `node_modules` lockfile entry for a single dependency. |
| **Doug count** | 15 per playthrough |
| **Trash talk lines** | 28 unique LP-coded insults, peer-reviewed |
| **Frames per second** | 60, locked, on basically anything from the last decade |
| **Browser support** | Anything that supports `<canvas>` and Web Audio. So, all of them. |

---

## 🎨 ART DIRECTION

The visual language of *Doug Hunt* draws on four primary influences:

1. **The original 1984 NES Duck Hunt** for layout, dog behavior, gradient skies, and the fundamental concept of being mocked by a small dog.
2. **A Bass Pro Shops circular from 2003**, for Doug's wardrobe.
3. **Pure spite**, for everything else.
4. **A particularly aggressive 6-page narrative document Doug once wrote**, for the trash talk.

All sprites are drawn at base resolution and uniformly scaled at runtime. No PNGs. No SVGs. No image assets of any kind. Every pixel is computed. We are operating with extreme **frugality**.

---

## 🐛 KNOWN ISSUES

- Doug is hard to hit. This is not a bug. Doug is supposed to be hard to hit. Doug spent six months training for this. Get good.
- The dog will laugh at you. This is also not a bug. The dog has earned the right to laugh.
- Audio may not play on first load on iOS until the user taps the screen. This is Apple's fault, not ours, and we have done everything humanly possible to mitigate it.
- If you turn your phone sideways mid-game, the canvas resizes and Doug may briefly teleport. Don't turn your phone sideways. Why are you turning your phone sideways. Stop that.

---

## 🤝 CONTRIBUTING

We welcome pull requests, particularly those that:
- Add more LP-coded trash-talk lines (especially deep cuts: "TWO-PIZZA TEAM," "ANDON CORD," "NARRATIVE NOT NUMBERED")
- Implement Round 4: Doug Strikes Back
- Add a "shotgun" sprite that Doug can hold *back*
- Replace the dog with a different small hunting breed
- Add a Connections-style meta-game where Doug grades your performance against the LP rubric

We do not welcome pull requests that:
- Add a build system
- Migrate any part of this to TypeScript
- Suggest "rewriting it in React"
- Add a 6-page narrative explaining why we should rewrite it in React
- Defend Doug

---

## ⚖️ LEGAL

Doug has not consented to being depicted in this software. Doug does not know this software exists. Doug will find out approximately 4 minutes after you send him the link. The legal department of FLOCO Entertainment (which is also you) is prepared for this eventuality.

This software is provided "AS IS", "AS DOUG", and "AS IS DOUG" with no warranty of any kind. If Doug retaliates, you're on your own.

---

## 📜 LICENSE

**MIT License** — Use it, fork it, modify it, slap your friend's face on it. Just don't try to sue me when Doug sees this and stops returning your texts.

---

## 🙏 ACKNOWLEDGMENTS

- **Nintendo**, for inventing the genre in 1984 and not noticing this exists.
- **Doug**, for being so visually distinctive that he was effectively asking for it.
- **The dog**, for unwavering professional service.
- **Web Audio API**, for letting us synthesize a duck's quack out of pure mathematics.
- **A certain large e-commerce company in Seattle**, for providing the script.
- **Coffee**.

---

```
                    ┌─────────────────────────────┐
                    │                             │
                    │   © 1984 FLOCO ENT.         │
                    │   DOUG MUST PAY             │
                    │                             │
                    └─────────────────────────────┘
                            ▲
                            │
                       PRESS START
```

---

*Built with love, ammunition, and one specific friend in mind.*
