# ⛳ 3D Mini Golf Game

[![Built with Three.js](https://img.shields.io/badge/Built%20with-Three.js-000000?logo=three.js&logoColor=white)](https://threejs.org/)
![HTML5](https://img.shields.io/badge/HTML5-Ready-orange)
[![Auth & Scores - Supabase](https://img.shields.io/badge/Auth%20%26%20Scores-Supabase-3ECF8E?logo=supabase&logoColor=white)](https://supabase.com/)

A lightweight 3D mini golf game built with Three.js.  
Play in your browser, aim and shoot across multiple holes, and optionally save best scores with Supabase authentication.

**Live Game:** 👉 [**Play Online Now**](https://https://golf-game-psi.vercel.app/) <br>
**Deployed Link:** `https://golf-game-psi.vercel.app/`

## ✨ Highlights

- 🎮 Interactive 3D mini golf (Three.js)
- ⚙️ Custom, lightweight physics: friction, collisions, slopes
- 🎯 Aim + power control (drag to aim, hold `SPACE` to charge)
- 🏞️ Three holes with increasing difficulty (Par 3 → Par 5)
- 🔐 Optional Supabase auth (sign up / sign in) + leaderboard persistence
- 📱 Mobile-friendly (touch drag) and deployable as a PWA if desired

## 🕹️ Controls

**Desktop**

- Click + Drag → Aim & power (release to shoot)
- Hold `SPACE` while aiming → Charge power (use power meter)
- Arrow keys → Camera rotate/angle
- `+` / `-` → Zoom in/out

**Mobile**

- Tap + Drag → Aim & shoot (touch listeners included)
- Pinch/Swipe → Camera gestures supported (consider adding on-screen buttons for polish)
- Best played in landscape mode

## 🚀 How to Play

1. Open the live game: [⛳ Start Playing](https://golf-game-psi.vercel.app/)
2. Sign in, create an account, or play as guest.
3. Aim with drag, release to shoot. Complete holes with the fewest strokes.
4. If signed in, your best scores are saved to the leaderboard.

## 🛠️ Tech Stack

- Three.js (r128) — WebGL 3D rendering
- Vanilla JS + HTML/CSS — Game logic & UI
- Supabase — Auth and score persistence (runs in demo mode without backend if not configured)
- Vercel — Hosting/deployment

## 📷 Media & Demo

| Screenshot 1                                                            | Screenshot 2                                                         |
| ----------------------------------------------------------------------- | -------------------------------------------------------------------- |
| <img src="/media/imgs/create_acc.jpg" alt="Screenshot 1" width="100%"/> | <img src="/media/imgs/level_2.jpg" alt="Screenshot 2" width="100%"/> |

<video src="/media/vids/Game.mp4" controls width="100%" title="Gameplay Demo"></video>

Full video link: [Demo Video On Youtube](https://youtu.be/AXhdfif_a0s)

_For more screenshots and assets, check the [`/media`](./media) folder._

## 🎯 Game Features

### Hole Designs

- **Hole 1**: Simple straight shot (Par 3)
- **Hole 2**: Obstacles to navigate around (Par 4)
- **Hole 3**: Complex course with ramps (Par 5)

### Visual Elements

- 🟩Colorful raised platforms with borders
- 🕳️ Deep, realistic holes with sinking animation
- 🚩 Blinking flag markers for easy hole identification
- 💡 Professional course lighting and shadows
- 🌳 Decorative trees and landscaping

---

## 🧭 Installation (Local)

Clone the repo :

```
git clone https://github.com/Bhavya-Chawat/golf_game.git
cd minigolf-game
```

Open the game (no server required) :

- macOS:

```
open index.html
```

- Windows:

```
start index.html
```

<h4>Or just drag index.html into any modern browser and enjoy<h4>

## 🔐 Supabase (Auth & Leaderboard)

- Email/password authentication
- Saves personal best scores to a player_scores table
- Leaderboard shows top players
- If Supabase is not configured, the game falls back to demo mode with a sample leaderboard

## 📱 Mobile & PWA Notes

- Runs in mobile browsers with touch controls
- Works best in landscape orientation
- Can be enhanced into a PWA (installable on home screen, offline play) with a manifest.json and service worker

## 🤝 Contributing & Ideas

Want to extend the game? Here are some ideas:

- 🏌️ More holes & obstacles
- 🔊 Sound effects & background music
- 🎛️ On-screen mobile camera controls
- 👥 Multiplayer or turn-based pass-and-play
- 🎨 More polished UI/UX and accessibility tweaks

PRs welcome — keep commits small & focused.

## 📝 License

MIT License — feel free to reuse and modify.

## ✅ Conclusion

This project delivers a browser-based 3D mini golf experience with optional Supabase authentication and a persistent leaderboard. Clone the repo, open index.html (or deploy to Vercel), and start putting; contributions and enhancements are encouraged.
