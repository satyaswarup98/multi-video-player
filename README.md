# 🎥 Multi Video Player Web App

A sleek, user-friendly **Multi Video Player** that allows viewing and controlling up to **9 videos simultaneously** in a responsive, dynamic grid layout.

> **Designed & Developed by Satya**

---

## 🌟 Features

### 🖼️ UI & Layout

- 📁 Upload and play **1 to 9 videos** at once.
- 📐 **Dynamic Grid Layout**:
  - Auto adjusts layout based on file count.
  - Max 3 videos per row.
  - Last row is **centered** (e.g. 7 videos → 3 + 3 + 1).
- 🌓 Smart **Fullscreen per video**:
  - Click expand icon to focus on a single video.
  - Automatically handles mute/play state.

### 🎮 Playback Controls

- ▶️ **Play/Pause all** videos together.
- ⏪ **Seek backward/forward** by 10 seconds.
- ⏩ **Next Video**: Switch to the next video fullscreen.
- 🎚️ **Seek Bar**:
  - Syncs with average progress of all videos.
  - Works even if some videos end earlier.

### 🔊 Audio Controls

- 🔇 **Mute/Unmute** individual or current video.
- 🔈 **Volume Slider**: Real-time volume control.
- 🔁 Respects mute state even during fullscreen toggling.

### ⚡ Advanced Behavior

- ⏱️ Auto-hide control bar after 5 seconds of inactivity.
- 🎞️ Accurate video duration sync — longest video determines seek range.
- ↩️ **Reverse seek** updates even ended/short videos to stay in sync.
- ⚙️ **Playback Speed Control**: 0.5x to 2x speed support.
- 🔄 Seamless fullscreen exit + restore video grid with preserved state.

---

## 📂 How to Use

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Upload 1–9 video files when prompted.
4. Use the control bar at the bottom to:
   - Play/Pause
   - Seek forward/back
   - Jump to next video
   - Adjust volume and speed
   - Toggle fullscreen

> ✅ Works offline, no server required. Pure HTML + JS + CSS.

---

## 🧠 Tech Stack

- **HTML5 Video API**
- **Vanilla JavaScript**
- **FontAwesome** (for icons)
- **CSS Grid + Flexbox**

---

## 📸 Screenshots

| Grid Layout | Fullscreen |
|-------------|------------|
| ![Grid](screens/grid.png) | ![Fullscreen](screens/fullscreen.png) |

> _(Add screenshots in a `/screens` folder)_

---

## 📄 License

MIT License. Feel free to fork, contribute, or adapt as needed.

---

## 🙏 Acknowledgements

- Inspired by advanced multicam video setups.
- Handcrafted with ❤️ by **Satya Swarup Srichandan**

---

## 🌍 How to Publish on GitHub Pages

### 1. 🗂 Create a GitHub Repository

- Go to [https://github.com](https://github.com)
- Click **"New"**
- Name it e.g., `multi-video-player`, keep it **Public**
- Click **Create Repository**

### 2. 💻 Upload Files

- Click **"Add file" → "Upload files"**
- Upload `index.html`, `style.css`, `script.js`, etc.
- Commit the changes

### 3. 🌐 Enable GitHub Pages

- Go to **Settings → Pages**
- Under **"Source"**, choose:
  - Branch: `main`
  - Folder: `/root`
- Click **Save**

### 4. 🔗 Get Your Public URL

After 30–60 seconds, your app will be live at:

## 🔗 Example Live Page


Repo: https://github.com/satyaswarup98/multi-video-player
Live: https://satyaswarup98.github.io/multi-video-player/
