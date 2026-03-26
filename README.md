# 🚀 Name Generator (Subsequence-Based)

A modern, minimal, and fast **name generator** based on **subsequence combinations** of a given word.

🔗 Repository: https://github.com/kmsyunus/namegenerator

---

## ✨ Features

* 🔠 Generate **all possible subsequences** (ordered combinations)
* 🎯 Filter by **number of characters (2 → n-1)**
* 📊 Visual highlight of selected characters
* 📄 Pagination (20 results per page)
* 🔢 Clean page numbering format (`000001`)
* 🌑 Modern **Dark Mode UI**
* ⚡ Fast and fully client-side (no backend)

---

## 🧠 How It Works

The generator uses a **Depth-First Search (DFS)** algorithm to produce all subsequences while maintaining the original character order.

Example:

Input:

```
menjadi
```

Output (3 letters sample):

```
men
mej
mea
...
```

✔ Order is preserved
✔ No character rearrangement
✔ All valid combinations included

---

## 🖥️ UI Overview

* **Top Bar** → Input & Generate button
* **Horizontal Slider** → Filter by length
* **Left Panel** → Result table with visual highlight
* **Right Panel** → Pagination

---

## 🧩 Tech Stack

* HTML (Single Page Application)
* Vanilla CSS (Modern Dark UI)
* Vanilla JavaScript (ES6+)

No frameworks. No dependencies.

---

## 📦 Installation

Just clone and open:

```bash
git clone https://github.com/kmsyunus/namegenerator.git
cd namegenerator
```

Then open:

```
index.html
```

---

## 🚀 Usage

1. Enter a word
2. Click **Generate**
3. Choose character length
4. Browse results

---

## 📸 Preview

Minimal, centered layout with:

* Locked viewport (no page scroll)
* Scrollable content areas
* Clean dark interface

---

## ⚠️ Notes

* Total combinations grow exponentially: `2^n`
* Recommended input length: **≤ 12 characters** for smooth performance

---

## 👨‍💻 Author

**Kemas M. Yunus**
GitHub: https://github.com/kmsyunus

---

## ⭐ Support

If you find this useful, consider giving it a **star ⭐** on GitHub!

---
