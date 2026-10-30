# 📦 COD Return-to-Origin (RTO) Predictor & Instant UPI Pre-Pay Engine

> **Interactive Frontend Prototype tackling Razorpay Fix-My-Itch Problem Statement #4**  
> *Engineered by [Abhay Vinod](https://github.com/abhayvinod)*

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)
![React 19](https://img.shields.io/badge/React-19-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)
![Tailwind CSS v4](https://img.shields.io/badge/Tailwind-CSS_v4-38bdf8?logo=tailwindcss)
![Vite](https://img.shields.io/badge/Vite-6-646cff?logo=vite)

---

## 🎯 The Problem
In Indian D2C commerce, 60%+ of tier-2/3 orders are Cash on Delivery (COD). **30% to 40% of these bounce back as Return-to-Origin (RTO)** because shoppers refuse parcels at doorstep or provide bogus addresses. D2C brands burn **₹120–₹160 in non-refundable courier freight** on each failed shipment.

---

## 💡 The Solution
An intelligent checkout gatekeeper with predictive risk telemetry:
- 📊 **Real-time 0–100 RTO Risk Scoring:** Evaluates pincode tier, NLP address completeness, and buyer phone historical behavior.
- 🛡️ **Dynamic COD Handling Fee:** High-risk orders are discouraged with a nominal risk protection charge.
- ⚡ **1-Click UPI Conversion Incentive:** Offers an instant ₹150 discount to convert risky COD shoppers into verified prepaid orders.
- 🚚 **Delivery Outcome Simulator:** Compares doorstep success vs. RTO courier burn in real time.

---

## 🛠️ Tech Stack & Architecture
- **Framework:** React 19 + TypeScript
- **Styling:** Tailwind CSS v4
- **Icons:** Lucide React
- **Micro-Animations:** Canvas Confetti
- **Build Tool:** Vite 6

---

## 🚀 Local Development

```bash
git clone https://github.com/abhayvinod-web/cod-rto-risk-engine.git
npm install
npm run dev
