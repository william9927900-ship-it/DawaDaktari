# DawaDaktari — Swahili-First AI Triage for Kenyan Dispensaries

> Built for Meta Global AI Developer Hackathon 2026

**Problem:** Level 2/3 dispensaries in Kenya handle 200+ patients/day with 1 nurse. Triage forms are in English, patients speak Swahili/Sheng. Delays = deaths.

**Solution:** DawaDaktari takes symptoms in Swahili/Sheng/English (text or voice) and returns:
- Triage level: GREEN / YELLOW / RED
- Top 3 differentials
- Next questions to ask (per Kenya Clinical Guidelines)
- Referral advice
- Swahili voice output for patients

**Stack:**
- Python + Flask
- Meta Llama 4 via Meta Model API
- Meta Speech-to-Text
- Twilio WhatsApp API (no app needed)
- Offline cache for low-connectivity

**Prototype: AfyaScan (precursor)**
Tested on 100+ cases from clinical rotations at Egerton University. Flagged 87% of RED cases correctly vs clinician review.

**Roadmap for Hackathon:**
- Migrate to Llama 4 for better Swahili reasoning
- Add offline PWA
- Pilot in 3 dispensaries in Nakuru County

Author: William — Clinical Officer / PharmTech, Egerton University, Nairobi, Kenya.