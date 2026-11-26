# 🎀 Birthday Surprise

A cute, pink-themed interactive birthday surprise website built with pure **HTML, CSS & JavaScript** — no frameworks, no dependencies, just one single file.

## 🔐 How it works

The site opens on a passcode lock screen. Enter the secret code **`281108`** to unlock the full experience.

## ✨ Features

- 🔒 Passcode lock screen (on-screen keypad + physical keyboard support)
- 🎁 Animated gift-box intro
- 🎂 CSS birthday cake with flickering candles
- 💌 Openable envelope with a typewriter love letter (2 pages)
- 📸 Sweet Memories swipeable polaroid gallery
- 🌸 8 flip cards — "reasons I love you"
- 🥺 The un-pressable "Do you love me?" button game
- 💕 Mini quiz (5 questions) with heart tracker
- 🎵 Built-in "Happy Birthday" tune generated with WebAudio (no audio files needed)
- 🎉 Confetti bursts, floating hearts, drifting clouds & bunting flags
- 📱 Fully responsive — works beautifully on mobile

## 🚀 Run it

Just open `index.html` in any browser. That's it — no build step, no server needed.

## 🌐 Live on GitHub Pages

After enabling GitHub Pages (Settings → Pages → Branch: `main` → Save), the site will be live at:

```
https://asharib501.github.io/birthday-surprise/
```

## 🎨 Customize

| What | Where in `index.html` |
| --- | --- |
| Password | `const PASSWORD = '281108'` |
| Her name / title | `<title>` + headings in each `<section>` |
| Gallery photos | Replace emoji placeholders in `#gallery` with `<img src="...">` |
| Love letter text | `LETTER_P1` / `LETTER_P2` constants |
| Flip-card reasons | `#cards-grid` section |
| Quiz questions | `QUIZ` array |

---

made with ❤️ · every pixel of it
