# aegis-soc-engine | AI-Driven Cyber Defense

**AEGIS** is a next-generation Security Operations Center (SOC) Engine that leverages dual-engine Artificial Intelligence to detect, analyze, and neutralize network threats in real-time.

---

## 💎 Executive Summary
Traditional security relying on static rules fails against modern "Zero-Day" attacks. AEGIS solves this by combining **Supervised Learning** (for known patterns) and **Unsupervised Anomaly Detection** (for identifying novel threats).

### Key Business Values:
- **Reduced False Positives**: AI-driven confidence scoring ensures analysts focus only on real risks.
- **Immediate ROI**: Out-of-the-box support for the MITRE ATT&CK framework.
- **Premium Visualization**: High-fidelity "Mission Control" dashboard for executive oversight.

---

## 🛠️ Technology Stack
- **AI Core**: Scikit-learn (Random Forest & Isolation Forest)
- **Backend**: Flask (Python)
- **Frontend**: Mission Control UI (HTML5, Vanilla CSS, Chart.js)
- **Data Source**: Optimized CICIDS-2017 Feature Set

---

## 🚀 Hosting & Deployment

### 1. Backend (AI Brain)
The backend is located in the `backend/` directory and is optimized for **Render**.
- **Root Directory**: `backend`
- **Build Command**: `pip install -r requirements.txt`
- **Start Command**: `python app.py`

### 2. Frontend (Dashboard)
The dashboard is located in the **Root Folder** and is optimized for **Vercel**.
- **Root Directory**: `./` (Root)
- **Build Settings**: Override all to "Empty" (Direct Static Hosting).

### 3. Docker (Recommended)
Run the entire stack with one command:
```bash
docker-compose up --build
```

---

## 🌩️ Free Hosting Recommendations

For a completely free "Mission Control" deployment, use these services:

### 1. Backend: [Render](https://render.com/)
- **Root Directory**: `backend`
- **Build Command**: `pip install -r requirements.txt`
- **Start Command**: `python app.py`

### 2. Frontend: [Vercel](https://vercel.com/)
- **Root Directory**: `./` (Empty)
- **Framework**: Other / Vite

---

## 📁 Repository Structure
```text
├── backend/         # Secure AI API Brain (Python/Flask)
├── index.html       # Mission Control Dashboard (Static)
├── main.js          # AI Connectivity & Logic
├── style.css        # Premium Visual Engine
└── vercel.json      # Master Routing Configuration
```

---

## 🛡️ Security & Simulation Disclaimer
The AEGIS SOC Engine is a **visual demonstration and education tool**. 
- **Mock Simulations**: All "Attacks" (SQLi, DDoS, etc.) are purely visual mocks. NO network traffic or packets are ever sent to any third-party websites typed by visitors.
- **Input Sanitization**: All visitor inputs are sanitized and length-limited on both the frontend and backend to prevent injection attacks.
- **Safe Purpose**: This platform is designed strictly for cybersecurity training and AI portfolio showcase.

---

Created with 🛡️ by the aegis-soc-engine Security Team.
