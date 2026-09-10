# PROJECT MEMORY DOWNLOAD: SIH26092 - UdyamSetu AI
**Generated on:** 31 August 2026  
**Context:** Smart India Hackathon (SIH) 2026 | College Internal Selection Round  
**Team Profile:** 1st Year Engineering Team (6 Members)  
**Project Codename:** UdyamSetu AI

---

## 1. Problem Statement Master Context
* **Problem Statement ID:** `SIH26092`
* **Title:** AI-Driven Scheme Matching for Marginalized Entrepreneurs
* **Sponsoring Ministry:** Ministry of Social Justice and Empowerment (MoSJE)
* **Theme:** Smart Automation | **Category:** Software
* **Target Audience:** Scheduled Caste (SC), Backward Classes, and Marginalized Micro-Entrepreneurs with annual family income up to **₹5.00 Lakhs**.
* **Financial Scale:** Government apex corporations (NSFDC, NBCFDC, Stand-Up India) offer loans covering **up to 90% of project costs** at concessional 4%–6% interest rates and 25%–35% capital subsidies.

---

## 2. Decision Log & Strategic Justification
* **Why Selected Over Other 7 Shortlisted Statements:**
  1. *Avoided Crowded Clichés:* SIH26033 (Farmer Marketplaces) and civic portals are flooded with senior-year competitors. SIH26092 is a high-priority, non-clichéd MoSJE problem.
  2. *College Internal Quota Advantage:* Colleges nominate at most 1–2 teams per PS. This team will likely have zero direct internal competitors.
  3. *High Demo Impact:* Combining vernacular voice input in Indian dialects with instant financial DPR generation provides an immediate 60-second "Aha!" moment for evaluators.
  4. *1st-Year Feasibility:* Relies on modern pre-trained APIs (Bhashini, Web Speech, Gemini/LLM APIs, Tesseract OCR) rather than training models from scratch or requiring hardware.

---

## 3. The 4 Ground Realities & Why Existing Solutions Fail
1. **The Language/Literacy Barrier:** Existing portals (`myscheme.gov.in`, `jansamarth.in`) require reading and typing in complex bureaucratic English/Hindi.
2. **The "Detailed Project Report" (DPR) Barrier:** Banks legally mandate an economic feasibility report with cash-flow projections and DSCR. Informal rural artisans cannot create DPRs and face immediate bank rejection or pay ₹5,000–₹10,000 to touts.
3. **The 40%+ Document Defect Rejection Rate:** Over 50% of portal applications are rejected at bank branches due to trivial spelling discrepancies or expired certificates.
4. **Missing Document Dead-End:** Current portals reject ineligible users without explaining how to obtain missing certificates from local administrative bodies.

---

## 4. Our 4 Core Differentiating Pillars
1. **Vernacular Voice-First Intake:** Spoken Indian dialect recognition via Project Bhashini / Web Speech API (zero typing needed).
2. **Deterministic + RAG Scheme Matching:** Strict validation against official statutory criteria to eliminate AI hallucinations.
3. **Automated Micro-DPR Generator:** Dynamic unit-economics calculator generating bank-grade 1-page financial projection tables (CapEx, OpEx, profit margins, DSCR).
4. **AI Document Pre-Flight Scanner & Missing Doc Guide:** OCR scanner that flags errors before bank submission and provides step-by-step guidance for nearest CSC/Tehsil resolution.

---

## 5. Prototype Screen-by-Screen Specification
The working prototype is contained in `prototype_demo.html`:
* **Screen 1 (Aadhaar Sandbox Auth):** Simulated DigiLocker / UIDAI 6-digit OTP verification.
* **Screen 2 (Voice Intake):** Live waveform audio simulation with Hindi speech intake and real-time NLP entity extraction (Applicant, Trade, Capital, Income).
* **Screen 3 (AI Scheme Comparison):** 3 ranked scheme cards (NSFDC 98% Top Match vs PMEGP vs Mudra) highlighting loan coverage and capital subsidies.
* **Screen 4 (Document Pre-Flight & Missing Doc Resolver):** Status badges (Aadhaar verified, Income warning, Caste missing) + interactive CSC help guide.
* **Screen 5 (Automated Micro-DPR & E-Sign):** CapEx/OpEx breakdown, DSCR ratio (2.1x), and 1-click submission to Uttar Pradesh SC Finance & Development Corp.
* **Screen 6 (Live Application Tracking):** 4-stage lifecycle timeline (Submitted → SCA Review → Bank Appraisal → DBT Disbursal) + simulated citizen SMS webhook.

---

## 6. Generated Project Artifacts Manifest
All files reside locally in the project workspace:

| Artifact Name | Path | Purpose |
| :--- | :--- | :--- |
| **Interactive Prototype** | `scratch/prototype_demo.html` | High-fidelity interactive prototype with Auto-Play Demo mode. |
| **Official SIH PPT Deck** | `scratch/SIH26092_AI_Scheme_Matching.pptx` | 6-slide official SIH 2026 presentation deck. |
| **Alternative Agri PPT** | `scratch/SIH26032_Farmer_Procurement_Slot_Booking.pptx` | Backup deck for Mandi slot management. |
| **Alternative Metrology PPT** | `scratch/SIH26036_Online_Verification_Weighing_Instruments.pptx` | Backup deck for Legal Metrology. |
| **Master Blueprint** | `scratch/SIH26092_Master_Team_Blueprint.md` | Comprehensive technical blueprint and team lead briefing speech. |
| **Project Memory** | `scratch/PROJECT_MEMORY_SIH26092.md` | This persistent knowledge base file. |

---

## 7. 6-Member Role Division Matrix
* **Member 1 (Team Leader):** System architecture, presentation lead, PPT polish, judge Q&A.
* **Member 2 (Frontend Engineer):** UI/UX screens, component styling, tracking dashboard.
* **Member 3 (AI & Voice Engineer):** Bhashini/Web Speech integration, NLP prompt engineering.
* **Member 4 (Backend & DPR Automation):** REST API endpoints, automated DPR unit economics, PDF generation.
* **Member 5 (Document OCR Specialist):** Image upload, OCR text parsing, missing document guide logic.
* **Member 6 (Policy & Research Lead):** Government scheme guidelines dataset, financial unit economics, PPT data.

---

## 8. Pitch & Demo Presentation Script
* **Introduction (30s):** Introduce the MoSJE problem: thousands of crores allocated, but 40%+ rejected due to literacy, DPR, and document hurdles.
* **Architecture (60s):** Walk through the 4 pillars (Voice, RAG, Pre-Flight, Micro-DPR).
* **Live Demo (60s):** Launch `prototype_demo.html`, hit "Auto-Play Demo Walkthrough", and explain the 6 screens live.
* **Conclusion (30s):** Emphasize how this turns a 45-day bureaucratic ordeal into a 5-minute digital reality for rural Indian entrepreneurs.
