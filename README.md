# 🧭 Study Compass

**A simple, browser-based dashboard to help students plan exams, stay focused, and solve maths step by step.**

Keep your exam dates, paper patterns, revision topics, reminders, and focus sessions together in one place.

<p align="center">
  <a href="https://github.com/shanyufantam/study-compass/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/shanyufantam/study-compass?style=for-the-badge&color=2f855a"></a>
  <a href="https://github.com/shanyufantam/study-compass/network/members"><img alt="GitHub forks" src="https://img.shields.io/github/forks/shanyufantam/study-compass?style=for-the-badge"></a>
  <a href="https://github.com/shanyufantam/study-compass/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/shanyufantam/study-compass?style=for-the-badge"></a>
  <img alt="Runs in the browser" src="https://img.shields.io/badge/platform-browser-4776a8?style=for-the-badge">
</p>

## ✨ What you can do

- 📅 **Plan exams** — save subjects, exam dates, start times, duration, and total marks.
- 🧠 **Track revision** — keep paper patterns and topics to review with each exam.
- 📊 **Track preparation** — update your preparation progress as you study.
- ✅ **Plan your day** — add subject-tagged study tasks, check them off, and see your completion progress.
- 🔔 **Set reminders** — schedule study reminders for upcoming exams.
- ⏱️ **Focus with a timer** — run, pause, and resume a focused study session.
- ➗ **Solve maths step by step** — simplify arithmetic, solve one-variable linear equations, and work through systems of linear equations.
- 🌙 **Choose your theme** — switch between light and dark mode.
- 💾 **Back up your work** — export exams and tasks to a JSON file and restore them later.
- 🔒 **Keep your data in your browser** — study data is saved in local browser storage; no account is required.

## 🚀 Get started

### Option 1: Open it directly

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Add your next exam and start planning.

No installation or account is needed for this option.

### Option 2: Run with Node.js

You need **Node.js 18 or newer**.

```bash
git clone https://github.com/shanyufantam/study-compass.git
cd study-compass
npm start
```

Then visit **http://localhost:3000** in your browser.

To use a different port:

**PowerShell (Windows):**
```powershell
$env:PORT=4000; npm start
```

**macOS / Linux:**
```bash
PORT=4000 npm start
```

## 🧮 Maths solver examples

Enter an arithmetic expression:

```text
(12 + 8) / 4
```

Or solve a system by putting one equation on each line:

```text
2x + y = 7
x - y = 1
```

The solver displays the variable order, augmented matrix, row operations, and final solution. It is designed for arithmetic and **linear** equations, not general nonlinear algebra.

## 📁 Project structure

| File | Purpose |
| --- | --- |
| `index.html` | Main dashboard structure |
| `styles.css` | Styling and responsive layout |
| `app.js` | Exam planner, reminders, focus timer, and maths solver |
| `study-compass.html` | Original single-file version |
| `server.js` | Local Node.js server used by `npm start` |
| `package.json` | Project metadata and start scripts |

## 🔐 Data and privacy

Study Compass stores exams, daily tasks, and theme preferences in your browser's local storage. Your saved data is tied to the browser and device you use, so it does not automatically sync between devices. Use **Export** to save a JSON backup and **Import** to restore one. Importing a backup replaces the current exams and tasks after confirmation. If you clear that browser's site data, locally saved information may be removed.

## 🤝 Contributing

Contributions, bug reports, and feature ideas are welcome!

1. Check the existing code and open issues first.
2. Create a fork of the repository.
3. Make your changes on a separate branch.
4. Test your changes in a browser.
5. Open a pull request describing what you changed and why.

Not ready to code? You can still help by [opening an issue](https://github.com/shanyufantam/study-compass/issues) with a clear bug report or feature suggestion.

## 💡 Ideas and feedback

Have an idea that would make studying easier? [Open an issue](https://github.com/shanyufantam/study-compass/issues) and share it.

If Study Compass is useful to you, consider giving the project a ⭐ on GitHub. It helps others discover it.

---

<p align="center">Made for clearer plans, focused study sessions, and less exam-day chaos. 📚</p>
