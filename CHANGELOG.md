# Changelog

All notable changes to **SuperArmor PDF Generator** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [v1.1.0] - 2026-06-07
### Added
- **[AI Engine] Groq Integration:** Migrated to the Groq API as the primary cognitive engine. Uses `llama-3.3-70b-versatile` as the core model with multiple Llama fallbacks to handle daily limits.
- **[Computer Vision] Groq Vision OCR:** Switched from Tesseract.js to Groq Vision API (`meta-llama/llama-4-scout-17b-16e-instruct` or similar Llama Vision models) for high-accuracy exam scenario parsing.
- **[UI/UX] Groq Styling:** Styled PDF elements, page margins, status badges, and buttons with custom Groq-themed accents (`#f55036` branding color).
- **[Security] Secure local storage:** Obfuscates API keys locally with encryption-style XOR/Base64 masking before saving.

### Changed
- **[UI] Key Setup:** Replaced the multi-engine Claude/Gemini steps with a single Groq API key configuration step.

---

## [v1.0.0] - Initial Release
### Added
- **[AI Engine] Multi-LLM Setup:** Client-side integration supporting Anthropic Claude (`claude-sonnet-4-20250514`) and Google Gemini (`gemini-2.0-flash`).
- **[OCR] local OCR processing:** Integrated Tesseract.js for parsing MEB exam scenario charts client-side.
- **[PDF Generator] jsPDF & AutoTable:** Advanced frontend-only PDF generator implementing customized themes, page alignments, warning blocks, reflex zones, and zero-hour sheets.
- **[Integration] YouTube Transcripts:** Step-by-step video transcript import and validation.
