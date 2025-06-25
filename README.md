> **⚠️ Heads-up:**  
> This README was auto-generated with AI and serves as a **temporary placeholder**.  
> Expect significant updates once our full documentation is ready.

# My Metric Health

Welcome to the **My Metric Health** codebase.  
Our mission is to help clinics, clinicians, and patients manage care more efficiently with secure, real-time data and AI-powered insights.

---

## ✨ Key Features
| Area | Highlights |
|------|------------|
| **Mobile App** | • Symptom & assessment reminders<br>• Push notifications for assigned tasks |
| **Web Portal** | • Multi-clinic & multi-clinician support<br>• Granular roles: Admin · Member · LimitedClinician · DataViewer<br>• De-identified analytics view |
| **Security** | • HIPAA-oriented architecture<br>• PHI encrypted at rest & in transit |
| **AI / Automation** | • Personalized task schedules<br>• Productivity tooling with Cursor & CI workflows |

---

## 🛠 Tech Stack
| Layer | Tech |
|-------|------|
| Frontend | React + TypeScript, Tailwind, Expo (mobile) |
| Backend  | Node.js (Express), PostgreSQL (RLS + enums) |
| Infra    | AWS (Amplify, Lambda, RDS), GitHub Actions CI/CD |

---

## 🚀 Quick Start
```bash
# 1. Clone
git clone https://github.com/MyMetricHealth/my-metric-health.git
cd my-metric-health

# 2. Install dependencies
pnpm install    # or yarn / npm

# 3. Environment
cp .env.example .env   # fill in secrets

# 4. Run services
pnpm dev              # starts web + API (concurrently)
expo start            # mobile app (if using Expo)
