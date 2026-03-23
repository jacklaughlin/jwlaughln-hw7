# STANDARDS.md
## BAIS:3300 - Digital Product Management · Module 8 | Personal Landing Page

## 1. Project Overview
This project is a personal professional landing page for Jack Laughlin, a Business Analytics student at the University of Iowa targeting data analyst roles and future law school opportunities. The site is designed for recruiters and admissions representatives in the Midwest to better understand his skills, leadership, and project experience beyond a traditional resume. Success is defined by generating recruiter and admissions interest, including interviews and professional outreach.

---

## 2. Technical Standards
These rules apply to every file in this project without exception.
**Languages and versions:**
- HTML5 — use semantic elements throughout: `<header>`, `<main>`, `<section>`,
`<article>`, `<footer>`, `<nav>`
- CSS3 — all styles must be written in `css/stylesheet.css`; no inline `style=""`
attributes; no `<style>` tags in any HTML file
- HTML5 and CSS3 code must pass validation
**Folder structure:**
<pre>
/your-website-project (Root Folder)
├── index.html
├── /css
│ └── stylesheet.css
├── /js
│ └── scripts.js
├── /images
│ └── headshot.jpg
</pre>
**Framework:**
- [Delete one of the following options:]
- No framework — vanilla CSS only
- Bootstrap 5.3 loaded via CDN in the `<head>` of `index.html`
- Tailwind CSS
**Architecture:**
- Static site — no JavaScript, no server-side code, no database, no back-end
- Single `index.html` file in the project root
- External stylesheet: `stylesheet.css` in the css folder and referenced by
relative path
- All images stored in the `images/` subfolder and referenced by relative path
(e.g., `src="images/photo.jpg"`) — never link to external image URLs
- Do not link to or embed my resume anywhere on the site
**Responsiveness:**
- Fully responsive at all screen widths from 320px and wider
- No horizontal scrolling on any viewport
**Accessibility — WCAG 2.2 Level AA (non-negotiable):**
- All `<img>` elements must have a descriptive `alt` attribute
- Color contrast ratio: minimum 4.5:1 for normal text, 3:1 for large text
- Heading hierarchy must be logical: `<h1>` → `<h2>` → `<h3>`, no levels skipped
- All link text must be descriptive — no "click here", "read more", or bare URLs
- Page `<title>` element must be descriptive (not "Untitled" or "index")
- All interactive elements (links, buttons) must be keyboard navigable
**Compatibility:**
- Must render correctly on Chrome, Safari, and Firefox; must be mobile-responsive
(works on screens 375px and wider)
## **Security:**
- Links to external sites should open in a new tab (`target="_blank"` with
`rel="noopener noreferrer"`)
---
## 3. Design Standards

**Color palette:**

| Role | Hex Code | Usage |
|---------------------|---------------|-------------------------------------|
| Background | #F8F9FA | Page background |
| Primary text | #212529 | Body copy, paragraphs |
| Accent | #0D6E6E | Section headings, links, skill tags |
| Secondary background | #E9ECEF | Section backgrounds, card backgrounds |

---

**Typography:**
- Heading font: Inter — import from Google Fonts  
- Body font: Inter  
- Body size: 16px, line height: 1.6  
- H1 (page name): 1.5rem, bold  
- H2 (section headings): 1.25rem, bold, accent color  

---

**Imagery:**
- Professional headshot only (stored locally in `/images/`)
- No stock photos or clip art
- No emojis

---

**Layout:**
- Maximum content width: 800px, centered  
- Navigation: Sticky top bar with anchor links to each section  
- Section spacing: 60px top and bottom padding  
- Single column on mobile, two-column layout for projects on desktop  
- Clean layout with generous whitespace  

---

**Component styles:**

_Profile photo:_
- Circular crop, 160px diameter, centered in hero section  

_Skill tags:_
- Rounded pill badges  
- Accent color background with white text  

_Contact links:_
- Display as labeled links (LinkedIn, GitHub, Email)  
- Open in new tab  

_Navigation links:_
- Plain text links  
- Accent color on hover  
- No underline by default  

---

**Tone:**
- Professional, Approachable, Data-driven  
- Clean and minimal design  
- Writing tone: First person, direct, and confident  
- Avoid buzzwords like “passionate”  

---

**Reference sites:**
- read.cv — for simplicity and whitespace  
- brittanychiang.com — for section structure (light mode only)
