Frontend Worksheet

React and Tailwind Landing Page Recreation (Figma Reference)

Recreate a modern SaaS landing page using React and Tailwind CSS by observing a given design.

Design: 

This exercise focuses on:

Layout thinking

Component structuring

Spacing & positioning

Visual accuracy (not pixel perfection)

Tech Stack (MANDATORY)

React (Vite)

Tailwind CSS

JavaScript

Framer Motion (for animations)

Project Setup

npm create vite@latest landing-page -- --template react

cd landing-page

npm install

npm install tailwindcss @tailwindcss/vite

npm install motion lucide-react

Configure Tailwind according to Tailwind v4 + Vite docs.

Required Page Sections

Your landing page must include ALL of the following sections:

Hero Section

Features Section

Automation Section

Messaging Workflow Section

Creators / Use-case Section

Integrations Section

CTA + Footer Section

Component Structure (REQUIRED)

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

Hero Section Requirements

The hero section must include:

Dark green background

Central human illustration (transparent PNG)

Floating chat/message bubbles around the person

Subtle loop animation on chat bubbles

Text aligned left

Image aligned right

Animation Expectations

Chat bubbles float up & down

Slight delay difference between bubbles

Continuous loop animation

Spacing & Layout Rules

Use Tailwind spacing utilities (gap, px, py, space-y)

No inline styles

No magic numbers

Mobile → Tablet → Desktop responsive

Animation Rules

Use Framer Motion for:
Section fade-in

Vertical slide-up on scroll

Floating hero elements

Do NOT over-animate.


