# 🤝 Contributing

## First Time Setup

1. **Get access** — Ask maintainer to add you as collaborator
2. **Clone repo**
```bash
git clone https://github.com/theonlyhennygod/100-days-leetcode.git
cd 100-days-leetcode
```
3. **Create your folder**
```bash
mkdir submissions/<your-username>
```

---

## Daily Workflow

Every day:

1. **Get problem** (via WhatsApp)
2. **Solve it**
3. **Submit**:

```bash
git pull origin main
git add submissions/<your-username>/dayXX_problem-name.ext
git commit -m "Day XX: Solved <Problem Name>"
git push origin main
```

**File naming:** `dayXX_problem-name.ext`
- ✅ `day01_two-sum.py`
- ✅ `day15_merge-intervals.js`
- ❌ `day1_two-sum.py` (needs zero padding)

---

## Rules

- Only modify your own folder (`submissions/<your-username>/`)
- Don't edit README.md or other root files
- Commit working code only
- Use any language you want

---

## If You Get a Conflict

```bash
git pull origin main
# Resolve conflicts in your folder
git add .
git commit -m "Resolved conflict - Day XX"
git push origin main
```

---

**That's it. Keep it simple. Code every day.** 🚀
