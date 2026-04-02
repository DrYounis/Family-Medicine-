# Dr. Younis — Family Medicine Masters Study Portal

> **GitHub:** `DrYounis/Family-Medicine-`
> **Last updated:** March 2026
> **Purpose:** OSCE preparation for Family Medicine Masters programme — Egyptian dialect Arabic roleplay + English clinical checklists + MCQs

---

## Table of Contents

1. [Site Map — All Pages](#1-site-map--all-pages)
2. [OSCE Page — Complete Card Inventory (osce.html)](#2-osce-page--complete-card-inventory-oschtml)
3. [Arabic Roleplay Page — All 22 Cases (osce_approach_arabic.html)](#3-arabic-roleplay-page--all-22-cases)
4. [How to Add a New Card Pair (Template)](#4-how-to-add-a-new-card-pair-template)
5. [How to Add a New Arabic Case (Template)](#5-how-to-add-a-new-arabic-case-template)
6. [Non-Negotiable Rules](#6-non-negotiable-rules)
7. [Card Numbering Convention](#7-card-numbering-convention)
8. [Pushing to GitHub](#8-pushing-to-github)
9. [Changelog](#9-changelog)

---

## 1. Site Map — All Pages

| File | Title | Language | Purpose |
|------|-------|----------|---------|
| `index.html` | MCQ Board Review | English | 50+ MCQs across all specialties |
| `osce.html` | OSCE Study Portal | English | 27 Roleplay + 27 Checklist cards + Rx blocks |
| `osce_approach_arabic.html` | Roleplay بالعامية | Arabic (Egyptian) | 22 clinical cases with step-by-step Arabic phrases + practice mode |
| `cheatsheet.html` | Clinical Cheatsheet | English | Quick-reference clinical summaries |
| `medications.html` | Medications Reference | English | Drug reference by system |
| `hand_examination.html` | Hand Examination | English | Hand & CTS examination guide |
| `jvp_examination.html` | JVP Examination | English | Jugular venous pressure examination |
| `gerd_approach_arabic.html` | GERD Arabic Approach | Arabic | Dedicated GERD Arabic roleplay script |
| `roleplay_arabic.html` | Arabic Roleplay (legacy) | Arabic | Original GERD role player card |

---

## 2. OSCE Page — Complete Card Inventory (`osce.html`)

### Naming Rule
Every topic has **two cards** — always added as a pair:
- `type: "roleplay"` — patient scenario card (what the simulated patient says)
- `type: "checklist"` — doctor assessment card (good vs poor performance)
- Plus an embedded **`rx`** block inside the roleplay card (prescription)

### Full Card List — 27 Topics

| # | Checklist No. | RP No. | Topic | Category |
|---|--------------|--------|-------|----------|
| 1 | `01` | `RP-00` | GERD — History & Management | GERD |
| 2 | `02` | `RP-02` | Cranial Nerve Examination | Clinical Skills |
| 3 | `03` | `RP-03` | Pediatric COVID-19 | Pediatrics |
| 4 | `04` | `RP-04` | Renal / Ureteric Stone | Internal Med |
| 5 | `06` | `RP-05` | Sciatica | MSK |
| 6 | `07` | `RP-07` | Diabetic Foot Examination | Clinical Skills |
| 7 | `08` | `RP-08` | IMCI — General Pediatric Assessment | Pediatrics |
| 8 | `09` | `RP-09` | Common Cold vs. Acute Rhinosinusitis | Pediatrics |
| 9 | `10` | `RP-10` | Acute Otitis Media (AOM) | Pediatrics |
| 10 | `11` | `RP-11` | Iron Deficiency Anaemia (IDA) | Pediatrics |
| 11 | `12` | `RP-12` | Thyroid Assessment | Internal Med |
| 12 | `13` | `RP-13` | Diabetes Mellitus Type 2 | Internal Med |
| 13 | `14` | `RP-14` | Chest Pain — Differentials | Internal Med |
| 14 | `16` | `RP-15` | High-Risk DM + Chest Pain | Internal Med |
| 15 | `17` | `RP-17` | Emesis Gravidarum | Obstetrics |
| 16 | `18` | `RP-18` | Abnormal Uterine Bleeding (AUB) | Obstetrics |
| 17 | `19` | `RP-16` | Shoulder Examination | MSK |
| 18 | `20` | `RP-17` | Elbow Examination (Tennis Elbow) | MSK |
| 19 | `21` | `RP-18` | Hand & Carpal Tunnel Syndrome | MSK |
| 20 | `22` | `RP-19` | Nocturnal Enuresis | Pediatrics |
| 21 | `23` | `RP-20` | Peptic Ulcer Disease (PUD) | GI |
| 22 | `24` | `RP-21` | Post-Menopausal Bleeding (PMB) | Gynaecology |
| 23 | `25` | `RP-22` | Osteoporosis | MSK |
| 24 | `26` | `RP-23` | Infertility — Both Partners | Gynaecology |
| 25 | `27` | `RP-24` | Peptic Ulcer Disease — Extended | GI |
| 26 | `28` | `RP-25` | Headache & Migraine | Neurology |
| 27 | `29` | `RP-26` | Dizziness & Vertigo (Ménière's) | Neurology |

**Totals:** 27 roleplay cards · 27 checklist cards · 27 rx prescription blocks

### Filters available in osce.html
- **Category filter** bar (by specialty)
- **Live search box** — searches across: title, patient name, chief complaint, history, good/poor items
- **Mode tabs:** All · Role Player · Checklist · Rx

---

## 3. Arabic Roleplay Page — All 22 Cases

**File:** `osce_approach_arabic.html`
**Format:** Each case has numbered steps with Arabic phrase boxes + clinical info boxes
**System filter:** باطنة · أطفال · عضلات وعظام · نساء وتوليد · أعصاب

| # | Case ID | Name | System |
|---|---------|------|--------|
| 1 | `sciatica` | عرق النسا (Sciatica) | عضلات وعظام |
| 2 | `diabetic-foot` | القدم السكرية | باطنة |
| 3 | `imci` | IMCI — تقييم الطفل | أطفال |
| 4 | `cold-sinusitis` | نزلة برد أم جيوب أنفية؟ | أطفال |
| 5 | `aom` | التهاب الأذن الوسطى (AOM) | أطفال |
| 6 | `ida` | فقر الدم بالحديد (IDA) | أطفال |
| 7 | `thyroid` | الغدة الدرقية | باطنة |
| 8 | `cranial-nerve` | الأعصاب القحفية | أعصاب |
| 9 | `renal-stone` | حصوة الكلى | باطنة |
| 10 | `dm` | السكري وخطر القلب | باطنة |
| 11 | `chest-pain` | ألم الصدر — التفريق | باطنة |
| 12 | `dm-chest` | سكري عالي الخطر + ألم صدر | باطنة |
| 13 | `gerd` | GERD / ارتجاع المريء | باطنة |
| 14 | `covid-pediatric` | كوفيد-١٩ (طفل) | أطفال |
| 15 | `emesis` | قيء الحمل (Emesis Gravidarum) | نساء وتوليد |
| 16 | `aub` | نزيف الرحم الشاذ (AUB) | نساء وتوليد |
| 17 | `shoulder-exam` | فحص الكتف | عضلات وعظام |
| 18 | `elbow-exam` | فحص الكوع (Tennis Elbow) | عضلات وعظام |
| 19 | `hand-cts-exam` | فحص اليد ومتلازمة النفق الرسغي | عضلات وعظام |
| 20 | `pmb` | نزيف ما بعد انقطاع الطمث (PMB) | نساء وتوليد |
| 21 | `osteoporosis` | هشاشة العظام (Osteoporosis) | عضلات وعظام |
| 22 | `infertility` | العقم وصعوبة الإنجاب | نساء وتوليد |

**Total: 22 cases**

---

## 4. How to Add a New Card Pair (Template)

Always add **both cards together** — roleplay first, then checklist. Both go inside the `cards` array in `osce.html`.

### Step 1 — Roleplay Card

```javascript
{
    cat: "Gynaecology",          // category shown in filter bar
    type: "roleplay",
    cardNum: "RP-27",            // next RP number in sequence
    q: "Topic Name — Role Player Information",
    patientName: "Full Name Here",
    age: "XX years old",
    background: "One-paragraph backstory. Occupation, marital status, relevant history.",
    chiefComplaint: "One sentence chief complaint",
    history: [
        "Main presenting symptom — how it started, duration, character",
        "Associated symptoms — mention only if specifically asked",
        "Relevant past medical history",
        "Medications and allergies",
        "Family history — if relevant",
        "Social history — smoking, alcohol, occupation",
        "ICE: what the patient thinks, fears, and expects"
    ],
    rx: {
        diagnosis: "Full Diagnosis Name — subtype if applicable",
        allergyNote: "NKDA — confirmed before prescribing",
        drugs: [
            { name: "Drug Name (Brand)", dose: "Dose", timing: "Frequency × Duration — reason" },
            { name: "Second Drug",       dose: "Dose", timing: "Frequency — reason" }
        ],
        followUp: "Follow-up plan and what to check.",
        returnIf: "Red flag symptoms — return immediately if..."
    }
},
```

### Step 2 — Checklist Card

```javascript
{
    cat: "Gynaecology",
    type: "checklist",
    cardNum: "30",               // next checklist number
    q: "Topic Name — Assessment & Management",
    good: [
        // HISTORY
        "Establishes rapport; acknowledges patient concerns",
        "Asks about [symptom] — onset, duration, severity, character",
        // EXAMINATION
        "Checks vital signs: BP, HR, temperature",
        // INVESTIGATIONS
        "Orders [investigation] — reason and what it shows",
        // MANAGEMENT
        "Prescribes [drug] [dose] [frequency] — after checking allergies",
        // SAFETY NETTING
        "Provides red flag advice: return if [criteria]",
        "Arranges follow-up in [timeframe]"
    ],
    poor: [
        "Does not ask about [key symptom]",
        "Does not order [essential investigation]",
        "Does not check allergies before prescribing",
        "Does not arrange follow-up"
    ]
},
```

---

## 5. How to Add a New Arabic Case (Template)

Add inside the `cases` array in `osce_approach_arabic.html`, before `]; // end cases`.

```javascript
{
    id: 'case-id',                    // unique lowercase hyphenated id
    system: 'باطنة',                  // باطنة | أطفال | عضلات وعظام | نساء وتوليد | أعصاب
    name: 'اسم الحالة (English)',
    icon: '🩺',
    color: '#2563eb', colorLight: '#eff6ff',
    steps: [
        {
            tag: 'تعريف المرض',
            tagColor: '#eff6ff', tagText: '#2563eb',
            title: 'إيه هو المرض وإزاي تشرحه للمريض؟',
            phrases: [
                { label: '📍 شرح المرض', text: '"..." ' },
                { label: '⚠️ قاعدة مهمة', text: '"..."' }
            ],
            clinical: {
                type: 'single',            // 'single' | 'two-col'
                color: 'blue',             // blue | green | red | orange | pink
                title: '📋 العنوان',
                items: ['بند ١', 'بند ٢']
            }
        },
        {
            tag: 'تاريخ الأعراض',
            tagColor: '#eff6ff', tagText: '#2563eb',
            title: 'إزاي تسأل عن الأعراض؟',
            phrases: [
                { label: '📍 الشكوى الرئيسية', text: '"..."' }
            ],
            clinical: null
        }
        // ... more steps
    ]
},
```

**Note:** After the last existing case, add a `,` then your new case object before `]; // end cases`.

---

## 6. Non-Negotiable Rules

These rules apply to **every card** without exception:

### Prescriptions (Rx blocks)
1. **Always ask about allergies before prescribing** — every rx block must state `allergyNote`
2. **Full diagnosis** must appear in `rx.diagnosis` — not just "fever" but "Acute Otitis Media"
3. **Drug entries** must include: drug name (+ brand), dose, timing, duration, and reason
4. **Follow-up** must be specified — time interval + what to check
5. **Return criteria** (red flags) must be listed — symptoms that require emergency attendance

### Medical Content
6. **Never change medical content** — only enhance teachability, formatting, or language
7. **Never add medications that were not discussed** in the session notes or audio
8. **Age-based AUB framework** must be applied for any bleeding case:
   - 20–30s → rule out pregnancy first
   - 30–40s → structural causes (fibroids, polyps)
   - 40–50+ → endometrial carcinoma until proven otherwise
   - Post-menopausal → **treat as cancer until proven otherwise**

### Roleplay Cards
9. **ICE** (Ideas, Concerns, Expectations) must always be in the history array
10. **Sensitive history points** (dyspareunia, vaginal infections, sexual history, stress) must be labelled: *"mention only if specifically asked"*
11. **Both partners** must be assessed when the case involves infertility or couples

---

## 7. Card Numbering Convention

```
Roleplay cards:  RP-00, RP-02, RP-03 ... RP-26
Checklist cards: 01, 02, 03 ... 29

Pairing rule:
  RP-XX  pairs with  checklist XX+1  (not always — some are 1:1)
  The cards are LINKED by topic, not strictly by matching number.
```

**Known numbering quirks** (do not change — affects existing references):
- `RP-00` pairs with checklist `01` (GERD)
- `RP-05` pairs with checklist `06` (Sciatica)
- `RP-15` pairs with checklist `16` (High-Risk DM + Chest)
- `RP-16` pairs with checklist `19` (Shoulder Exam)
- `RP-19` pairs with checklist `22` (Nocturnal Enuresis — appears at end of array)

**Next available numbers:**
- Next roleplay: `RP-27`
- Next checklist: `30`

---

## 8. Pushing to GitHub

Always fetch the current SHA before pushing. Never push without fetching first.

```javascript
// Run with: node push.js  (or inline with node -e)
const fs = require('fs'), https = require('https');
const TOKEN = 'YOUR_PAT_HERE';
const OWNER = 'DrYounis', REPO = 'Family-Medicine-';

function ghReq(opt, body) {
  return new Promise((res, rej) => {
    const r = https.request({
      hostname: 'api.github.com',
      path: opt.path,
      method: opt.method || 'GET',
      headers: {
        'Authorization': 'token ' + TOKEN,
        'Accept': 'application/vnd.github.v3+json',
        'User-Agent': 'node-script',
        ...(body ? { 'Content-Type': 'application/json', 'Content-Length': Buffer.byteLength(body) } : {})
      }
    }, resp => { let d = ''; resp.on('data', c => d += c); resp.on('end', () => res(JSON.parse(d))); });
    r.on('error', rej);
    if (body) r.write(body);
    r.end();
  });
}

async function pushFile(path, message) {
  const cur = await ghReq({ path: `/repos/${OWNER}/${REPO}/contents/${path}` });
  const b64 = fs.readFileSync(path).toString('base64');
  const body = JSON.stringify({ message, content: b64, sha: cur.sha });
  const r = await ghReq({ path: `/repos/${OWNER}/${REPO}/contents/${path}`, method: 'PUT' }, body);
  console.log(path, '→ commit:', r.commit?.sha);
}

// Push multiple files:
(async () => {
  await pushFile('osce.html', 'Update: description of changes');
  await pushFile('osce_approach_arabic.html', 'Update: description of changes');
})().catch(console.error);
```

---

## 9. Changelog

| Date | Change | Files |
|------|--------|-------|
| March 2026 | Added PMB (RP-21/Card 24): age-based AUB framework, TVS, endometrial biopsy | `osce.html` |
| March 2026 | Added Osteoporosis (RP-22/Card 25): DEXA, T-score, Alendronate | `osce.html` |
| March 2026 | Added Infertility (RP-23/Card 26): both-partner assessment, FSH/LH/AMH, Semen Analysis | `osce.html` |
| March 2026 | Added PUD (RP-24/Card 27): H. pylori triple therapy, NSAID counselling, alarm features | `osce.html` |
| March 2026 | Added Headache/Migraine (RP-25/Card 28): SNOOP3, POUND, Sumatriptan + Propranolol | `osce.html` |
| March 2026 | Added Dizziness/Vertigo (RP-26/Card 29): duration framework, Ménière's, Betahistine | `osce.html` |
| March 2026 | Added live search box to osce.html (searches all card fields) | `osce.html` |
| March 2026 | Removed voice recording feature completely | `osce.html` |
| March 2026 | Added system filter bar to osce_approach_arabic.html (5 specialty buttons) | `osce_approach_arabic.html` |
| March 2026 | Updated RP-21/24 (PMB): added dyspareunia history point | `osce.html` |
| March 2026 | Updated RP-22/25 (Osteoporosis): added general bone pain + sedentary lifestyle | `osce.html` |
| March 2026 | Updated RP-23/26 (Infertility): added vaginal infections (wife) + stress (husband) | `osce.html` |
| March 2026 | Added Arabic cases 20–22 to osce_approach_arabic.html: PMB, Osteoporosis, Infertility | `osce_approach_arabic.html` |
| March 2026 | Fixed all non-standard cardNum values (RP2→RP-17, RP3→RP-18, etc.) | `osce.html` |

---

## Quick Checklist — Before Every Push

- [ ] New card pair added? Both RP + Checklist present?
- [ ] Rx block complete? (diagnosis, allergyNote, drugs, followUp, returnIf)
- [ ] Allergy question mentioned in both good[] and allergyNote?
- [ ] Topic added to Arabic page too? (`osce_approach_arabic.html`)
- [ ] Card numbers correct and sequential?
- [ ] Medical content unchanged? (no new drugs added beyond session notes)
- [ ] SHA fetched fresh before pushing?
