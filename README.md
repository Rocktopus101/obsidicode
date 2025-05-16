# obsidicode
## Paste a LeetCode link, get a pre-filled Obsidian note. Track your DSA grind, one problem at a time.

# 🧠 Obsidian LeetCode Tracker

> A simple automation script using [Templater](https://github.com/SilentVoid13/Templater) + [QuickAdd](https://github.com/chhoumann/quickadd) plugins in Obsidian to auto-generate daily LeetCode notes with metadata, spaced repetition dates, and structured sections.

## 🔍 What It Does

Paste a LeetCode problem URL in your clipboard → run the template → and it will:

- Parse the problem title from the URL
- Autofill difficulty and topic using a hardcoded map
- Add today’s date and a revisit reminder
- Pre-format your note with sections for:
  - Summary
  - Approach
  - Struggles
  - Final code
  - One-liner takeaway

## 📦 Files Included

| File | Description |
|------|-------------|
| `leetcode-autofill` | Templater script you can use as a template |
| `README.md` | This file |

## 🛠️ Setup Instructions

1. Install the **Templater** and **QuickAdd** plugins in Obsidian.
2. Place `leetcode-autofill` inside your Templater templates folder.
3. Set up a QuickAdd macro to run this script when you hit a hotkey or button.
4. Copy any LeetCode link and run the script!

This is how the QuickAdd Macro should look:

<img width="628" alt="image" src="https://github.com/user-attachments/assets/f54e00d0-08b3-483b-bede-5c2ca2f9445d" />
<img width="680" alt="image" src="https://github.com/user-attachments/assets/00db539a-d5dc-4c5b-acba-1ddd232fb609" />
<img width="680" alt="image" src="https://github.com/user-attachments/assets/ef877af4-7a17-47e1-a37d-c8024b0ffb8c" />


## 🎯 Example Output

🧠 [Two Sum]
	•	🔗 LeetCode: Two Sum
	•	🟩 Difficulty: Easy
	•	📁 Topic: Arrays & Hashing
	•	Date: [[2025-05-15]]

✅ Problem Summary

…

✏️ My Approach

…

🚧 Struggles

…

💻 Final Solution (Language: python)

# paste your code here

🔄 Revisit Date: [[2025-05-22]]

## 📸 Demo
![Noaudio-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/312bd679-fd75-4824-8236-6885a8e718ae)

## 📌 Why I Made This

I wanted a better way to track my LeetCode progress while studying for interviews. Obsidian is my second brain, so I figured… why not make it automatic?

This script helps me retain concepts, plan reviews, and reflect on problems better.

---

## 🤝 Contributions

PRs welcome if you want to extend the topic/difficulty maps or add support for fetching problem data dynamically.

Currently it only supports Problem Difficulty and category for the Neetcode 150 (hardcoded implementation which I'm not too proud of but it gets the job done), so that would be the primary thing to work on. 

---

## 🧵 License

MIT License


⸻
