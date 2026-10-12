# EziNurse — Adaptive Clinical Scenario Assessment

A browser-based adaptive clinical scenario assessment tool for undergraduate nursing education. Students work through realistic patient situations, select priority actions, and rate their confidence — the tool adjusts difficulty in real time based on performance.

## 🚀 Live Demo

Open `adaptive-assessment-v2.html` directly in any browser — no installation, no server required.

## 📋 Overview

- **13 adaptive scenarios** across 6 nursing practice domains
- Each scenario has three complexity levels (Simple → Moderate → Complex) that adjust dynamically based on the student's Bayesian Skill Index (BSI)
- Confidence rating after every decision (1–5 scale)
- Real-time performance tracking with a Response Confidence Index chart
- Session summary with domain-level feedback and trajectory analysis
- Up to 3 pauses per session

## 🏥 Clinical Domains

| Domain | Focus |
|---|---|
| Respiratory | Asthma, COPD, post-operative complications |
| Medication | Safe administration, patient education |
| Deterioration | Early recognition, rapid response |
| Infection | Sepsis, wound management |
| Fluid Balance | IV therapy, assessment |
| Neurological | Neuro observations, stroke |

## 🎯 How It Works

The tool uses an adaptive algorithm (BSI) to select scenario complexity:
- Strong performance → escalates to more complex presentations
- Declining confidence → de-escalates to consolidate foundational knowledge
- Each response is weighted by both correctness and confidence rating

## 📁 Files

```
adaptive-assessment-v2.html   # Entire application — single self-contained file
```

## 🛠 Usage

1. Download `adaptive-assessment-v2.html`
2. Open in any modern browser (Chrome, Firefox, Safari, Edge)
3. Click **Begin Assessment**

No dependencies to install. Chart.js loads from CDN.

## 👨‍💻 Author

**Dr. Samuel Duraivel**  
Researcher in adaptive learning technologies and immersive health education  
📧 duraivelsamuel@gmail.com

## 📚 References

- Duraivel, S. (2026). *Proof-of-concept implementation of the cGAN conditioning mechanism for adaptive VRET*. Zenodo. https://doi.org/10.5281/zenodo.21326066
- Tanner, C. A. (2006). Thinking like a nurse: A research-based model of clinical judgment in nursing. *Journal of Nursing Education, 45*(6), 204–211.
- Nursing and Midwifery Board of Australia (NMBA). (2016). *Registered Nurse Standards for Practice*. https://www.nursingmidwiferyboard.gov.au

## 📄 License

MIT License — © 2026 Dr. Samuel Duraivel. Free to use for educational purposes with attribution.
