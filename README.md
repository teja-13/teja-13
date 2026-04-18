    Teja Swaroop Battula | Portfolio    :root { --bg-deep: #3a1a14; --bg-mid: #6A3428; --surface: rgba(207, 184, 130, 0.08); --surface-strong: rgba(207, 184, 130, 0.16); --text-main: #3f1d16; --text-soft: #5a2d23; --text-card: #f8ecd0; --text-card-soft: #e2cf9f; --ink-dark: #3f1d16; --ink-soft: #5a2d23; --mint: #CFB882; --teal: #9a634d; --gold: #CFB882; --danger: #b56d62; --shadow: 0 22px 50px rgba(31, 11, 7, 0.45); --radius-lg: 22px; --radius-md: 14px; --radius-sm: 10px; } \* { box-sizing: border-box; } html { scroll-behavior: smooth; } body { margin: 0; font-family: "Space Grotesk", "Segoe UI", sans-serif; line-height: 1.6; color: var(--text-main); background: var(--mint); min-height: 100vh; } a { color: var(--bg-mid); text-decoration: none; } a:hover, a:focus-visible { color: #4f261d; } button { font: inherit; } .scroll-progress { position: fixed; top: 0; left: 0; z-index: 100; width: 100%; height: 4px; background: rgba(58, 26, 20, 0.18); } .scroll-progress span { display: block; width: 0; height: 100%; background: linear-gradient(90deg, var(--bg-mid), var(--bg-deep)); } .background-layer { display: none; } .orb { position: absolute; border-radius: 50%; filter: blur(2px); opacity: 0.5; } .orb-one { width: 340px; height: 340px; top: -110px; left: -80px; background: radial-gradient(circle, rgba(207, 184, 130, 0.34), rgba(207, 184, 130, 0.02)); animation: floatOrb 12s ease-in-out infinite; } .orb-two { width: 260px; height: 260px; right: 8%; top: 18%; background: radial-gradient(circle, rgba(154, 99, 77, 0.26), rgba(154, 99, 77, 0)); animation: floatOrb 15s ease-in-out infinite reverse; } .orb-three { width: 280px; height: 280px; left: 55%; bottom: -120px; background: radial-gradient(circle, rgba(207, 184, 130, 0.18), rgba(207, 184, 130, 0)); animation: floatOrb 13s ease-in-out infinite; } .site-shell { width: min(1150px, calc(100% - 2.2rem)); margin: 1.1rem auto 2.2rem; position: relative; z-index: 2; } .topbar { --text-main: var(--text-card); --text-soft: var(--text-card-soft); position: sticky; top: 10px; z-index: 30; display: flex; align-items: center; justify-content: space-between; gap: 1rem; padding: 0.7rem 1rem; margin-bottom: 1rem; border: 1px solid rgba(207, 184, 130, 0.48); border-radius: 999px; background: rgba(58, 26, 20, 0.92); box-shadow: 0 12px 26px rgba(31, 11, 7, 0.2); backdrop-filter: blur(12px); } .brand { font-family: "IBM Plex Mono", monospace; font-size: 0.98rem; font-weight: 500; color: var(--mint); letter-spacing: 0.08em; } .site-nav { display: flex; align-items: center; gap: 0.75rem; flex-wrap: wrap; } .site-nav a { font-size: 0.92rem; padding: 0.38rem 0.72rem; border-radius: 999px; color: var(--text-soft); transition: background-color 0.25s ease, color 0.25s ease; } .site-nav a:hover, .site-nav a:focus-visible, .site-nav a.active { color: var(--text-main); background: rgba(207, 184, 130, 0.16); } .menu-toggle { display: none; background: #eadab4; border: 1px solid rgba(58, 26, 20, 0.4); color: var(--ink-dark); border-radius: 999px; padding: 0.4rem 0.85rem; cursor: pointer; } main section\[id\] { scroll-margin-top: 90px; } .hero { --text-main: var(--text-card); --text-soft: var(--text-card-soft); color: var(--text-main); border-radius: var(--radius-lg); border: 1px solid rgba(207, 184, 130, 0.44); background: rgba(58, 26, 20, 0.92); box-shadow: 0 28px 52px rgba(31, 11, 7, 0.36); padding: clamp(1.5rem, 3vw, 3rem); } .eyebrow { margin: 0; color: var(--mint); font-family: "IBM Plex Mono", monospace; letter-spacing: 0.08em; text-transform: uppercase; font-size: 0.82rem; } .hero h1 { margin: 0.35rem 0 0; font-size: clamp(1.8rem, 5vw, 3.3rem); line-height: 1.06; } .subtitle { margin: 0.55rem 0 0; color: var(--text-card-soft); font-size: clamp(1rem, 2vw, 1.28rem); font-weight: 500; } .summary { margin-top: 1rem; max-width: 73ch; color: var(--text-soft); } .hero-actions { display: flex; flex-wrap: wrap; gap: 0.72rem; margin-top: 1.25rem; } .btn { display: inline-flex; align-items: center; justify-content: center; border-radius: 999px; padding: 0.55rem 1rem; font-weight: 600; border: 1px solid rgba(58, 26, 20, 0.44); background: var(--mint); color: var(--ink-dark); transition: transform 0.2s ease, background-color 0.2s ease, border-color 0.2s ease; } .btn:hover, .btn:focus-visible { transform: translateY(-2px); } .btn-primary { background: linear-gradient(120deg, var(--mint), #e8d7ad); color: var(--ink-dark); border-color: rgba(58, 26, 20, 0.46); } .btn-outline { border-color: rgba(58, 26, 20, 0.48); color: var(--ink-dark); background: #ecdcb7; } .btn-soft { background: #f1e5ca; color: var(--ink-dark); } .hero .btn-primary { background: linear-gradient(120deg, var(--mint), #e8d7ad); color: var(--ink-dark); border-color: rgba(58, 26, 20, 0.46); } .hero .btn-outline { border-color: rgba(58, 26, 20, 0.48); color: var(--ink-dark); background: #ecdcb7; } .hero .btn-soft { background: #f1e5ca; color: var(--ink-dark); } .facts { margin-top: 1rem; display: grid; grid-template-columns: repeat(5, minmax(0, 1fr)); gap: 0.8rem; } .fact-card { --text-main: var(--text-card); --text-soft: var(--text-card-soft); color: var(--text-main); border-radius: var(--radius-md); border: 1px solid rgba(207, 184, 130, 0.4); background: rgba(58, 26, 20, 0.9); box-shadow: 0 12px 26px rgba(31, 11, 7, 0.22); padding: 0.95rem 0.9rem; } .fact-number { margin: 0; color: var(--mint); font-family: "IBM Plex Mono", monospace; font-size: clamp(1.15rem, 1.9vw, 1.55rem); font-weight: 500; } .fact-label { margin: 0.25rem 0 0; color: var(--text-soft); font-size: 0.88rem; } .content-section, .footer { --text-main: var(--text-card); --text-soft: var(--text-card-soft); color: var(--text-main); margin-top: 1rem; border-radius: var(--radius-lg); border: 1px solid rgba(207, 184, 130, 0.42); background: rgba(58, 26, 20, 0.9); box-shadow: var(--shadow); position: relative; overflow: hidden; padding: clamp(1.2rem, 2.7vw, 2rem); } .content-section::before, .footer::before { content: ""; position: absolute; left: 0; top: 0; width: 100%; height: 3px; background: linear-gradient(90deg, var(--mint), rgba(207, 184, 130, 0.1)); } .section-head h2, .footer h2 { margin: 0; color: var(--gold); font-size: clamp(1.2rem, 2.2vw, 1.8rem); } .section-head p, .footer p { margin: 0.45rem 0 0; color: var(--text-soft); } .about-grid { display: grid; grid-template-columns: 1.3fr 1fr; gap: 0.9rem; margin-top: 1rem; } .about-card { padding: 1rem; border-radius: var(--radius-md); background: rgba(43, 19, 14, 0.65); border: 1px solid rgba(207, 184, 130, 0.34); } .about-card p { margin: 0; color: var(--text-soft); } .about-card p + p { margin-top: 0.7rem; } .info-stack p { display: flex; justify-content: space-between; gap: 1rem; flex-wrap: wrap; } .info-stack span { font-family: "IBM Plex Mono", monospace; color: var(--gold); font-size: 0.86rem; } .filter-row { margin-top: 1rem; display: flex; gap: 0.55rem; flex-wrap: wrap; } .filter-btn { border: 1px solid rgba(207, 184, 130, 0.5); border-radius: 999px; background: #e8d7ad; color: var(--ink-dark); padding: 0.36rem 0.74rem; cursor: pointer; transition: background-color 0.2s ease, border-color 0.2s ease; } .filter-btn:hover, .filter-btn:focus-visible, .filter-btn.active { background: #f3e8cd; border-color: #f3e8cd; color: var(--bg-mid); } .skills-grid { margin-top: 0.95rem; display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 0.75rem; } .skill-card { border: 1px solid rgba(207, 184, 130, 0.32); border-radius: var(--radius-md); background: rgba(43, 19, 14, 0.65); padding: 0.9rem; } .skill-card h3 { margin: 0; font-size: 1rem; } .skill-card p { margin: 0.4rem 0 0; color: var(--text-soft); } .skill-card.is-hidden { display: none; } .project-grid { margin-top: 1rem; display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 0.8rem; } .project-card { border-radius: var(--radius-md); border: 1px solid rgba(207, 184, 130, 0.44); background: rgba(43, 19, 14, 0.65); padding: 1rem; } .project-head { display: flex; justify-content: space-between; align-items: flex-start; gap: 0.9rem; } .project-card h3 { margin: 0; font-size: 1.03rem; max-width: 30ch; } .project-card p { margin: 0.65rem 0 0; color: var(--text-soft); } .project-card ul { margin: 0.68rem 0 0; padding-left: 1.1rem; color: var(--text-soft); } .project-card li + li { margin-top: 0.35rem; } .chip-row { display: flex; flex-wrap: wrap; gap: 0.45rem; margin-top: 0.8rem; } .chip-row span { background: #eadab4; border: 1px solid rgba(58, 26, 20, 0.44); border-radius: 999px; padding: 0.18rem 0.55rem; font-size: 0.82rem; color: var(--bg-mid); font-weight: 500; } .chip-row.large span { font-size: 0.92rem; padding: 0.3rem 0.72rem; } .mini-link { display: inline-flex; align-items: center; justify-content: center; border: 1px solid rgba(58, 26, 20, 0.52); background: #eadab4; border-radius: 999px; padding: 0.28rem 0.66rem; color: var(--bg-mid); font-size: 0.83rem; white-space: nowrap; transition: background-color 0.2s ease; } .mini-link:hover, .mini-link:focus-visible { background: #f3e8cd; } .timeline { margin-top: 1rem; display: grid; gap: 0.72rem; } .timeline-item { border-radius: var(--radius-md); border: 1px solid rgba(207, 184, 130, 0.32); background: rgba(43, 19, 14, 0.65); padding: 0.9rem; } .timeline-item h3 { margin: 0; font-size: 1rem; } .timeline-item p, .timeline-item span { margin: 0.35rem 0 0; color: var(--text-soft); display: block; } .card-grid { margin-top: 1rem; display: grid; gap: 0.75rem; } .two-col { grid-template-columns: repeat(2, minmax(0, 1fr)); } .simple-card { border-radius: var(--radius-md); border: 1px solid rgba(207, 184, 130, 0.32); background: rgba(43, 19, 14, 0.65); padding: 0.95rem; } .simple-card h3 { margin: 0; font-size: 1rem; } .simple-card .mini-link { margin-top: 0.68rem; } .footer-actions { display: flex; gap: 0.7rem; flex-wrap: wrap; margin-top: 1rem; } .foot-links { margin-top: 1rem; display: flex; gap: 0.5rem; align-items: center; } .copyright { margin-top: 0.8rem; font-size: 0.85rem; color: #dec999; } .hero a:not(.btn):not(.mini-link), .facts a:not(.btn):not(.mini-link), .content-section a:not(.btn):not(.mini-link), .footer a:not(.btn):not(.mini-link) { color: #f6e3b6; } .hero a:not(.btn):not(.mini-link):hover, .hero a:not(.btn):not(.mini-link):focus-visible, .facts a:not(.btn):not(.mini-link):hover, .facts a:not(.btn):not(.mini-link):focus-visible, .content-section a:not(.btn):not(.mini-link):hover, .content-section a:not(.btn):not(.mini-link):focus-visible, .footer a:not(.btn):not(.mini-link):hover, .footer a:not(.btn):not(.mini-link):focus-visible { color: #fff2d4; } .back-top { position: fixed; right: 1rem; bottom: 1rem; z-index: 40; border: 1px solid rgba(58, 26, 20, 0.55); border-radius: 999px; background: var(--mint); color: var(--bg-mid); padding: 0.5rem 0.85rem; cursor: pointer; opacity: 0; transform: translateY(10px); transition: opacity 0.2s ease, transform 0.2s ease; } .back-top.visible { opacity: 1; transform: translateY(0); } .reveal { opacity: 0; transform: translateY(18px); transition: opacity 0.55s ease, transform 0.55s ease; } .reveal.is-visible { opacity: 1; transform: translateY(0); } @keyframes floatOrb { 0%, 100% { transform: translateY(0) scale(1); } 50% { transform: translateY(16px) scale(1.03); } } @media (max-width: 1060px) { .facts { grid-template-columns: repeat(3, minmax(0, 1fr)); } .project-grid, .two-col, .about-grid { grid-template-columns: 1fr; } } @media (max-width: 760px) { .site-shell { width: min(100%, calc(100% - 1rem)); } .topbar { border-radius: 16px; align-items: flex-start; flex-wrap: wrap; } .menu-toggle { display: inline-flex; } .site-nav { width: 100%; display: none; padding-top: 0.5rem; } .site-nav.is-open { display: flex; } .facts { grid-template-columns: repeat(2, minmax(0, 1fr)); } .skills-grid { grid-template-columns: 1fr; } .hero-actions .btn { width: 100%; } .footer-actions .btn { width: 100%; } } @media (max-width: 440px) { .facts { grid-template-columns: 1fr; } .project-head { flex-direction: column; align-items: flex-start; } } @media (prefers-reduced-motion: reduce) { html { scroll-behavior: auto; } \*, \*::before, \*::after { animation-duration: 0.001ms !important; animation-iteration-count: 1 !important; transition-duration: 0.001ms !important; } .reveal { opacity: 1; transform: none; } }

[TSB](#home) Menu

[About](#about) [Skills](#skills) [Projects](#projects) [Education](#education) [Certifications](#certifications) [Achievements](#achievements) [Contact](#contact)

Portfolio 2026

Teja Swaroop Battula
====================

B.Tech CSE Student | MERN Stack Developer

I build practical, user-focused web applications with React, Node.js, Express.js, and MongoDB. I am currently focused on scalable backend design, real-world product workflows, and AI-assisted features that create measurable impact.

[View GitHub](https://github.com/teja-13) [Connect on LinkedIn](https://www.linkedin.com/in/teja-swaroop-battula-b76696299) [Email Me](mailto:teja72025@gmail.com)

0

Major MERN Projects

0

Programming Languages

0

Industry Certifications

0

Current CGPA

0

Notable Achievements

About Me
--------

Computer science undergraduate with strong execution in full-stack delivery and collaborative product building.

I am a B.Tech Computer Science student at Vasireddy Venkatadri Institute of Technology (VVIT), Guntur, with a deep interest in building scalable web products using the MERN stack.

My current focus is on real-world workflow automation, secure backend systems, and AI-powered features such as semantic matching and text-driven insights.

Email [teja72025@gmail.com](mailto:teja72025@gmail.com)

Phone [+91 8919537353](tel:+918919537353)

LinkedIn [View profile](https://www.linkedin.com/in/teja-swaroop-battula-b76696299)

GitHub [Explore repositories](https://github.com/teja-13)

Base Guntur, Andhra Pradesh, India

Skills
------

Filter by category to quickly scan the stack I use in development projects.

All Languages Frontend Backend Databases AI / NLP Tools Soft Skills

### Languages

JavaScript (ES6+), Python, Java, C, SQL

### Frontend

React.js, TypeScript, Vite, Tailwind CSS, React Router

### Backend

Node.js, Express.js, REST APIs, JWT Authentication, Middleware

### Databases

MongoDB Atlas, Mongoose, MySQL

### AI / NLP

TF-IDF, Cosine Similarity, Text Processing, Pandas, NumPy

### Tools

Git, GitHub, Postman

### Soft Skills

Leadership, Problem Solving, Communication, Time Management

Projects
--------

Detailed snapshots of product work across AI and workflow management domains.

### AI-Powered Resume-JD Matcher (MERN)

[Source Code](https://github.com/teja-13/resume-jd-analyser)

Built a complete MERN application for resume-job description matching using NLP-powered ranking, match score generation, and skill-gap highlighting.

*   Implemented resume parsing support for PDF and DOCX uploads.
*   Used TF-IDF and cosine similarity for semantic job relevance scoring.
*   Designed JWT-secured APIs and integrated them with a React frontend.

React Node.js Express.js MongoDB NLP

### Smart Library Management System

[Source Code](https://github.com/teja-13/e2e)

Developed a role-based MERN platform for handling books, borrowers, and admin workflows with secure authentication and full-stack integration.

*   Built user and librarian flows with permissions and protected routes.
*   Added reservations, due-date tracking, overdue handling, and fines.
*   Connected APIs, database models, and frontend state for smooth operations.

React Express.js MongoDB JWT Role-Based Access

Education
---------

Academic progression and performance milestones.

### B.Tech CSE - VVIT, Guntur

CGPA: 8.07 / 10

2023 - Present

### ISC (Class XII) - Loyola Public School, Guntur

Score: 79.6%

2021 - 2023

### ICSE (Class X) - Loyola Public School, Guntur

Score: 90.16%

2020 - 2021

Certifications
--------------

Formal credentials that support my backend, cloud, and data workflow competencies.

### Introduction to MongoDB

[View Certificate](https://github.com/teja-13/certifications/blob/755df082656693cf5ed5b495abb35331c36d462e/23bq1a0524mongodb.pdf)

### AWS Academy Graduate - Cloud Foundations

[View Certificate](https://github.com/teja-13/certifications/blob/755df082656693cf5ed5b495abb35331c36d462e/AWS_Academy_Graduate___Cloud_Foundations___Training_Badge_Badge20260306-31-phuif8.pdf)

Achievements
------------

Highlights from discipline, team performance, and extracurricular leadership.

### NCC 'B' Certificate

[View Proof](https://drive.google.com/file/d/1F3nM6Y3kxJ4U3gnFOtyH6PG7EkYSlUf0/view?usp=drivesdk)

### Second Place - Central Zone Basketball Inter Collegiate Tournament (2024-2025)

[View Proof](https://drive.google.com/file/d/1epJPYzmR4GoaQf53QACa0f72q1xIwnFN/view?usp=drivesdk)

Hobbies
-------

Interests that keep me creative, focused, and team-driven.

Basketball Music Photography

Contact
-------

I am open to internships, project collaborations, and developer opportunities.

[teja72025@gmail.com](mailto:teja72025@gmail.com) [+91 8919537353](tel:+918919537353) Copy Email

[LinkedIn](https://www.linkedin.com/in/teja-swaroop-battula-b76696299) | [GitHub](https://github.com/teja-13)

© Teja Swaroop Battula

Top const prefersReducedMotion = window.matchMedia("(prefers-reduced-motion: reduce)").matches; const progressBar = document.getElementById("progressBar"); const menuToggle = document.getElementById("menuToggle"); const siteNav = document.getElementById("siteNav"); const revealItems = document.querySelectorAll(".reveal"); const counters = document.querySelectorAll("\[data-count\]"); const backToTop = document.getElementById("backToTop"); const filterButtons = document.querySelectorAll(".filter-btn"); const skillCards = document.querySelectorAll(".skill-card"); const copyEmail = document.getElementById("copyEmail"); const yearNode = document.getElementById("year"); if (yearNode) { yearNode.textContent = String(new Date().getFullYear()); } if (menuToggle && siteNav) { menuToggle.addEventListener("click", () => { const opened = siteNav.classList.toggle("is-open"); menuToggle.setAttribute("aria-expanded", opened ? "true" : "false"); }); siteNav.querySelectorAll("a").forEach((link) => { link.addEventListener("click", () => { siteNav.classList.remove("is-open"); menuToggle.setAttribute("aria-expanded", "false"); }); }); } if (copyEmail) { copyEmail.addEventListener("click", async () => { try { await navigator.clipboard.writeText("teja72025@gmail.com"); const original = copyEmail.textContent; copyEmail.textContent = "Email copied"; window.setTimeout(() => { copyEmail.textContent = original; }, 1400); } catch (error) { copyEmail.textContent = "Copy failed"; window.setTimeout(() => { copyEmail.textContent = "Copy Email"; }, 1400); } }); } if (filterButtons.length > 0 && skillCards.length > 0) { filterButtons.forEach((button) => { button.addEventListener("click", () => { filterButtons.forEach((item) => item.classList.remove("active")); button.classList.add("active"); const selected = button.dataset.filter || "all"; skillCards.forEach((card) => { const category = card.dataset.category || ""; const showCard = selected === "all" || category.includes(selected); card.classList.toggle("is-hidden", !showCard); }); }); }); } const updateScrollProgress = () => { if (!progressBar) { return; } const documentHeight = document.documentElement.scrollHeight - window.innerHeight; const scrolled = documentHeight > 0 ? (window.scrollY / documentHeight) \* 100 : 0; progressBar.style.width = \`${Math.min(100, Math.max(0, scrolled))}%\`; }; let scrollTicking = false; window.addEventListener( "scroll", () => { if (!scrollTicking) { window.requestAnimationFrame(() => { updateScrollProgress(); if (backToTop) { backToTop.classList.toggle("visible", window.scrollY > 640); } scrollTicking = false; }); scrollTicking = true; } }, { passive: true } ); updateScrollProgress(); if (backToTop) { backToTop.addEventListener("click", () => { window.scrollTo({ top: 0, behavior: prefersReducedMotion ? "auto" : "smooth" }); }); } const setCounterFinal = (counter) => { const finalValue = Number(counter.dataset.count || "0"); const decimals = Number(counter.dataset.decimals || "0"); const suffix = counter.dataset.suffix || ""; counter.textContent = \`${finalValue.toFixed(decimals)}${suffix}\`; }; const animateCounter = (counter) => { const target = Number(counter.dataset.count || "0"); const decimals = Number(counter.dataset.decimals || "0"); const suffix = counter.dataset.suffix || ""; const duration = 1200; const start = performance.now(); const run = (now) => { const progress = Math.min((now - start) / duration, 1); const eased = 1 - Math.pow(1 - progress, 3); const current = target \* eased; counter.textContent = \`${current.toFixed(decimals)}${suffix}\`; if (progress < 1) { window.requestAnimationFrame(run); } }; window.requestAnimationFrame(run); }; if (prefersReducedMotion) { revealItems.forEach((item) => item.classList.add("is-visible")); counters.forEach((counter) => setCounterFinal(counter)); } else { const revealObserver = new IntersectionObserver( (entries, observer) => { entries.forEach((entry) => { if (entry.isIntersecting) { entry.target.classList.add("is-visible"); observer.unobserve(entry.target); } }); }, { threshold: 0.15, rootMargin: "0px 0px -5% 0px" } ); revealItems.forEach((item) => revealObserver.observe(item)); const counterObserver = new IntersectionObserver( (entries, observer) => { entries.forEach((entry) => { if (entry.isIntersecting) { animateCounter(entry.target); observer.unobserve(entry.target); } }); }, { threshold: 0.6 } ); counters.forEach((counter) => counterObserver.observe(counter)); } const sections = document.querySelectorAll("main section\[id\]"); const navLinks = document.querySelectorAll('.site-nav a\[href^="#"\]'); if (sections.length > 0 && navLinks.length > 0) { const activateLink = (id) => { navLinks.forEach((link) => { const target = link.getAttribute("href")?.slice(1); link.classList.toggle("active", target === id); }); }; const sectionObserver = new IntersectionObserver( (entries) => { entries.forEach((entry) => { if (entry.isIntersecting) { activateLink(entry.target.id); } }); }, { rootMargin: "-45% 0px -45% 0px", threshold: 0 } ); sections.forEach((section) => sectionObserver.observe(section)); }