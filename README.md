# HabitFlow — Habit Tracker 🌿

A beautiful, responsive, and feature-rich habit tracker built with **vanilla HTML/CSS/JavaScript**.  
Tracks daily habit completion, calculates streaks, visualizes progress with a donut chart, and stores data locally (no backend required). Perfect for a portfolio project or internship demo.

---

## 🚀 Demo
Open `index.html` in your browser or serve the `public/` folder with a static server.  
(If you deploy this, add a live demo URL here.)

---

## ✨ Features

- Add / edit / delete habits (title, color, weekly target)  
- Mark daily completion on a weekly calendar view  
- Week navigation (previous / next week)  
- Current streak and best streak calculations  
- Progress donut chart (Chart.js) showing completed vs remaining checks  
- Search & filter habits by name  
- Export / Import JSON backup (download/upload)  
- Light / Dark theme toggle  
- LocalStorage persistence (no server)  
- Mobile-first, responsive, accessible UI with animations

---
🧭 How to use

Add habit: Fill the title, choose a color and weekly target → click Add Habit.

Mark completion: In calendar week view, click a habit blob for a day to toggle completion.

Edit/Delete: Use the edit (✎) or delete buttons in the habits list.

Navigate weeks: Use ◀ / ▶ to change the displayed week.

Export / Import: Back up your data with Export (JSON) and restore via Import.

Theme: Toggle Light / Dark using the theme button.

Storage: All data is saved to your browser localStorage under key habitflow_v1.

🛠 Tech & Libraries

HTML5, CSS3 (responsive, mobile-first design)

Vanilla JavaScript (ES6+)

Chart.js
 (doughnut chart via CDN)

No backend required (localStorage persistence). Easily extendable to a server + DB.

📈 Possible enhancements (ideas)

User accounts with server-side persistence (Express + MongoDB)

Push notifications / reminders (Service Worker + Notifications API)

Calendar heatmap and long-term analytics

Recurring habit scheduling & custom frequencies

Sync across devices (cloud storage)

Improve accessibility (ARIA readouts, keyboard navigation)

🧾 Contributing

Contributions, issues and feature requests are welcome.

Fork the repo

Create a feature branch (git checkout -b feature/awesome)

Commit your changes (git commit -m 'Add awesome feature')

Push to the branch (git push origin feature/awesome)

Open a Pull Request

📷 Screenshots

Add screenshots of the app here (recommended). Example:

🔒 License

This project is open-source and available under the MIT License. See LICENSE for details.

❤️ Thanks / Contact

Made with ❤️.
If you share this repo publicly, drop a link — I’d love to see it live!


