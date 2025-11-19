# AI for Healthcare: Interactive Educational Demos

**Making AI Concepts Accessible for Clinical Audiences**

---

## About This Project

I'm a pharmacist turned software engineer working to bridge the gap between technical AI concepts and clinical practice. These interactive web demos translate fundamental AI principles into visual, hands-on experiences designed for healthcare professionals with little to no AI background.

Rather than explaining AI through abstract theory or mathematical formulas, each demo uses real healthcare scenarios to teach concepts that matter when deploying AI in clinical settings.

---

## The Three Demos

### **Demo 1: Temporal Drift - When AI Models Go Stale**

AI models don't stay accurate forever. As patients age, medications change, devices update, and seasons shift, model performance gradually degrades. This demo shows a sleep apnea detection model dropping from 91% to 75% accuracy over 18 months without retraining.

**Interactive element:** Slide through 24 months and watch accuracy degrade in real-time, with alerts showing when retraining is needed.

[**→ Explore Temporal Drift Demo**](temporal-drift.html)

---

### **Demo 2: Human-AI Collaboration - Better Together Than Alone**

AI and clinicians make different types of errors. When you combine their predictions, you catch cases that either would miss working alone. This demo proves hybrid approaches outperform individual approaches—jumping from 80-82% to 92% accuracy.

**Interactive element:** Toggle between AI-only, Clinician-only, and Hybrid modes to see how diagnostic accuracy improves.

[**→ Explore Human-AI Collaboration Demo**](human-ai-diagnosis.html)

---

### **Demo 3: Sample Size & Confidence - How Much Data Is Enough?**

Predictions from wearable devices are noisy. Any single night's data is unreliable, but averaged over many nights, the true signal emerges. This demo shows how 7 days gives dangerously wide confidence intervals (±3.2), while 30+ days narrows uncertainty enough for clinical decisions.

**Interactive element:** Slide from 1 to 90 days of collected data and watch the confidence interval narrow from ±3.2 to ±0.9.

[**→ Explore Sample Size & Confidence Demo**](sample-size.html)

---

**Built to bridge the gap between computer science and clinical practice.**
