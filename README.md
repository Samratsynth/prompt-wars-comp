# 🇮🇳 Census 2027: India's First Digital Census
**Official Portal Prototype for "PromptWars x ADYPU" Hackathon**  
*Built by Principal Full-Stack Engineer & Elite UI/UX Designer*

---

## 🌟 Overview & Key Highlights
**Census 2027** is a production-grade, privacy-first, responsive single-page web application representing the digital transformation of India's national population and housing enumeration. 

Equipped with **Zero-Knowledge verification**, **BhashaSetu Voice GenAI**, **Niti-Drishti Policy Simulation**, **DPDP Act 2023** compliance, and the **Vriksha-Setu Green Digital Carbon Offset Tracker**, this portal sets the benchmark for citizen-first digital public infrastructure (DPI).

---

## 🚀 Key Feature Checklist

### 1. 🗺️ Two-Phase Interactive Architecture
- **Phase 1: Houselisting & Housing Census** (*April – September 2026*): Mapping building materials (walls, roofs, floors), sanitation, tap water (Jal Jeevan Mission), clean cooking fuel (LPG/PNG), electricity, digital assets, and transport ownership.
- **Phase 2: Population Enumeration** (*February 9 – 28, 2027*): Complete nationwide headcount assessing age cohorts, literacy, education levels, occupational classification (organized vs. unorganized sectors), mother tongues, migration, and fertility patterns.

### 2. 📅 State-Wise Interactive Schedule & Regional Map
- Live dynamic schedule viewer with instant search and regional zone filtering (*North, South, East, West, Central, North-East, UTs*).
- Real-time phase completion status badges, progress bars, household counts, and regional helpline contacts for all 36 States & UTs.

### 3. 📝 Two-Part Core Workflow
- **Part A: Guided Multi-Step Self-Enumeration Form**:
  - **Step 1**: Head of Household & Dwelling Details (Structure type, Wall/Roof materials, Water, Electricity, LPG, Broadband).
  - **Step 2**: Household Composition & Demographics (Dynamic addition/removal of family members with age, gender, relation).
  - **Step 3**: Socio-Economics & Literacy (Highest qualification, primary occupation, mother tongue).
  - **Step 4**: DPDP Act 2023 Consent, Review, and **ZK-Census Pass Generator with Green Eco-Citizen Badge**.
  - Animated exponential counter hook, input validation, audio read-out accessibility (TTS), and celebratory confetti upon submission.
- **Part B: Local/State Admin & Supervisor Control Room**:
  - Real-time submission feed with filters by Reference ID, State, and verification status.
  - **Differential Privacy Mask Toggle** ($\varepsilon=0.50$ Laplace Noise) protecting raw citizen PII.
  - Anomaly detection flaggers and CSV/JSON export capability.

### 4. 🌱 "Good for the World": Vriksha-Setu Green Carbon Offset Tracker
- **Live Environmental Metrics**:
  - **Paper Saved**: Calculates real-time A4 sheets conserved by replacing paper census forms ($8\text{ sheets/household} \to 1.48\text{ Crore+ sheets saved}$).
  - **$CO_2$ Avoided**: Tracks carbon emissions eliminated from physical logistics and printing (~$151\text{ Metric Tons } CO_2$).
  - **Water Conserved**: Fresh water saved from industrial paper pulping (~$34.2\text{ Lakh Liters}$).
  - **"1 Self-Enumeration = 1 Virtual Seed" Counter**: Dynamic progress bar connected with national urban forest initiatives (*Nagar Van Yojana*), awarding every citizen a verified **Eco-Citizen Green Seed Badge** on their downloadable ZK-Pass.

### 5. 🛡️ Privacy, DPDP Act 2023 & Misinformation Shield
- **5-Stage Zero-Knowledge Cryptographic Visualizer**:
  `Citizen Browser (AES-256 GCM)` ➔ `Homomorphic Masking` ➔ `ZK-Hash Digest` ➔ `National Vault (NIC Cloud)` ➔ `Audited Ledger`.
- **AI Myth Buster & Rumor Shield**: Clarifying citizenship questions, tax data confidentiality (Census Act 1948 Section 15), zero biometric uploads, and mathematical ZKP guarantees.

### 6. 📈 Meaningful Demographic Visualizations
- Real-time interactive charts powered by **Chart.js**:
  - **Demographic Age-Gender Pyramid** (Male vs. Female proportional age distribution).
  - **Amenities Radar Chart** (Urban vs. Rural penetration for Tap Water, LPG, Power, Broadband, Pucca structures, EV).
  - **Hourly Self-Enumeration Velocity Chart** (Tracking server throughput up to 31,800 submissions/hr).

### 7. 🌐 Multilingual Localization Engine
- Complete, seamless runtime switching across **English**, **Hindi (हिंदी)**, and **Marathi (मराठी)** covering all titles, labels, placeholders, alerts, and system dialogs.

---

## 🏆 Frontier Innovations

| # | Innovation | Technical Description |
|---|---|---|
| **1** | **🎙️ BhashaSetu AI Voice Engine** | Multilingual Speech-to-Form GenAI with Web Speech API recognition and NLU entity extractor. Enables semi-literate citizens to speak naturally in Hindi, Marathi, or English to auto-populate all census fields with visual confidence chips. |
| **2** | **🛡️ ZK-Census Offline Token** | Generates an offline-verifiable, tamper-proof QR code with cryptographic HMAC SHA-256 digest and Differential Privacy ($\varepsilon=0.5$). Field surveyors scan the QR code to verify records in 5 seconds without decrypting raw PII. |
| **3** | **🧠 Niti-Drishti Policy Simulator** | Interactive predictive policy dashboard with dynamic sliders (Urbanization %, Senior Citizen %, Clean Energy %, Female Workforce %). Projects 2030–2040 infrastructure needs with instant AI Strategic Policy Brief generation. |
| **4** | **🌱 Vriksha-Setu Green Offset** | Live paperless environmental calculator & community afforestation tracker linking digital self-enumeration with certified ecological impact. |

---

## 💻 Visual & UX Polish
- **Ambient Flowing Mesh Orbs**: Floating multi-colored ambient gradient spheres (`#FF9933` Saffron, `#10B981` Emerald, `#0284C7` Ashoka Blue) with `backdrop-blur-2xl` and fluid keyframe motion.
- **Modern Elevated Glassmorphism**: High-depth frosted cards (`bg-slate-900/72 border border-slate-700/60 backdrop-blur-xl shadow-[0_8px_32px_0_rgba(0,0,0,0.36)]`).
- **Interactive Micro-Animations**: Active glowing ring gradients, hover translations (`hover:-translate-y-1`), and smooth ripple effects on badges.
- **Animated Metrics**: Smooth exponential number counter hook for national enrollment velocity.

---

## 🏃 How to Run Locally

### Option 1: Direct File Launch
Double-click `index.html` to open directly in any modern web browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local HTTP Server (Recommended)
```bash
# Python
python -m http.server 3000

# Or Node.js
npx serve .
```
Then visit `http://localhost:3000` in your browser.
