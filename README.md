   # 🤟 SignLens Pro

   Real-time ASL hand gesture recognition — Alphabets · Numbers · Words · Phrases

   Powered by **MediaPipe Hands** · Runs 100% in the browser · No server, no uploads.

   ---

   ## ✨ Features

   - **72 gesture classes**: A–Z alphabets, 0–9 numbers, 20 words, 14 phrases
   - Live confidence ring + stability bar per gesture
   - Dataset mode switcher (All / Alphabets / Numbers / Words / Phrases)
   - Text assembly with copy & text-to-speech
   - Detection history log
   - Responsive layout (desktop & mobile)

   ---

   ## 🚀 Run Locally (VS Code)

   ### Option A — Open directly
   ```bash
   # Clone or unzip the project, then simply open index.html in Chrome/Edge
   ```
   > ⚠️ Camera requires a secure context. Use the Live Server extension (below) — **not** `file://`.

   ### Option B — VS Code Live Server (recommended)
   1. Install the **Live Server** extension by Ritwick Dey
   2. Right-click `index.html` → **Open with Live Server**
   3. Browser opens at `http://127.0.0.1:5500` — camera works!

   ---

   ## 📁 Project Structure

   ```
   SignLens-Pro/
   ├── index.html          ← Main HTML layout
   ├── src/
   │   ├── style.css       ← All styles & CSS variables
   │   ├── data.js         ← Gesture constants & mode config
   │   ├── ui.js           ← UI rendering, state, controls
   │   ├── classifier.js   ← Hand landmark → gesture classifier
   │   └── camera.js       ← MediaPipe + camera setup
   └── README.md
   ```

   ---

   ## ☁️ Deploy to GitHub Pages

   ```bash
   # 1. Create a new GitHub repo (e.g. signlens-pro)
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/signlens-pro.git
   git push -u origin main

   # 2. Enable GitHub Pages
   #    Go to: Settings → Pages → Source → Deploy from branch → main / (root)
   #    Your site will be live at: https://YOUR_USERNAME.github.io/signlens-pro/
   ```

   ---

   ## 🌐 Deploy to Render (Static Site)

   1. Push code to GitHub (see above)
   2. Go to [render.com](https://render.com) → **New → Static Site**
   3. Connect your GitHub repo
   4. Settings:
      - **Name**: signlens-pro
      - **Branch**: main
      - **Publish directory**: `.` (root)
      - **Build command**: *(leave empty)*
   5. Click **Create Static Site** — done! 🎉

   ---

   ## 🌐 Browser Support

   Chrome · Edge · Firefox · Safari 14+  
   *(Webcam requires HTTPS or localhost)*

   ---

   ## 📄 License

   MIT — free to use and modify.
