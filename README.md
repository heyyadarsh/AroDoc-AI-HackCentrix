# 🏥 AroDoc AI - HackCentrix Submission

**AroDoc AI** is a medical triage assistant powered by **Google Gemini 1.5 Flash**. It solves the problem of delayed healthcare intervention by categorizing symptoms into intuitive Risk Levels (Green/Yellow/Red).

### 🚀 Key Features
* **AI-Powered Triage:** Instant symptom analysis using Google's Generative AI.
* **Lifestyle Prescriptions:** Auto-generates Nutrition and Recovery advice.
* **Emergency Protocol:** Dedicated SOS module for critical 'Red Risk' scenarios.
* **Secure History:** Dashboard to track past health records.

### ⚠️ Security Note for Judges
To prevent unauthorized usage, the **API Key has been removed** from `src/App.jsx`.
* The app includes a **"Backup Demo Mode"** that will automatically run if no key is detected, ensuring the prototype is fully testable without crashing.
* To enable live AI, paste a valid `GEMINI_API_KEY` in `App.jsx`.
