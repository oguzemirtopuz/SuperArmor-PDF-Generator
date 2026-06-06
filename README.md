<div align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Architecture-Serverless-blue?style=for-the-badge" alt="Architecture">
  <img src="https://img.shields.io/badge/AI-Claude%20%7C%20Gemini-8E75C2?style=for-the-badge" alt="AI Engine">
  <br>
  <h1>🛡️ SuperArmor PDF Generator</h1>
  <p><b>An Autonomous, AI-Driven Exam Preparation Ecosystem for Elite Students</b></p>
</div>

---

## 🚀 The Vision

**SuperArmor PDF Generator** is a serverless, zero-latency front-end application designed to completely automate and optimize the exam preparation process. Built entirely on client-side technologies (HTML, CSS, JavaScript) and utilizing advanced AI APIs, it takes unstructured data (YouTube transcripts, MEB scenario matrices via OCR) and engineers a flawless, highly structured, and pedagogically sound "Super Armor" PDF note.

No servers, no databases, no latency. Just pure architectural efficiency converting raw knowledge into an elite study asset.

---

## 🛠️ Technological Architecture

*   **Core Logic:** Vanilla HTML, CSS3, and ES6 JavaScript.
*   **Cognitive Engines:** Anthropic Claude (`claude-sonnet-4-20250514`) & Google Gemini (`gemini-2.0-flash`) via an abstracted AI provider layer.
*   **Computer Vision (OCR):** Tesseract.js (Frontend implementation, no backend needed).
*   **Document Generation:** jsPDF & jsPDF-AutoTable for dynamic, styled client-side PDF generation.
*   **Security Paradigm:** Ephemeral API key storage via `localStorage`—keys never leave the user's browser.

---

## 🧠 The "Super Armor" Protocol

The generated PDFs adhere to a strictly optimized pedagogical structure:
1.  **Strategic Overview:** Exam scope and question distribution matrix.
2.  **Concept Mapping:** Tabular breakdown of critical formulas and core terminology.
3.  **Scenario-Aligned Q&A:** Anticipated questions matching the exam scenario, complete with step-by-step reasoning.
4.  **85+ Trap Zones (Red Flags):** Identification of high-risk areas where students typically lose points.
5.  **Reflex Strategies (Green Zones):** Anticipating teacher behavior and pre-programming reflex responses.
6.  **Zero-Hour Review:** A condensed, high-density table for the final 30 minutes before the exam.

---

## ⚙️ Operational Workflow

1.  **Configure Cognitive Engine:** Select between Claude or Gemini and input your API key securely.
2.  **Ingest Raw Data:** 
    *   Upload the MEB exam scenario image (processed instantly via Tesseract.js).
    *   Paste NotebookLM video transcription summaries.
3.  **Data Validation:** Verify and edit the parsed OCR table (Topic, Code, Question Count).
4.  **Generate & Deploy:** Trigger the AI pipeline. The system constructs the prompt, parses the structured JSON response, and dynamically renders the stylized PDF for immediate download.

---

## 📐 Aesthetic Specifications (PDF)

The output is engineered to be visually striking and highly readable:
*   **Headers & Themes:** `#1a1a2e` (Deep Navy) for absolute focus.
*   **Warning Zones:** `#e94560` (Vibrant Red) borders with `#fff3f3` backgrounds for 85+ Traps.
*   **Reflex Zones:** `#1a6b3c` (Forest Green) borders with `#f0fff6` backgrounds for strategic insights.
*   **Question Blocks:** `#f0f8ff` (Ice Blue) to separate active problem-solving from passive reading.

---

<div align="center">
  <i>"Discipline in study, absolute automation in preparation."</i>
</div>
