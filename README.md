# ⛳ 3D Mini Golf Game

[![Built with Three.js](https://img.shields.io/badge/Built%20with-Three.js-000000?logo=three.js&logoColor=white)](https://threejs.org/)
[![Auth & Scores - Supabase](https://img.shields.io/badge/Auth%20%26%20Scores-Supabase-3ECF8E?logo=supabase&logoColor=white)](https://supabase.com/)
[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?logo=vercel)](https://vercel.com/)

A lightweight 3D mini golf game built with Three.js.  
Play in your browser, aim and shoot across multiple holes, and optionally save best scores with Supabase authentication.

**Live demo:** [https://YOUR-VERCEL-LINK.vercel.app](https://YOUR-VERCEL-LINK.vercel.app)

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

1. Open the live demo: `https://YOUR-VERCEL-LINK.vercel.app`
2. Sign in, create an account, or play as guest.
3. Aim with drag, release to shoot. Complete holes with the fewest strokes.
4. If signed in, your best scores are saved to the leaderboard.

## 🛠️ Tech Stack

- Three.js (r128) — WebGL 3D rendering
- Vanilla JS + HTML/CSS — Game logic & UI
- Supabase — Auth and score persistence (runs in demo mode without backend if not configured)
- Vercel — Hosting/deployment

## 📷 Media & Demo

![Gameplay Screenshot](/media/screenshot1.png)

🎥 Demo video: [https://youtube.com/YOUR-DEMO-LINK](https://youtube.com/YOUR-DEMO-LINK)

## 🧭 Installation (Local)

clone the repo
git clone https://github.com/YOUR_USERNAME/minigolf-game.git
cd minigolf-game

open the game (no server required)
macOS:
open index.html

Windows:
start index.html

or just drag index.html into any modern browser
text

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
