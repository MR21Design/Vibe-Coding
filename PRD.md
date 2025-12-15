# Product Requirements Document (PRD)

## Header

* **Project Name:** Milankumar Ramoliya – Personal Portfolio Website
* **Date:** December 2025
* **Author:** Milankumar Ramoliya
* **Version:** v1.0
* **Short Pitch:** A visually engaging, interactive personal portfolio showcasing UX, animation, and 3D design work, crafted to impress judges and peers during a UX/Design hackathon.
* **Relevant Links:**

  * Existing Portfolio (Framer): [https://milankumarramoliya.framer.website/](https://milankumarramoliya.framer.website/)
  * Platform: Jekyll (Academic Pages template)

---

## 1. Core Context

### Problem

Judges and recruiters often have limited time to review portfolios. Traditional static portfolios fail to communicate a designer’s personality, motion skills, and interactive thinking quickly and memorably.

### Solution

Create a fast, visually striking portfolio website that blends UX clarity with motion, 3D visuals, and subtle interactivity to communicate skill, personality, and craft within seconds.

### Target Users

* Hackathon judges
* UX/UI designers and peers
* Creative developers
* Recruiters and academic reviewers

### Primary Use Cases

* Quickly understand who Milankumar is and what he specializes in
* Explore featured projects with visual and interactive depth
* Assess design, animation, and interaction skills
* Access background, skills, and contact information

### North-Star Metric

* **Judges can understand the designer’s profile and key skills within 30 seconds**

### Non-Goals

* Blogging platform
* CMS-heavy content editing
* E-commerce or client booking system

---

## 2. UX Foundations

### Personas

**Hackathon Judge**

* Goal: Evaluate creativity, UX thinking, and execution quickly
* Behavior: Skims, scrolls fast, focuses on visuals and clarity

**Recruiter / Mentor**

* Goal: Assess potential and skill depth
* Behavior: Reviews projects, reads case summaries, checks polish

### Key Insights / Pain Points

* First impression matters more than completeness
* Motion and interaction strongly influence memorability
* Overloaded text reduces engagement

### Experience Principles / “Vibe”

* Playful but professional
* Calm, cool, and confident
* Motion with purpose (never decorative only)

### Accessibility & Inclusion Requirements

* WCAG AA color contrast
* Keyboard navigability
* Reduced-motion support for animations
* Readable typography

### High-Level Journey

Landing → Hero intro → Selected works → Project deep dive → About → Contact / links

---

## 3. Scope & Priorities

### MVP (V1) Goals

* Clear personal brand and role
* Showcase 2 strong portfolio projects
* Lightweight animations and interactions
* Fast loading and responsive design

### Out of Scope

* Multiple language support
* Large project archive
* Advanced backend features

### Assumptions & Risks

* Assumes judges view on modern browsers
* Risk of overusing animation impacting performance

---

## 4. Tech Overview

### Frontend

* Jekyll (Academic Pages)
* HTML, SCSS, JavaScript

### Backend

* Static site (no backend logic)

### Database

* None

### APIs / Integrations

* Optional: Three.js for 3D embeds
* Optional: Lottie for animations

### Deployment

* GitHub Pages

### Security / Privacy

* No user data collection
* External links clearly indicated

---

## 5. Feature Modules

### 5.1 Hero Section (P0)

**User Story:** As a visitor, I want to instantly understand who the designer is and what they do.

**Acceptance Criteria:**

* Displays name, role, and short intro
* Includes subtle motion or animation
* Strong visual hierarchy

---

### 5.2 Portfolio Projects (P0)

**User Story:** As a visitor, I want to explore featured projects and understand their creative value.

**Acceptance Criteria:**

* Two featured projects displayed prominently
* Each project includes visuals, short description, and tools used
* Hover or scroll-based interactions

**Projects:**

* Space War – Audio-video interactive project
* The Forgotten Vault – 3D game environment project

---

### 5.3 About Section (P1)

**User Story:** As a visitor, I want to learn about the designer’s background and personality.

**Acceptance Criteria:**

* Includes personal bio with friendly tone
* Mentions institution (THI)
* Highlights interests (animation, 3D, gaming, cricket)

---

### 5.4 Contact & Links (P1)

**User Story:** As a recruiter or judge, I want to quickly find contact and external profiles.

**Acceptance Criteria:**

* Email or contact link
* Social / portfolio links
* Clear CTA

---

## 6. IA, Flows & UI

### Main Screens

* Home
* Project Detail Pages
* About

### Key Flows

Home → Project → About → Contact

### Design Tokens / Components

* Cool and natural color palette
* Modern sans-serif typography
* Card-based project layout

### Localization / Tone

* English with friendly, approachable tone

---

## 7. Interactive Features

* Scroll-based animations
* Hover effects on projects
* Optional 3D embeds or animated previews
* Micro-interactions for feedback

---

## 8. Quality

### Testing Requirements

* Cross-browser testing (Chrome, Firefox, Safari)
* Mobile and tablet responsiveness

### Accessibility Checks

* Contrast validation
* Keyboard navigation

### Performance Targets

* First meaningful paint under 2s
* Optimized media assets

---

## 9. Metrics & Analytics

### KPIs

* Time to first scroll
* Project section engagement
* Average session duration

---

## 10. Launch & Operations

### Environments

* Local development
* Production (GitHub Pages)

### Rollout Plan

* Final QA
* Hackathon submission

### Support & Maintenance

* Content updates via Markdown
* Periodic project refresh

---

## 11. Success Criteria

* Judges can understand skills and personality quickly
* Portfolio feels memorable and polished
* Clear alignment between UX, animation, and 3D work
* Positive feedback during hackathon reviews
