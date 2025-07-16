# 🌾 Farmer Platform: AI + Marketplace (No-IoT-First Approach)

A 6-month roadmap for a 5-member team to build a mobile-first platform that empowers farmers with AI-driven crop advice, disease detection, and a direct marketplace—delaying IoT integration until after launch.

---

## 👥 Team Roles

| Role               | Responsibility                                      |
|--------------------|-----------------------------------------------------|
| AI/ML Specialist 1 | Fertilizer & crop recommendation models             |
| AI/ML Specialist 2 | Plant disease detection via phone photos            |
| AI/ML Specialist 3 | Price prediction & marketplace AI                   |
| Web Developer      | App/website + marketplace                           |
| Flex Role          | Assist AI/ML or Web tasks as needed                 |

---

## 🚀 Phase 1: Planning & Foundation (Weeks 1–4)

### 🎯 Goal: Validate ideas and set up infrastructure

#### Week 1: Farmer Research
- Visit 3 local farms or conduct video calls
- Ask: “What’s your #1 tech problem?”
- Document pain points (selling crops, disease identification)

#### Week 2: Data Collection
- Crop prices: [AGMARKNET API](https://agmarknet.gov.in/)
- Soil data: ICAR Soil Health Card
- Disease images: PlantVillage dataset

#### Week 3: Tech Setup
- Create GitHub repository
- Build basic app skeleton (React Native)
- Set up Firebase (free tier)

#### Week 4: UI Design
- Sketch 3 key screens:
  - Home: "Scan Disease", "Sell Crops"
  - Marketplace: Crop listings like OLX
  - Profile: Farmer history

---

## 🧠 Phase 2: Core Development (Weeks 5–16)

### 🔬 Track A: AI Models

| Feature               | Timeline     | Owner         | Output Example                                      |
|-----------------------|--------------|---------------|-----------------------------------------------------|
| Fertilizer Recommender| Weeks 5–8    | AI/ML 1       | "For rice in Punjab, use urea: 50kg/acre"           |
| Disease Detector      | Weeks 9–12   | AI/ML 2       | Detects 5 common diseases via MobileNet             |
| Price Predictor       | Weeks 13–16  | AI/ML 3       | LSTM model for weekly price forecasts               |

### 💻 Track B: App & Marketplace

| Feature               | Timeline     | Owner         | Description                                         |
|-----------------------|--------------|---------------|-----------------------------------------------------|
| Basic App             | Weeks 5–10   | Web Dev + AI/ML| Login, disease scan, crop inventory                 |
| Marketplace           | Weeks 11–16  | Web Dev + AI/ML| Crop listings, buyer-seller chat, Razorpay payment |

---

## 📱 Phase 3: Testing & Launch (Weeks 17–24)

### Week 17–18: Alpha Test
- Share app with 10 farmer friends
- Fix critical bugs (e.g., photo upload crash)

### Week 19–20: Beta Launch
- Release on Play Store (1 district only)
- Run WhatsApp ads: “Sell crops directly!”

### Week 21–24: Monitor & Improve
- Collect top 3 complaints
- Example: Retrain price model with local data

---

## 🔧 Phase 4: IoT Integration (Months 6–8)

### Step 1: Prototype
- Budget: ₹4,000
- Components:
  - ESP32 microcontroller (₹600)
  - Soil moisture sensor (₹200)
  - Low-res camera (₹800)

### Step 2: Minimal Features
- Measure soil moisture
- Capture disease photos

### Step 3: Premium Testing
- Offer device to ₹199/month subscribers
- Compare IoT vs manual entries

---

## 📅 Key Milestones

| Month | Milestone                          |
|--------|------------------------------------|
| 1      | App prototype ready                |
| 3      | First AI models working            |
| 5      | 100 farmers using marketplace      |
| 6      | Revenue from premium features      |
| 8      | IoT rollout (if demand exists)     |

---

## 💡 Pro Tips

- *Start Small*: Launch in Punjab, focus on rice/wheat
- *Avoid IoT Risks*: Prove demand with software first
- *Monetization*:
  - Free: Basic app
  - ₹99/month: Price alerts + buyer contacts
  - ₹199/month: IoT device rental

---

## ✅ Week 1 Priority Checklist

- [ ] Talk to 5 farmers
- [ ] Download AGMARKNET price data
- [ ] Create GitHub repo
- [ ] Design homepage screen

---

## 💰 Estimated Costs

- *Total Budget*: ₹50,000 for 6 months
- Includes: Server, marketing, farmer training

---

## 📦 Project Philosophy

> “Launch fast, learn from farmers, build only what they need.”

---
