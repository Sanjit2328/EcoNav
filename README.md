# 🚢 ECONAV – AI-Powered Sustainable Maritime Routing
## 🔗 WEB APP LINK:
https://your-econav-link.vercel.app 

## 🧭 BRIEF INTRO:
EcoNav is an AI-powered web platform designed to revolutionize maritime navigation through sustainable route optimization. It provides real-time, AI-driven marine routing that minimizes fuel consumption, reduces carbon emissions, and enhances safety by factoring in weather, ocean currents, and maritime regulations. With both online and offline capabilities, EcoNav empowers maritime operators to make environmentally responsible and cost-efficient decisions.

## 🚨 PROBLEM STATEMENT:
**Environmental Challenges in Maritime Industry:**
The maritime industry contributes nearly 3% of global CO₂ emissions.

Inefficient routes lead to excessive fuel consumption, higher costs, and increased pollution.

**Lack of Smart Routing Tools:**
There’s a scarcity of integrated platforms that optimize marine navigation using AI while promoting sustainability.

**🔄 WORKFLOW DIAGRAM:**
![Screenshot 2025-07-08 085826](https://github.com/user-attachments/assets/31441507-6e0c-4061-b4d0-b7bcf895aa1c)

##🛠 TECH STACK:
**Frontend (Client-Side)**
React.js + Next.js + Tailwind CSS

Responsive UI for route visualization, dashboards, and offline map viewing.

Interactive elements for selecting route type (fastest, fuel-efficient, safe).

Recharts / Leaflet / Mapbox GL JS:

To visualize optimized maritime routes, ship position, and hazard zones.

**Backend (Server-Side)**
Next.js API Routes + Node.js (Optional):

Real-time API calls to weather/marine data providers.

AI route recommendation logic.

Python ML API (Flask/FastAPI):

Handles route optimization using RL algorithms (PPO, DDPG).

Processes offline and historical data for local predictions.

MongoDB Atlas:

Stores user route history, environmental savings, and offline route files.

**AUTHENTICATION & SECURITY**
NextAuth.js + JWT:

Secure login system with Google/Auth providers.

Route preferences and tracking history are saved per user securely.

**☁️ CLOUD HOSTING & DEPLOYMENT**
Vercel + Render:

Frontend deployed on Vercel.

Python ML API served through Render.

Offline route files served via serverless functions.

**🔔 PUSH NOTIFICATIONS**
Firebase Cloud Messaging (FCM):

Alerts about weather changes, hazard zones, or upcoming fuel-saving tips.

**📊 ANALYTICS & MONITORING**
Google Analytics + Vercel Insights + Sentry:

Track how users interact with route options.

Monitor performance and detect runtime issues early.

**✅ TESTING & QUALITY ASSURANCE**
Jest + Cypress + ESLint + Prettier:

Ensure route calculations are accurate and interface is responsive across devices.

**🔁 CI/CD PIPELINE**
Vercel CI + GitHub Actions:

Push to GitHub triggers automatic deployments.

Optional test runs on Actions for AI backend.

## ✨ NOVELTY
🌍 AI for Maritime Sustainability
EcoNav’s biggest innovation lies in applying Reinforcement Learning and real-time data integration to maritime logistics. It dynamically optimizes for:

Reduced emissions

Fuel savings

Hazard avoidance

Regulatory compliance

**👥 Offline Support + Scalable Architecture**
Offline GPS-based tracking for ships with low connectivity.

Downloadable GPX/KML routes.

Scalable architecture supports both large shipping fleets and small independent boats.

**🧑‍💻 USER-CENTRIC DESIGN**
📱 Intuitive Interface
Clean, easy-to-navigate UI with route selection options.

Real-time updates, download buttons, fuel-saving metrics.

**🧩 Personalized Routes**
Based on user history, ship type, and mission needs (commercial, cargo, patrol, etc.).

**♿ Accessibility**
Simple navigation, dark/light modes, and mobile support.

**⏱ REAL-TIME FEEDBACK**
“This route saves 18% fuel.”

“Carbon footprint reduced by 350 kg.”

“Avoided storm zone detected – safe reroute recommended.”

These insights motivate users, help fine-tune decisions, and promote green shipping behavior.

## 🚀 SOLUTION SUMMARY
EcoNav provides an end-to-end solution for eco-friendly maritime navigation. It combines powerful AI, live environmental data, and user-centric features to promote sustainability in the shipping industry.

**Key Features:**
AI-Based Route Optimizer

Fuel-efficient, safe, and regulation-compliant route generation using RL.

Offline Navigation Module

Download routes, view maps offline, sync GPS data when online.

Environmental Savings Dashboard

Track emissions saved, fuel usage reduced, impact visualized.

Sustainable Shipping Tips & Alerts

Real-time eco-tips, alerts on high-risk zones, route suggestions.

**🌱 VISION**
EcoNav envisions a future where shipping becomes smarter, greener, and safer. By enabling ships to navigate with intelligence, EcoNav supports:

Sustainable Development Goals (SDG 7, 9, 13, 14)

Greener oceans

Empowered maritime decision-making

## 📸 OUTPUT SNAPSHOTS
![Screenshot 2025-07-08 090506](https://github.com/user-attachments/assets/c3e69ad9-a3ba-413c-8f04-87933c0af64e)
![Screenshot 2025-07-08 090441](https://github.com/user-attachments/assets/6fed85dc-9b29-4151-bd4d-f520e05a9b30)
![Screenshot 2025-07-08 090417](https://github.com/user-attachments/assets/0ef76eda-09dc-486c-be93-3029a4b72d80)
![Screenshot 2025-07-08 090359](https://github.com/user-attachments/assets/9dc06b09-0964-46d8-9d1b-2940b98b579e)
![Screenshot 2025-07-08 090312](https://github.com/user-attachments/assets/8e1d6b06-2274-4fcc-bd59-2b25e1936cc9)
![Screenshot 2025-07-08 090247](https://github.com/user-attachments/assets/c66936fe-73f1-463c-b496-b27cca065a3b)
