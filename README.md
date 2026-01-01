# 🌷 The Ultimate Birthday Journey: Vault & Virtual Room

A multi-layered digital gift designed to celebrate a special birthday through a week-long countdown and an interactive final surprise.

## 📁 Phase 1: The Memory Vault (`birthday.html`)
The entry point of the gift. A "Berry/Pink" themed interactive grid that locks memories behind specific dates.

- **Time-Locked Content:** Logic ensures Jan 1st–7th memories only unlock on their respective days.
- **Un-skippable Memories:** The "Close" button only appears once the daily video (`day1.mp4` to `day7.mp4`) has finished playing.
- **Automatic Transitions:** Displays a "Welcome Back" message that tracks her progress through the week.

## 🏠 Phase 2: The Virtual Room (`index.html`)
The "Grand Finale" unlocked on January 8th. An immersive experience where she explores a decorated room.

- **Interactive Elements:**
  - **Panda & Stickers:** Clicking the panda or stickers triggers audio cues and visual reactions.
  - **Photo Gallery:** Hidden "Polaroids" (`pic1.jpeg`, `pic2.jpeg`, `pic3.jpeg`) scattered around the room.
  - **Immersive Sound:** Includes `door_creak`, `footsteps`, and a special `fav` background track.

## 🛠️ Technical Stack
- **Languages:** HTML5, CSS3 (Berry/Pink palette), and JavaScript.
- **Hosting:** GitHub Pages.
- **Logic:** Real-world date tracking via the `Date()` object.

---
*Created with effort, heart, and a little bit of code.*
