# 🏥 Clinical AI + Human Intuition Risk Assessment

An interactive demonstration tool showing how AI risk algorithms and human clinical intuition work together in Emergency Department risk assessment.

## 🌐 Live Demo

**[View Live App](https://drzayed87.github.io/clinical-intuition-app/)**

---

## 🎯 Purpose

This tool is designed for **medical education** to illustrate:

| AI Strengths | Human Strengths |
|--------------|-----------------|
| Consistent scoring | Contextual interpretation |
| Never forgets variables | "Sick or not sick" gestalt |
| Processes structured data | Understands the "WHY" |
| Scalable across patients | Recognizes deviation from baseline |

### Key Learning Objectives

1. **What AI sees**: Structured EHR data (vitals, labs, utilization history)
2. **What AI misses**: Clinical context, soft signs, bedside assessment
3. **How humans add value**: Adjusting algorithm scores with clinical knowledge
4. **When to trust which**: Decision framework for AI-human collaboration

---

## 🏥 Case Study: Mr. H. Mansour

The demo uses a realistic case of a 78-year-old patient presenting to the ER:

| Parameter | Value | AI Interpretation |
|-----------|-------|-------------------|
| Age | 78 years | — |
| BP | 155/90 | Uncontrolled HTN (+3) |
| ER Visits (6mo) | 3 | High Utilizer (+4) |
| Comorbidities | CHF, COPD, T2DM, CKD | Multi-morbidity (+3) |
| Med Adherence | Irregular | Non-Compliance (+3) |
| Living Status | Alone | Lack of Support (+2) |
| **AI Total** | | **15/16 = HIGH RISK** |

---

## 📊 How It Works

### Tab 1: 🤖 AI Assessment (Raw)
Shows the algorithm output based solely on structured EHR data.

### Tab 2: 👨‍⚕️ Human Adjustment of AI Variables
Clinicians can adjust each AI score based on clinical context:

| AI Variable | Question for Clinician |
|-------------|----------------------|
| BP 155 | Is this actually his baseline? |
| 3 ER visits | Were these appropriate or concerning? |
| Non-compliance | WHY? Cognitive decline? Cost? Choice? |
| Lives alone | Does family visit daily? |
| Multi-morbidity | Are conditions controlled or interacting? |

### Tab 3: 👁️ Soft Signs (AI Blind Spot)
Factors only the clinician can assess:

- **"Sick or Not Sick"** — First 3-second gestalt
- **Skin** — Color, diaphoresis, mottling
- **Breathing** — Work of breathing, pattern
- **Mental Status** — Orientation, change from baseline
- **Baseline Deviation** — "Is this normal for him?"
- **Gut Feeling** — What does your experience tell you?

### Tab 4: ⚖️ Final Comparison
Side-by-side comparison with interpretation:

| Scenario | Interpretation |
|----------|---------------|
| Human < AI | AI may be overestimating — verify context |
| Human ≈ AI | Agreement — proceed with confidence |
| Human > AI | Human sees something AI missed — escalate |
| Human >> AI | 🚨 Urgent — patient may crash |

---

## 💡 Key Teaching Points

1. **AI provides the scaffold** — Ensures nothing is missed, consistent baseline
2. **Humans provide context** — "WHY" matters as much as "WHAT"
3. **Soft signs are invisible to AI** — Gestalt, gut feeling, family concern
4. **Disagreement is information** — When AI and human diverge, investigate

---

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** — No dependencies, runs anywhere
- **Mobile responsive** — Works on tablets for bedside teaching
- **No data collection** — All processing happens locally
- **GitHub Pages ready** — Just enable Pages in settings

---

## 📚 References

- Obermeyer, Z., et al. (2019). Dissecting racial bias in an algorithm. *Science*
- Elias, P., et al. (2022). Clinical intuition vs. machine learning in medicine
- ESI Triage Guidelines, Version 5
- NEWS2 National Early Warning Score

---

## 👨‍⚕️ Author

**Dr. Ahmed Zayed**  
Clinical AI Specialist | Medical Writer | Healthcare Technology

---

## 📄 License

MIT License — Free for educational use

---

## 🤝 Contributing

Suggestions for additional clinical scenarios or improvements are welcome! Open an issue or submit a PR.
