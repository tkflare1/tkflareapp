# Prework – tkflareapp

Submitted by: **Keith Tawe Vhurumuku**

This is a super‑simple iOS app that demonstrates the basics of Interface Builder and Swift actions.  
When the user taps the button, the app picks a random background color for the entire screen and updates a status label with the new hex value.

Time spent: **2.5 hours** total

## Required Features

The following **required** functionality is completed:

- [x] User sees a screen containing **three labels** and **one button**
- [x] Tapping the button changes the **background color** of the screen to a random color

## Video Walk‑through

> 📽️ [Watch the demo on Loom](https://www.loom.com/share/a66435a0b31e43e3a2a165e2feec5e1b?sid=478b6c52-79a5-4eac-afc4-36874754c209) – under 30 seconds.

## App Brainstorming

### Favorite apps & killer features

| App | Feature #1 | Feature #2 |
|-----|------------|------------|
| Instagram | Seamless stories swipe‑through | Powerful in‑app photo editor |
| Duolingo | Bite‑sized daily goals | Streak + XP gamification |
| Notion | Drag‑to‑reorder blocks | Real‑time collaboration |
| Spotify | Discover Weekly playlist | Lyrics synced to playback |

### My app idea – *FlashFuel*

**FlashFuel** is a mobile study companion that mixes spaced‑repetition flashcards with quick “brain‑fuel” breaks (30‑second wellness tips or breathing exercises).  
Key features I’d like to prototype:

1. **Adaptive deck scheduler** – cards reappear based on individual accuracy and response time.  
2. **Micro‑break overlay** – after every 10 cards, the app suggests a guided stretch or hydration reminder.  
3. **Camera‑scan card creation** – point the phone at textbook diagrams; OCR+Vision auto‑generates a flashcard pair (front = image, back = user annotation).  

I’m interested in blending productivity with healthy study habits, and this project would let me practice Core Data, VisionKit, and local notifications in iOS.

## Notes

* Biggest challenge: wiring the `IBAction`—Xcode initially dropped it **outside** the class, causing a build error. Re‑dragging the connection inside the class scope fixed it.

## License
Copyright 2025 Keith Tawe Vhurumuku

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
