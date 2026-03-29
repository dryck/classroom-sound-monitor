# 🔊 Sound Level Monitor

A classroom tool for teachers to monitor and control noise levels during lessons.

## 🎯 Features

- **Visual Sound Meter** — Real-time noise level display (0-40 dB scale)
- **Smart Warnings** — 3 warnings before consequences
- **Timer** — Tracks time until all warnings are spent
- **Coin System** — Gamification: students earn coins for quiet behavior
- **Customizable Thresholds** — Adjust noise sensitivity for your classroom
- **Audio Alerts** — Beep sounds and fanfare when limits are reached
- **Kids Mode** — Separate interface for student view

## 🚀 Quick Start

1. Open the tool in your browser
2. Click "Start microphone" 
3. Allow microphone access
4. Adjust the noise threshold slider
5. Start your lesson!

## 🎮 How It Works

### Sound Levels
- 🤫 0-4 dB — Silence
- 📚 4-12 dB — Library (perfect for class)
- 💬 12-20 dB — Quiet conversation
- 🔊 20-28 dB — Getting loud
- 📢 28-35 dB — Too loud for class!
- 🚨 35+ dB — Way too loud!

### Warnings System
- Students get **3 warnings** per session
- Each warning burns one red circle
- After 3rd warning — fanfare plays, coins stop
- Reset anytime with "Reset warnings" button

### Coin System
- Set lesson duration (default: 40 min)
- Set max coins (default: 100)
- Students earn coins proportionally to quiet time
- If all warnings spent — coins stop accumulating

## ⚙️ Settings

| Setting | Default | Description |
|---------|---------|-------------|
| Noise Threshold | 22 | dB level that triggers warnings |
| Sustained Noise | 2.0s | How long noise must persist before alert |
| Cooldown | 1.5s | Time between alerts |
| Warnings | 3 | Number of warnings per session |
| Lesson Time | 40 min | Duration for coin calculation |
| Max Coins | 100 | Total coins students can earn |

## 🛠️ Technical

- Pure HTML/CSS/JavaScript — no backend needed
- Works in any modern browser
- Requires microphone permission
- Runs entirely client-side

## 📱 Live Demo

https://dryck.github.io/classroom-sound-monitor/

## 📝 License

MIT — free to use and modify for educational purposes.

---

Made with ❤️ for teachers everywhere.
