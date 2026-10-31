# OA-Risk-Detection-NER
AI-Assisted Early Detection System for Osteoarthritis (OA) Risk Markers in North Eastern Region (NER)

[![Live Website](https://img.shields.io/badge/Live%20Demo-Website-0284c7?style=for-the-badge&logo=google-chrome&logoColor=white)](https://rajasree202006.github.io/OA-Risk-Detection-NER/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rajasree202006/OA-Risk-Detection-NER)
[![Streamlit Cloud](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://share.streamlit.io/)

---

## 🌐 Live Website

Access the fully functional live web application directly in your browser:
👉 **[https://rajasree202006.github.io/OA-Risk-Detection-NER/](https://rajasree202006.github.io/OA-Risk-Detection-NER/)**

Anyone can open this public link on any desktop, tablet, or smartphone to test the AI screening system, analyze gait parameters, simulate knee X-ray diagnostics, and download clinical reports.

---

## 📋 Project Overview

The **OA Early Detection System** is an AI-assisted clinical prototype designed to screen, quantify, and analyze early risk indicators of knee Osteoarthritis (OA). It incorporates:
1. **Patient Intake & Demographics**: BMI calculations, joint pain scores, and symptom duration.
2. **WOMAC Functional Questionnaire**: 5-point validated scoring for joint stiffness and daily mobility impairment.
3. **Quantitative Gait Biomechanics**: Spatiotemporal metrics (walking speed, stride length, cadence, step count, and gait variability).
4. **AI Computer Vision Radiograph Screening**: Deep learning assessment of joint space narrowing (JSW), marginal osteophyte detection, and Kellgren-Lawrence (KL Grade 0 to 4) grading.
5. **Integrated Clinical Risk Engine**: Multi-factorial risk scoring (Age, BMI, Pain, WOMAC, and Gait Biomechanics) categorized into Low, Moderate, and High Risk.
6. **Multilingual Voice Assistant**: Audio guidance in English, Tamil (தமிழ்), and Hindi (हिन्दी) via Web Speech API.
7. **Patient Records & Database**: Live filtering, cohort analytics, and CSV clinical report exports.

---

## 💻 Tech Stack

- **Frontend / Live Web**: HTML5, Modern Tailwind CSS, Canvas API, Chart.js, Lucide Icons, Web Speech API
- **AI & Data Science**: Python, Pandas, NumPy, Scikit-learn logic, Streamlit
- **Deployment**: GitHub Pages (instant worldwide serverless hosting) & Streamlit Community Cloud

---

## 🚀 How to Run Locally

### Option 1: Streamlit Python App
1. Clone the repository:
   ```bash
   git clone https://github.com/Rajasree202006/OA-Risk-Detection-NER.git
   cd OA-Risk-Detection-NER
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Streamlit:
   ```bash
   streamlit run app.py
   ```

### Option 2: Live Web App (Direct in Browser)
Simply double-click [`index.html`](index.html) or run a local static server:
```bash
python -m http.server 8000
```
Open [http://localhost:8000](http://localhost:8000).

---

## 🏥 Clinical Disclaimer

This is an academic research and early screening prototype for educational purposes. The calculated risk indicators and gait classification do not constitute a definitive medical diagnosis and should not substitute evaluation by an orthopedic specialist or licensed healthcare professional.
