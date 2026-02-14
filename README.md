# 🧘 FlowState

> A minimal, beautiful focus timer dashboard with session tracking, streaks, and productivity visualizations.

![FlowState Preview](https://via.placeholder.com/1200x630/0f172a/38bdf8?text=FlowState+Dashboard)

## ✨ Features

- **Focus Timer** — Customizable Pomodoro-style timer with visual progress ring
- **Session Types** — Focus (25min), Short Break (15min), Long Break (30min)
- **Progress Tracking** — Daily sessions and minutes counter
- **Weekly Analytics** — Beautiful Chart.js visualization of your week
- **Session History** — Log of recent focus sessions with status
- **Streak Counter** — Maintain your daily focus streak
- **Motivational Quotes** — Inspirational quotes to keep you focused
- **Desktop Notifications** — Get notified when sessions complete
- **Dark Mode UI** — Easy on the eyes, perfect for deep work

## 🛠️ Built With

- **[Tailwind CSS](https://tailwindcss.com/)** — Utility-first CSS framework
- **[Chart.js](https://www.chartjs.org/)** — Beautiful charts and visualizations
- **[Heroicons](https://heroicons.com/)** — Beautiful hand-crafted SVG icons
- **Vanilla JavaScript** — No frameworks, just clean JS

## 🚀 Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/ai-develops/flowstate.git
   cd flowstate
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   npx serve
   ```

### GitHub Pages Deployment

1. Go to repository **Settings** → **Pages**
2. Select **Source**: Deploy from a branch
3. Select **Branch**: `main` / `root`
4. Your site will be live at: `https://ai-develops.github.io/flowstate`

## 📖 Usage

1. **Set your task** — Enter what you're working on in the task input
2. **Choose session type** — Focus, Short Break, or Long Break
3. **Start the timer** — Click "Start Focus" to begin
4. **Stay focused** — Work until the timer completes
5. **Track progress** — View your stats and history

## 🎨 Customization

The dashboard uses CSS custom properties and Tailwind configuration. Key customization points:

```javascript
// Timer durations (in minutes)
const durations = { focus: 25, shortBreak: 15, longBreak: 30 };

// Theme colors in tailwind.config
colors: {
  flow: { /* sky-500 palette */ }
}
```

## 📊 Data Persistence

Current version uses in-memory storage. Future versions will include:
- LocalStorage for session persistence
- Export/import functionality
- Cloud sync capabilities

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## 📄 License

MIT License — feel free to use this for your own productivity journey!

---

<p align="center">
  Made with focus ❤️ • <a href="https://ai-develops.github.io/flowstate">Live Demo</a>
</p>
