# 🤝 Contributing to 100 Days of LeetCode

Welcome! This guide explains how to submit your daily solutions.

---

## 🚀 Quick Start (First Time Setup)

### 1. Get Repository Access
Ask a maintainer to add you as a **collaborator** with write access.

### 2. Clone the Repository
```bash
git clone https://github.com/theonlyhennygod/100-days-leetcode.git
cd 100-days-leetcode
```

### 3. Create Your Personal Folder
```bash
mkdir submissions/<your-github-username>
cd submissions/<your-github-username>
```

### 4. (Optional) Add Your Progress Tracker
```bash
echo "# My 100 Days Progress" > README.md
```

---

## 📝 Daily Workflow

### Each Day, Follow These Steps:

#### 1. Pull Latest Changes
Always pull before you start to avoid conflicts:
```bash
git pull origin main
```

#### 2. Solve Your LeetCode Problem
Write your solution in your folder:
```bash
submissions/<your-username>/dayXX_problem-name.ext
```

**Example:**
```bash
submissions/theonlyhennygod/day01_two-sum.py
```

#### 3. Add Your File
```bash
git add submissions/<your-username>/dayXX_problem-name.ext
```

#### 4. Commit with Clear Message
```bash
git commit -m "Day XX: Solved <Problem Name>"
```

**Examples:**
```bash
git commit -m "Day 01: Solved Two Sum"
git commit -m "Day 15: Solved Merge K Sorted Lists"
```

#### 5. Push to Main
```bash
git push origin main
```

---

## 🔁 If You Get a Conflict

Conflicts are rare since everyone has their own folder, but if it happens:

```bash
# Pull the latest changes
git pull origin main

# If there's a conflict in YOUR folder, resolve it manually
# Then:
git add .
git commit -m "Resolved merge conflict - Day XX"
git push origin main
```

---

## 📋 File Naming Rules

- **Format:** `dayXX_problem-name.ext`
- **Day number:** Two digits (01, 02, ..., 99)
- **Problem name:** Lowercase, hyphen-separated
- **Extension:** Your language's file extension

**Valid Examples:**
- ✅ `day01_two-sum.py`
- ✅ `day23_binary-tree-level-order.java`
- ✅ `day99_lru-cache.cpp`

**Invalid Examples:**
- ❌ `day1_two-sum.py` (needs zero padding)
- ❌ `Day01_Two_Sum.py` (wrong case)
- ❌ `two-sum.py` (missing day number)

---

## 🛡️ Important Rules

### ⚠️ Only Modify Your Own Folder
- **DO:** Add/edit files in `submissions/<your-username>/`
- **DON'T:** Modify other people's folders
- **DON'T:** Edit README.md, rules.md, or other root files (unless you're a maintainer)

### 🔒 Keep the Main Branch Clean
- Commit only working, tested code
- Don't commit personal notes, temp files, or IDE configs (they're in `.gitignore`)

---

## 🎯 Optional: Create a Personal Progress Log

Inside your folder, you can maintain a `README.md` to track your journey:

```markdown
# My 100 Days Journey

| Day | Problem | Difficulty | Language | Time | Space | Notes |
|-----|---------|------------|----------|------|-------|-------|
| 1 | Two Sum | Easy | Python | O(n) | O(n) | Hash map approach |
| 2 | Add Two Numbers | Medium | Python | O(max(m,n)) | O(max(m,n)) | Linked list traversal |
| 3 | Longest Substring | Medium | Java | O(n) | O(min(m,n)) | Sliding window |
```

---

## 🆘 Need Help?

- **Git issues?** Ask in the repo Discussions or Issues
- **Problem-solving help?** Share your approach (not full solution) in Discussions
- **Streak broken?** No worries—catch up and keep going!

---

## 🏆 Stay Consistent

Remember: **1 commit per day, 100 days in a row.**

You've got this! 💪
