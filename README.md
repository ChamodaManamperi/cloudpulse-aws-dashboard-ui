# Travel Lanka – Smart Travel Planning Platform

> A cloud-driven travel platform concept that helps travelers explore Sri Lanka smartly, using **real-time weather**, personal preference, and (in future) optimized travel routes with cost awareness.

![Travel Lanka Hero](images/hero.png)

**Role:** UI/UX Designer & Front-end Developer
**Type:** Personal concept project
**Timeline:** Concept to working prototype
**Focus:** UI/UX Design · System Design · Cloud-Driven · Front-end Development · SaaS

🎨 **Figma Design:** [Add your Figma link here]
🌐 **Live Demo:** Private demo (hosted on Netlify, API key protected)

---

## About the Product

Travel Lanka is a cloud-based travel platform designed for people who want to explore Sri Lanka smartly.

The core idea is simple but powerful: help travelers choose **provinces and districts** based on **real-time weather** and personal preference, and later get an **optimized travel route** with cost awareness.

I designed the complete user flow and built a working prototype for the **Southern Province** as a proof of concept.

---

## The Problem

Most travel websites in Sri Lanka only show beautiful photos and generic information. Travelers still face these real problems:

- They don't know the current weather in different districts
- They waste time deciding which places to visit
- There is no smart system that helps them create an efficient travel order
- Planning feels scattered and stressful

I wanted to solve this by combining **beautiful design, real data, and smart logic**.

---

## The Solution

**Homepage:** Users swipe through all provinces of Sri Lanka and select any province they are interested in.

![Homepage](images/homepage.png)

**Province Page (Southern Province, fully designed):**

- Shows the main districts: **Galle, Matara, Hambantota**
- Displays **live weather** for each district (today + next 3 days)
- Users review the weather and click **"Add Destination"** based on their preference

![Southern Province Page](images/southern-province.png)

### Future Intelligent Layer (logic designed, not yet developed)

When a user adds multiple districts:

- The system automatically generates the **most efficient travel order**
- Shows all selected destinations in the user's profile
- Allows the user to choose hotels and re-adjust the plan according to their budget

This combination of **real-time data + user preference + intelligent routing** is the heart of the concept.

---

## What I Built

- Full high-fidelity design in Figma (Homepage + Southern Province)
- Interactive prototype
- Working live weather integration for 3 districts
- Responsive layout
- Clear user flow from province selection to adding destinations

---

## Features

- Clean, premium dark-themed UI
- Real-time weather using WeatherAPI (cloud data)
- Today + 3-day forecast for multiple districts
- Card-based layout with clear information hierarchy
- "Add Destination" action to build a personal travel list
- Responsive design for mobile and desktop
- Scalable structure (one code structure can support all 25 districts)

---

## Tech Stack

| Area | Tools |
|------|-------|
| UI/UX Design | Figma |
| Frontend | HTML, CSS, JavaScript |
| API | WeatherAPI (real-time & forecast data) |
| Tools | VS Code, Netlify (private demo) |

---

## Design Process & Thinking

1. **User goal first:** What does a traveler actually need when planning a trip to Sri Lanka? → *Weather information + easy selection + smart planning*
2. **Information architecture:** Homepage (province selection) → Province Page (district + weather) → Profile (saved destinations + optimized plan)
3. **Visual design:**
   - Dark, premium, travel-friendly interface
   - Province-specific theme color for each province page
   - Clear hierarchy so weather information is easy to scan
   - Soft cards and good spacing for mobile and desktop
4. **Interaction design:**
   - Swipe to explore provinces
   - Click an image or "Explore" button to open the province page
   - "Add Destination" creates a personal travel list
5. **Technical decision:**
   - Used **WeatherAPI** for real-time and forecast data
   - Built the Southern Province page with **HTML, CSS, and JavaScript**
   - Made the system **scalable** so it can support all 25 districts

![Design Process](images/design-process.png)

---

## Design System

A warm, premium dark palette (peach, tan, deep green, and brown tones on near-black) with a clear typographic scale from Heading 1 down to captions and small print.

![Design System](images/design-system.png)

---

## Challenges & Decisions

| Challenge | Decision |
|-----------|----------|
| Showing weather for multiple districts without a messy page | Clean card-based layout with today's weather highlighted and the next 3 days in smaller boxes |
| API key security | Kept the working prototype private and password-protected. In a real product, API calls would move to serverless functions |
| Scope of the concept | Fully designed and prototyped the Southern Province experience. Designed the full intelligent system logic but focused development on the most important part (weather + selection) |

---

## Key Learnings

- Good UI is not enough. Real data makes the experience useful.
- Thinking about the full system (even if not fully built) shows product thinking.
- Clear information hierarchy is critical when showing multiple data points (weather + description + actions).
- Security and privacy should be considered from the beginning.

---

## How to Run Locally

1. Clone this repository
```bash
   git clone https://github.com/your-username/travel-lanka.git
   cd travel-lanka
```
2. Get a free API key from [WeatherAPI](https://www.weatherapi.com/)
3. Add your key in `script.js`
```js
   const API_KEY = "YOUR_API_KEY_HERE";
```
4. Open `index.html` in your browser

> ⚠️ **Never commit your real API key.** For a production version, move the API calls to a serverless function (e.g. Netlify Functions) so the key stays on the server.

---

## Roadmap

- [ ] Extend weather support to all 25 districts
- [ ] Intelligent route ordering for selected destinations
- [ ] Cost awareness and budget-based plan adjustment
- [ ] Hotel selection and re-adjustable travel plan
- [ ] User profile with saved destinations
- [ ] Serverless backend to protect API keys

---

## Screenshots

| Homepage | Province Page |
|----------|---------------|
| ![Homepage](images/homepage.png) | ![Province](images/southern-province.png) |

---

## About This Project

This project is 100% my original idea. I wanted to create something that feels modern, useful, and uniquely Sri Lankan, a true cloud-driven travel experience. I'm excited to keep developing the intelligent routing and cost optimization features in the future.

**Designed with passion in Figma.**

🔗 [LinkedIn](https://www.linkedin.com/in/your-profile) · 🎨 [Figma](https://www.figma.com/your-profile)
