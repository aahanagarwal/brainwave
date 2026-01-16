# 👵👴 Saaya (साया)

### Your Digital Grandson: AI-Powered Companionship & Assistance on WhatsApp

**Saaya** is a comprehensive AI companion designed specifically for the elderly, living entirely within the interface they trust most: **WhatsApp**. It bridges the digital divide by turning complex apps (Uber, Zomato, Banking) into simple, natural conversations, all while ensuring safety through a novel "Human 2FA" system.

---

## 💡 The Problem

The digital world is moving too fast for the elderly.

1. **UI/UX Barriers:** Modern super-apps are cluttered and confusing for seniors.
2. **Financial Vulnerability:** Seniors are prime targets for OTP scams and financial fraud.
3. **Loneliness:** The lack of personalized interaction leads to isolation.

## 🚀 The Solution: Saaya

Saaya acts as a "Digital Grandson." It is an intelligent agent that lives in their WhatsApp contacts. It handles bookings, payments, and loneliness with the familiarity of a family member.

### ✨ Key Features

#### 1. 🗣️ Natural Language Actions (The "Agent")

No more navigating menus. The user simply types or speaks: _"I want to go to the Hanuman Temple."_

- **Contextual Awareness:** Saaya asks relevant follow-ups (When? Which temple?) naturally.
- **Service Integration:** Automatically interfaces with **Uber/Ola** APIs to book rides or **Blinkit/Zomato** for groceries/food without the user leaving WhatsApp.

#### 2. 🛡️ Integrated Wallet with "Human 2FA"

We re-invented safety for senior payments.

- **The Concept:** When a senior initiates a payment (e.g., paying for the cab), the transaction is paused.
- **The Approval:** A notification is sent to their designated "Assignee" (Son/Daughter).
- **The Execution:** Once the assignee approves, the transaction processes. This empowers independence while eliminating the risk of fraud or accidental transfers.

#### 3. 🎙️ Hyper-Personalized AI (Voice Cloning)

- **Familiarity:** Saaya uses voice cloning technology to reply in the voice of a loved one (e.g., their grandson or daughter), making the AI feel less robotic and more comforting.
- **Multimodal:** Supports full Speech-to-Text (STT) and Text-to-Speech (TTS).

#### 4. 🩺 Health Sentinel & Context Awareness

- **Audio Analysis:** The AI analyzes voice notes for background context and health cues.
- **Example:** If the user is coughing while sending a message, Saaya detects it and asks, _"I noticed you are coughing, Bauji. Should I order some syrup?"_

#### 5. 🤝 The "Saathi" App (Companion App)

A separate mobile application for gig-workers or volunteers.

- **Generic Requests:** If the senior needs something not covered by APIs (e.g., "Help me fix the bulb"), the request is broadcast to the **Saathi** app.
- **Uber-style Model:** Verified "Saathis" can accept the request and assist.

---

## 🛠️ Tech Stack

- **Interface:** WhatsApp Business API (Twilio / Meta)
- **Backend:** Node.js / Express / Python
- **AI Core:**
- **LLM:** OpenAI GPT-4o / Gemini (for conversation and intent detection).
- **Voice:** ElevenLabs (Voice Cloning & TTS), Whisper (STT).

- **Database:** MongoDB (User profiles, Transaction logs).
- **Mobile App (Saathi):** React Native / Flutter.
- **Integrations:** Uber API, Payment Gateway (Razorpay/Stripe).

---

## 📸 Workflow

1. **User (Grandpa):** Sends voice note on WhatsApp: _"Book a cab to the clinic."_
2. **Saaya (Backend):** Transcribes audio -> Detects Intent -> Checks Uber Price.
3. **Saaya:** Replies: _"Uber is ₹250. Should I book?"_
4. **User:** _"Yes."_
5. **Saaya (Security):** Sends alert to **Assignee (Son)**: _"Dad wants to book a cab for ₹250. Approve?"_
6. **Assignee:** Clicks "Approve."
7. **Saaya:** Books cab -> Shares live location with both Grandpa and Son.

---

## 🔮 Future Roadmap

- **SOS Fall Detection:** Integrating with wearable API data.
- **Medicine Reminders:** OCR scanner for prescription slips to auto-set reminders.
- **Vernacular Support:** Full support for regional dialects (Hindi, Marathi, Tamil, etc.).

---
