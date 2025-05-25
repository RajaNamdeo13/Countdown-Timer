# ⏳ Countdown Timer

A simple countdown timer that displays the remaining time until a fixed end date. The timer updates every second and includes a dynamic progress bar to show how much time has passed since the page was loaded.

---

## 🔥 Features

- Fixed **start time** (page load) and **end time** (hardcoded)
- Countdown display: Days, Hours, Minutes, Seconds
- Progress bar that visually tracks elapsed time
- Smooth and responsive UI using HTML, CSS, and JavaScript

---

## 📅 Timer Configuration

- **Start Time:** Automatically set when the page is loaded
- **End Time:** `25 May, 2025 16:34:00` (hardcoded)

If you want to change the countdown target, edit the following line in `script.js`:

```javascript
const endDate = new Date("25 May, 2025 16:34:00").getTime();

🛠️ Tech Stack
HTML – Page structure
CSS – Styling and layout
JavaScript – Timer logic and DOM manipulation

HOW TO RUN LOCALLY
1. Download or clone the repo
git clone https://github.com/RajaNamdeo13/countdown-timer.git
cd countdown-timer
2. open index.html in browser

