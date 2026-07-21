# Polo Playbook — Water Polo Board & Coach

A single-page, mobile-friendly web app for youth water polo coaches and players. It's one self-contained file (`index.html`) — no install, no server, no account required. Everything you save stays on your device.

## Running it

Just open `index.html` in a browser (double-click it, or "Add to Home Screen" on a phone for an app-like experience). There's nothing to build or install.

## The three tabs

### 🎯 Board

A draggable court whiteboard for drawing up plays.

- **✋ Move** — drag players (white circles = offense, dark circles = defense, red = goalie) and the ball around the court.
- **✏️ Draw** — freehand sketch on the water.
- **➡️ Arrow** — draw an arrow from where you press to where you release (great for showing passes, drives, and swim routes).
- **Color dots** — pick the ink color for Draw/Arrow.
- **↩️ Undo** — remove the last ink stroke.
- **🗑 Clear ink** — remove all strokes but keep player positions.
- **🔄 Reset** — put everyone back in the default Diamond Set formation and clear ink.
- **▣ Full court / ◧ Half court** — switch between the whole pool (both goals) and just your attacking end, zoomed in.
- **💾 Save play** — name and save the current board to My Saved Plays.
- **📖 Open playbook** — jump to the Playbook tab.

Your board auto-saves as you go, so closing the app or refreshing never loses your work.

### 📖 Playbook

- **My saved plays** — everything you've saved from the Board tab. Tap **Load** to bring one back onto the board, or **✕** to delete it.
- **Starter set plays** — four built-in plays to learn from or build on: Diamond Set, Power Play (4-on-3), Wing Drive, and Counterattack Lanes. Load any of them to see the setup and arrows, then tweak it.
- **Backup** — **⬇️ Save backup file** downloads all your plays (and your current board) as a `.json` file; **⬆️ Restore backup** loads one back in. Use this before switching phones/browsers, since plays are stored locally and don't sync on their own.

### 🧢 Coach

A quick-answer chat for water polo questions — positions, the diamond/umbrella offense, 6-on-5 (4-on-3 in youth leagues) power plays, man-down defense, fouls and kickouts, eggbeater, shooting, passing, goalie tips, driving, drills, conditioning, game nerves, and more. Tap one of the suggestion chips or type your own question. It answers from a built-in library of coaching tips (not a live/online chatbot), so it works offline and never sends your questions anywhere.

## Data & privacy

Everything (saved plays, board state, chat history) is stored only in your browser's local storage on your device. Nothing is uploaded anywhere — use the backup/restore feature in the Playbook tab if you want to move your plays to another device.
