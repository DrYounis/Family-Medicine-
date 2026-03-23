# Dr. Younis Master Study Portal - Exam Materials

---

## 📁 Project Structure

```
/Volumes/Elements/Exam/
├── README.md                    # This file - Project documentation
├── index.html                   # Main MCQs Practice Page
├── osce.html                    # OSCE Flashcards (Good/Poor Performance)
├── roleplay_arabic.html         # Arabic Role Play Script (GERD Case)
├── OSCE_content.txt             # Raw OSCE flashcards content (English)
├── OSCE_Flashcards (1).docx     # Original OSCE flashcards document
└── arabic script GERD.jpg       # Original Arabic role play script image
```

---

## 🌐 Pages Overview

| File | Purpose | Key Features |
|------|---------|--------------|
| `index.html` | MCQs Board Review | 50+ questions across OB/GYN, Pediatrics, Ethics, Internal Med, etc. |
| `osce.html` | OSCE Flashcards | Checklists with Good vs Poor performance columns |
| `roleplay_arabic.html` | Arabic Role Play | GERD case role player instructions (RTL Arabic) |

---

## 🚀 Quick Update Guide

### Update MCQs (index.html)
1. Open `index.html`
2. Find the `questionBank` array in the `<script>` section
3. Add new questions following this format:
```javascript
{ cat: "Category", q: "Question text?", a: "Answer text" },
```
4. Update the "Updated:" date in the header

### Update OSCE Flashcards (osce.html)
1. Open `osce.html`
2. Find the `questionBank` array in the `<script>` section
3. Add new checklist cards:
```javascript
{
    cat: "Category",
    type: "checklist",
    cardNum: "XX",
    q: "Card title",
    good: ["Good point 1", "Good point 2"],
    poor: ["Poor point 1", "Poor point 2"]
}
```
4. Update the "Updated:" date in the header

### Update Arabic Role Play (roleplay_arabic.html)
1. Open `roleplay_arabic.html`
2. Edit the Arabic content in the HTML sections
3. Content is organized in:
   - Patient info section (`.patient-info`)
   - Main dialogue section (`.section`)
   - Warning section (`.section.warning`)
   - Medical history section (`.section.success`)

### Add New Role Play Cases
1. Duplicate `roleplay_arabic.html` as `roleplay_arabic_XXX.html`
2. Replace Arabic content with new case info
3. Add link to `index.html` and `osce.html` navigation

---

## 🎨 Styling & Design

| Page | Color Scheme | Font |
|------|--------------|------|
| index.html | Blue (#2563eb) | Inter |
| osce.html | Blue + Green/Red | Inter |
| roleplay_arabic.html | Purple gradient | Cairo (Arabic) |

---

## 📱 Mobile Responsiveness

- **index.html**: Fully responsive cards
- **osce.html**: On mobile, Good/Poor columns stack vertically (Good first, Poor below)
- **roleplay_arabic.html**: RTL layout optimized for Arabic text

---

## 🔗 Navigation Links

All pages are interconnected:
- `index.html` → Links to OSCE + Arabic Role Play
- `osce.html` → Links to MCQs + Arabic Role Play
- `roleplay_arabic.html` → Links back to `index.html`

---

## 📝 Recent Updates

| Date | Change | Files Modified |
|------|--------|----------------|
| March 20, 2026 | Added Arabic Role Play page | `roleplay_arabic.html` (new), `index.html`, `osce.html` |
| March 20, 2026 | Mobile enhancement for OSCE cards | `osce.html` (responsive CSS) |

---

## 🛠 How to Open

Simply open any `.html` file in a web browser:
```bash
open /Volumes/Elements/Exam/index.html
```

Or double-click the file in Finder.

---

## 📞 Support

For issues or updates, contact Dr. Younis.
