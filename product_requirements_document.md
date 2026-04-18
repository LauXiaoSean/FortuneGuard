# Project 2030: FortuneGuard (守卫灵) – PRD

## 1. Problem Statement
- Malaysia lost RM1.3B to scams in 2023.
- Current apps: reactive, boring, anxiety‑inducing.
- High “Apathy Friction” → low engagement, especially among elderly users.

## 2. Product Vision
- Build a culturally resonant digital guardian.
- Prevent financial loss via:
  - **Daily Blessings** (positive UX hook).
  - **Automatic Neutralization** (scam blocking/reporting).

## 3. Target Audience
- **Primary:** Elderly, rural, non‑tech‑savvy (high risk, low reporting).
- **Secondary:** Gen Z & Millennials (gamified, low‑friction security).

## 4. Functional Requirements
**FR1: Automatic Awareness (Bagua Mirror)**
- Background scanning via Android Accessibility Services.
- Detect suspicious patterns (URLs, APK prompts).
- On‑device triage with Gemini Nano (privacy‑preserving).

**FR2: Daily Blessing (UX Hook)**
- Every 24h, generate personalized blessing via Gemini 1.5 Flash.
- Blessing synthesizes prior day’s logs into BaZi metaphors.  
  - Example: “Your Water element is strong; no phishing waves reached your shore.”

**FR3: Seal the Wealth Palace (Action)**
- Auto‑report confirmed scams to NSRC (997).
- Entity extraction: scammer name, bank account, phone number.

## 5. Technical Stack
- **Core AI:** Gemini 1.5 Flash (Cloud) + Gemini Nano (Edge).
- **Cloud:** Vertex AI (multimodal analysis).
- **Backend:** Firebase (Auth, Firestore encrypted logs, Cloud Functions for NSRC reporting).
- **Frontend:** Flutter (Android/iOS, national reach).

## 6. Success Metrics
- Detection latency: < 3s.
- User retention: > 60% D30.
- Reporting efficiency: 90% faster NSRC filing.
