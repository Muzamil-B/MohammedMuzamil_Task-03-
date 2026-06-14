# MohammedMuzamil_Task-03-
# CSS Specificity Demo

A beginner-friendly HTML + CSS project that demonstrates how **CSS specificity** works — covering tag selectors, class selectors, ID selectors, and how conflicts between them are resolved by the browser.

---

## 📌 What This Project Covers

| Step | Concept |
|------|---------|
| 1–2  | Creating and linking an external CSS file |
| 3    | Styling the `body` background via tag selector |
| 4–5  | Applying a class selector (`.head`) to multiple headings |
| 6    | Overriding class styles with an ID selector (`#bglime`) |
| 7    | Targeting a specific word with a class selector (`.head-text`) |
| 8    | Styling all `<p>` tags using a tag selector |
| 9    | Overriding paragraph color with an ID selector (`#para`) |
| 10   | Overriding a specific word's style with a class (`.para-text`) |
| 11   | Styling "here" text two different ways — via `<strong>` and `<a>` tags |

---

## 🧠 Specificity Hierarchy (Low → High)

```
Tag selector     (0, 0, 1)   →   p { }
Class selector   (0, 1, 0)   →   .head { }
ID selector      (1, 0, 0)   →   #bglime { }
```

> ⚠️ All styling is done in `style.css` only. No inline styles are used anywhere in `index.html`.

---

## 📁 Project Structure

```
project/
├── index.html    ← HTML structure with headings, paragraphs, and lists
├── style.css     ← All CSS styles (external only)
└── README.md     ← Project documentation
```

---

## 🚀 How to Run

1. Open the project folder in **VS Code**
2. Install the **Live Server** extension (by Ritwick Dey)
3. Right-click `index.html` → **"Open with Live Server"**
4. The page auto-reloads whenever you save changes


## 🛠️ Tech Stack

- HTML5
- CSS3 (External stylesheet only)
