# MindHaven-Mental-Health-Support-Tools
# MindHaven — Clickable Prototype

This is a static, offline demo that showcases core flows:
- GAD-7 self-assessment with real-time scoring
- Suggested coping plan
- “Hani” supportive chatbot with basic rule logic + crisis detection
- Simple counselor dashboard with anonymized notifications and a toy heatmap
- Local-only storage (no backend)

## How to Run
1. Put `index.html` and `README.md` into a folder (e.g., `mindhaven-prototype`).
2. Double-click `index.html` to open it in Chrome/Edge/Firefox.
3. Accept the consent notice, then try:
   - Complete the assessment and view results.
   - Open the chat and type phrases like “I feel stressed”, “hopeless”.
   - Check the dashboard for notifications.

## Customize Quickly
- Change the app name, colors, or text in `index.html` (search for “MindHaven”).
- Replace demo phrases / coping tips in the JavaScript section (`planFor()` and `crisisWords`).
- Replace the demo alerts with real actions later.

## MVP Roadmap
1. **Auth & Roles:** Student/counselor login (Firebase Authentication).
2. **Database:** Store assessments (Firestore) with Security Rules.
3. **Real Chatbot:** Connect to an LLM API with a safety layer and escalation.
4. **Dashboards:** Per-counselor case list + follow-up tracking.
5. **Compliance:** Consent screens, data retention policy, audit logs.
6. **Deployment:** Host on Netlify/Vercel (static) and add serverless functions as needed.

## Safety Notice
This demo is not a medical device and must not be used for clinical purposes. In emergencies, contact local emergency services.
