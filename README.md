# Frontend Worksheet  
## React + Tailwind SaaS Landing Page Recreation

---
Recreate a **modern SaaS landing page** using **React** and **Tailwind CSS** by observing a **given visual reference image**.

---

## Design Reference
Design Link: https://saaslanding-phi.vercel.app/

You must rely on:
- Visual judgment
- Layout understanding
- Spacing intuition
- Component thinking

---

## This Exercise Focuses On

- Layout thinking
- Component structuring
- Tailwind spacing usage
- Animation logic
- Responsive design
- Real-world frontend workflow

---

##  Tech Stack (MANDATORY)

- **React** (Vite)
- **Tailwind CSS (v4)**
- **JavaScript only** 
- **Framer Motion** (for animations)

---

##  Project Setup

```bash
npm create vite@latest landing-page -- --template react
cd landing-page
npm install
npm install tailwindcss @tailwindcss/vite
npm install motion lucide-react
```
Configure Tailwind strictly following Tailwind v4 + Vite official docs.
---


## Required Component Structure (STRICT)

Your project **must follow this exact structure**:

```txt
src/
 ├─ components/
 │   ├─ Hero.jsx
 │   ├─ FeaturesSection.jsx
 │   ├─ AutomationSection.jsx
 │   ├─ MessagingWorkflow.jsx
 │   ├─ CreatorsSection.jsx
 │   ├─ IntegrationSection.jsx
 │   ├─ CTASection.jsx
 ├─ App.jsx
 ├─ main.jsx
 └─ index.css
```
---

## Required Page Sections
- Your landing page MUST include ALL sections below:

- Hero Section

- Features Section

- Automation Section

- Messaging Workflow Section

- Creators / Use-case Section

- Integrations Section

- CTA + Footer Section
---

## Hero Section Requirements
- The Hero Section must include:

- Dark green background

- Left-aligned text content

- Right-aligned illustration

- Human image (transparent PNG)

- Floating chat/message bubbles around the person

- Subtle looping animation on bubbles
---

## Hero Visual Rules
- Person image has NO background

- Chat bubbles are separate images

- Bubbles float independently

- Bubbles must overlap the hero area

- Use position: absolute with Tailwind utilities
---

## Animation Expectations
- Use Framer Motion for:

### Hero Section
- Chat bubbles floating up & down

- Different delays per bubble

- Continuous loop animation
---

### Other Sections
- Fade-in on scroll

- Slide-up motion

- One animation per section (keep it clean)

- Do NOT over-animate
---


## Styling Rules
- Use Tailwind default colors where possible

- Dark green hero background must be consistent

- Cards should use:
rounded-xl / rounded-2xl
shadow-sm
bg-white
---
