
 BruteBrains.com 

a puzzle-based, Firebase-powered, AI-integrated mental challenge platform. This project includes a React front-end, Firebase backend, admin tools, machine learning hooks, and the legendary `Conclogan` engine.

---

 Directory Structure

```
BruteBrains
├── public/                  # Firebase hosting root
│   └── index.html           # Static placeholder
├── src/                     # React frontend app
│   └── App.tsx              # App entry point (UI)
├── functions/               # Firebase Cloud Functions
│   └── index.ts             # Game logic, Conclogan brain, ML scoring
├── admin/                   # FireCMS or Admin Interface
│   └── README.md            # Admin guide
├── config/
│   └── firebaseConfig.ts    # Firebase SDK config (add your keys)
└── README.md                # ← You're here
```

---

## Features

- Puzzle Auth Engine** (Optional crypto-wallet tie-in)
- Conclogan ML Hook** – analyzes player decisions over time
- Time-Margin Logic** – adjusts based on player pace & struggle
- Minimal UI** – only 3 screens: `Game`, `Challenge`, `Board`
- Firebase Cloud Functions** for scoring, time limits, and updates
  Future-ready for TensorFlow.js or FireML integrations

---

How to Deploy

1. **Install Firebase CLI**
```bash
npm install -g firebase-tools
```

2. **Login to Firebase**
```bash
firebase login
```

3. **Init project (first time)**
```bash
firebase init hosting functions
```

4. **Deploy**
```bash
firebase deploy
```

---

Conclogan Logic (functions/index.ts)
Conclogan is an AI-driven logic engine that evaluates:
- Player intent and response patterns
- Puzzle success proximity
- Time stress scoring and bias detection

---

Admin Panel (admin/)
Use FireCMS, Firebase Console, or custom dashboards.
(Optionally powered via Supabase/Retool/Rowy in future releases.)

---

Roadmap
Firebase Function Structure
React Frontend
Conclogan Prompt Scaffold
ML training loop for puzzle adaptation
Leaderboard and A/B logic tweaks
Scratch-to-Reveal Puzzle UX

---

#Contribute?

This project is experimental, open-ended, and  smart by design. Want to test it, expand it, or plug in your own AI? Welcome aboard.

