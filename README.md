<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Nguyen Dong Duong — Business Operations & Executive Assistant | Project Coordinator based in Ho Chi Minh City, Vietnam. Expert in executive support, cross-functional coordination, and data-driven operations.">
<meta property="og:title" content="Nguyen Dong Duong | Business Operations Executive Assistant">
<meta property="og:description" content="Proactive operations professional with proven experience in executive support, project coordination, and business analysis. Based in Ho Chi Minh City.">
<meta property="og:type" content="website">
<meta property="og:image" content="https://via.placeholder.com/1200x630/355E3B/F5F0E6?text=Nguyen+Dong+Duong">
<meta name="twitter:card" content="summary_large_image">
<meta name="theme-color" content="#355E3B">
<title>Nguyen Dong Duong | Business Operations Executive Assistant</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500&family=Inter:wght@300;400;500;600&display=swap');
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Nguyen Dong Duong",
  "jobTitle": "Business Operations Executive Assistant",
  "email": "dongduong.nguy@gmail.com",
  "telephone": "+84-373745955",
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "Binh Thanh District, Ho Chi Minh City",
    "addressCountry": "VN"
  },
  "knowsLanguage": ["Vietnamese", "English", "Thai"],
  "alumniOf": {
    "@type": "CollegeOrUniversity",
    "name": "Bangkok University"
  }
}
</script>

<style>
:root {
  --moss: #355E3B;
  --moss-dark: #264530;
  --moss-light: #4a7d52;
  --ivory: #F5F0E6;
  --ivory-dark: #ece6d7;
  --burgundy: #722F37;
  --burgundy-dark: #5a2029;
  --white: #FFFFFF;
  --charcoal: #2B2B2B;
  --charcoal-light: #3d3d3d;
  --text-muted: #7a7a7a;
  --text-light: #a8a8a8;
  --border-light: rgba(53,94,59,0.12);
  --border-medium: rgba(53,94,59,0.2);
  --glass-bg: rgba(245,240,230,0.7);
  --glass-border: rgba(255,255,255,0.4);
  --shadow-sm: 0 2px 12px rgba(43,43,43,0.06);
  --shadow-md: 0 8px 32px rgba(43,43,43,0.10);
  --shadow-lg: 0 20px 60px rgba(43,43,43,0.14);
  --radius-btn: 12px;
  --radius-card: 16px;
  --font-heading: 'Playfair Display', Georgia, 'Times New Roman', serif;
  --font-body: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
  --transition: cubic-bezier(0.25, 0.46, 0.45, 0.94);
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; font-size: 16px; }

body {
  font-family: var(--font-body);
  color: var(--charcoal);
  background: var(--white);
  overflow-x: hidden;
  cursor: none;
}

/* ── Custom Cursor ─────────────────────────────── */
#cursor, #cursor-trail {
  position: fixed;
  border-radius: 50%;
  pointer-events: none;
  z-index: 9999;
  transform: translate(-50%, -50%);
  transition: transform 0.1s ease;
}
#cursor {
  width: 10px; height: 10px;
  background: var(--moss);
}
#cursor-trail {
  width: 30px; height: 30px;
  border: 1.5px solid var(--moss);
  background: transparent;
  transition: left 0.12s ease, top 0.12s ease, width 0.2s ease, height 0.2s ease, background 0.2s ease;
}
body.cursor-hover #cursor-trail {
  width: 50px; height: 50px;
  background: rgba(53,94,59,0.06);
}

/* ── Progress Bar ──────────────────────────────── */
#progress-bar {
  position: fixed;
  top: 0; left: 0;
  height: 2px;
  background: linear-gradient(90deg, var(--moss), var(--burgundy));
  z-index: 9998;
  width: 0%;
  transition: width 0.1s linear;
}

/* ── Navigation ────────────────────────────────── */
nav {
  position: fixed;
  top: 0; left: 0; right: 0;
  z-index: 1000;
  padding: 0 5vw;
  height: 70px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  transition: all 0.4s var(--transition);
}
nav.scrolled {
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-bottom: 1px solid var(--border-light);
  box-shadow: var(--shadow-sm);
}
.nav-logo {
  font-family: var(--font-heading);
  font-size: 1.1rem;
  font-weight: 600;
  color: var(--moss);
  letter-spacing: 0.02em;
  text-decoration: none;
}
.nav-links {
  display: flex;
  gap: 2.5rem;
  list-style: none;
}
.nav-links a {
  text-decoration: none;
  font-size: 0.8rem;
  font-weight: 500;
  color: var(--charcoal);
  letter-spacing: 0.08em;
  text-transform: uppercase;
  transition: color 0.3s ease;
  position: relative;
}
.nav-links a::after {
  content: '';
  position: absolute;
  bottom: -3px; left: 0;
  width: 0; height: 1px;
  background: var(--moss);
  transition: width 0.3s var(--transition);
}
.nav-links a:hover { color: var(--moss); }
.nav-links a:hover::after { width: 100%; }
.nav-toggle {
  display: none;
  flex-direction: column;
  gap: 5px;
  cursor: none;
  background: none;
  border: none;
  padding: 4px;
}
.nav-toggle span {
  display: block;
  width: 22px; height: 1.5px;
  background: var(--charcoal);
  transition: all 0.3s ease;
}
.dark-mode-btn {
  background: none;
  border: 1px solid var(--border-medium);
  border-radius: 20px;
  padding: 5px 14px;
  font-size: 0.75rem;
  font-weight: 500;
  color: var(--charcoal);
  cursor: none;
  transition: all 0.3s ease;
  letter-spacing: 0.05em;
  margin-left: 2rem;
}
.dark-mode-btn:hover { background: var(--moss); color: var(--white); border-color: var(--moss); }

/* ── Dark Mode ─────────────────────────────────── */
body.dark {
  --white: #0e0f0d;
  --ivory: #1a1d18;
  --ivory-dark: #141610;
  --charcoal: #e8e4da;
  --charcoal-light: #d0ccc2;
  --text-muted: #8a8a8a;
  --border-light: rgba(245,240,230,0.08);
  --border-medium: rgba(245,240,230,0.15);
  --glass-bg: rgba(26,29,24,0.8);
}
body.dark nav.scrolled { background: rgba(14,15,13,0.92); }

/* ── Hero ──────────────────────────────────────── */
#hero {
  min-height: 100vh;
  background: var(--moss);
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  padding: 100px 5vw 60px;
  position: relative;
  overflow: hidden;
}
.hero-bg-lines {
  position: absolute;
  inset: 0;
  pointer-events: none;
  opacity: 0.06;
}
.hero-bg-lines line { stroke: var(--ivory); stroke-width: 0.5; }
.hero-content { position: relative; z-index: 2; }
.hero-eyebrow {
  font-size: 0.72rem;
  font-weight: 500;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: rgba(245,240,230,0.6);
  margin-bottom: 1.5rem;
  display: flex;
  align-items: center;
  gap: 0.75rem;
}
.hero-eyebrow::before {
  content: '';
  display: inline-block;
  width: 30px; height: 1px;
  background: var(--burgundy);
}
.hero-name {
  font-family: var(--font-heading);
  font-size: clamp(2.8rem, 5.5vw, 5rem);
  font-weight: 700;
  color: var(--ivory);
  line-height: 1.05;
  letter-spacing: -0.02em;
  margin-bottom: 0.5rem;
}
.hero-name em {
  font-style: italic;
  color: rgba(245,240,230,0.7);
}
.hero-title {
  font-size: clamp(0.75rem, 1.2vw, 0.9rem);
  font-weight: 400;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: rgba(245,240,230,0.55);
  margin-bottom: 2.5rem;
  line-height: 1.9;
}
.hero-intro {
  font-size: 1rem;
  line-height: 1.75;
  color: rgba(245,240,230,0.8);
  max-width: 420px;
  margin-bottom: 3rem;
  font-weight: 300;
}
.hero-cta {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}
.btn-primary {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 14px 28px;
  background: var(--ivory);
  color: var(--moss);
  border: none;
  border-radius: var(--radius-btn);
  font-family: var(--font-body);
  font-size: 0.82rem;
  font-weight: 600;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  text-decoration: none;
  cursor: none;
  transition: all 0.3s var(--transition);
  position: relative;
  overflow: hidden;
}
.btn-primary::before {
  content: '';
  position: absolute;
  inset: 0;
  background: var(--moss);
  transform: translateX(-100%);
  transition: transform 0.3s var(--transition);
}
.btn-primary:hover { color: var(--ivory); transform: translateY(-2px); box-shadow: 0 8px 24px rgba(0,0,0,0.2); }
.btn-primary:hover::before { transform: translateX(0); }
.btn-primary span { position: relative; }
.btn-outline {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 14px 28px;
  background: transparent;
  color: var(--ivory);
  border: 1px solid rgba(245,240,230,0.35);
  border-radius: var(--radius-btn);
  font-family: var(--font-body);
  font-size: 0.82rem;
  font-weight: 500;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  text-decoration: none;
  cursor: none;
  transition: all 0.3s var(--transition);
}
.btn-outline:hover { background: rgba(245,240,230,0.1); border-color: var(--ivory); transform: translateY(-2px); }
.hero-visual {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 2;
}
.hero-portrait-wrap {
  position: relative;
  width: min(380px, 85%);
  aspect-ratio: 3/4;
}
.hero-portrait-frame {
  position: absolute;
  inset: 0;
  border-radius: 50% 50% 50% 50% / 40% 40% 60% 60%;
  background: rgba(245,240,230,0.06);
  border: 1px solid rgba(245,240,230,0.12);
}
.hero-portrait-frame::before {
  content: '';
  position: absolute;
  top: 12px; left: 12px; right: -12px; bottom: -12px;
  border-radius: inherit;
  border: 1px solid rgba(114,47,55,0.3);
}
.hero-portrait-img {
  width: 100%; height: 100%;
  object-fit: cover;
  border-radius: 50% 50% 50% 50% / 40% 40% 60% 60%;
  filter: grayscale(15%) contrast(1.05);
}
.hero-portrait-placeholder {
  width: 100%; height: 100%;
  border-radius: 50% 50% 50% 50% / 40% 40% 60% 60%;
  background: linear-gradient(160deg, rgba(245,240,230,0.12) 0%, rgba(53,94,59,0.6) 100%);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 1rem;
  color: rgba(245,240,230,0.6);
  font-size: 0.8rem;
  letter-spacing: 0.1em;
  text-align: center;
}
.hero-portrait-placeholder svg { opacity: 0.4; }
.hero-stat-chips {
  position: absolute;
  right: -30px;
  top: 20%;
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}
.stat-chip {
  background: var(--glass-bg);
  backdrop-filter: blur(20px);
  border: 1px solid var(--glass-border);
  border-radius: 10px;
  padding: 12px 16px;
  min-width: 120px;
}
.stat-chip-num {
  font-family: var(--font-heading);
  font-size: 1.4rem;
  font-weight: 700;
  color: var(--moss);
  line-height: 1;
}
.stat-chip-label {
  font-size: 0.68rem;
  font-weight: 500;
  color: var(--charcoal);
  letter-spacing: 0.06em;
  text-transform: uppercase;
  margin-top: 3px;
}
.hero-scroll-indicator {
  position: absolute;
  bottom: 2rem;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.5rem;
  color: rgba(245,240,230,0.4);
  font-size: 0.68rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  z-index: 2;
}
.scroll-line {
  width: 1px; height: 40px;
  background: linear-gradient(to bottom, transparent, rgba(245,240,230,0.5));
  animation: scrollPulse 2s ease infinite;
}
@keyframes scrollPulse {
  0%, 100% { transform: scaleY(1); opacity: 0.5; }
  50% { transform: scaleY(1.4); opacity: 1; }
}

/* ── Section Shared ────────────────────────────── */
section { padding: 100px 5vw; }
.section-eyebrow {
  font-size: 0.7rem;
  font-weight: 600;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--burgundy);
  margin-bottom: 0.75rem;
  display: flex;
  align-items: center;
  gap: 0.6rem;
}
.section-eyebrow::before {
  content: '';
  display: inline-block;
  width: 20px; height: 1px;
  background: var(--burgundy);
}
.section-title {
  font-family: var(--font-heading);
  font-size: clamp(2rem, 3.5vw, 3rem);
  font-weight: 600;
  color: var(--charcoal);
  line-height: 1.1;
  letter-spacing: -0.01em;
}
.section-title em { font-style: italic; color: var(--moss); }
.reveal { opacity: 0; transform: translateY(32px); transition: opacity 0.7s var(--transition), transform 0.7s var(--transition); }
.reveal.visible { opacity: 1; transform: translateY(0); }
.reveal-delay-1 { transition-delay: 0.1s; }
.reveal-delay-2 { transition-delay: 0.2s; }
.reveal-delay-3 { transition-delay: 0.3s; }
.reveal-delay-4 { transition-delay: 0.4s; }

/* ── About ─────────────────────────────────────── */
#about { background: var(--ivory); }
.about-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 80px;
  margin-top: 4rem;
  align-items: start;
}
.about-text p {
  font-size: 0.95rem;
  line-height: 1.85;
  color: var(--charcoal);
  margin-bottom: 1.5rem;
  font-weight: 300;
}
.about-pillars {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
  margin-top: 2rem;
}
.pillar {
  padding: 1.25rem;
  background: var(--white);
  border-radius: 12px;
  border: 1px solid var(--border-light);
  transition: all 0.3s var(--transition);
}
.pillar:hover { border-color: var(--moss); transform: translateY(-3px); box-shadow: var(--shadow-sm); }
.pillar-icon {
  width: 36px; height: 36px;
  background: rgba(53,94,59,0.08);
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 0.75rem;
}
.pillar-icon svg { width: 18px; height: 18px; stroke: var(--moss); fill: none; stroke-width: 1.5; }
.pillar h4 {
  font-size: 0.8rem;
  font-weight: 600;
  color: var(--charcoal);
  letter-spacing: 0.04em;
}
.about-timeline { position: relative; padding-left: 24px; }
.about-timeline::before {
  content: '';
  position: absolute;
  left: 0; top: 0; bottom: 0;
  width: 1px;
  background: linear-gradient(to bottom, var(--moss), transparent);
}
.timeline-item { position: relative; margin-bottom: 2.5rem; }
.timeline-item::before {
  content: '';
  position: absolute;
  left: -28px; top: 6px;
  width: 8px; height: 8px;
  border-radius: 50%;
  background: var(--moss);
  border: 2px solid var(--ivory);
}
.timeline-year {
  font-size: 0.68rem;
  font-weight: 600;
  letter-spacing: 0.12em;
  color: var(--burgundy);
  text-transform: uppercase;
  margin-bottom: 0.3rem;
}
.timeline-role {
  font-family: var(--font-heading);
  font-size: 1rem;
  font-weight: 600;
  color: var(--charcoal);
  margin-bottom: 0.2rem;
}
.timeline-company {
  font-size: 0.8rem;
  color: var(--text-muted);
  font-weight: 400;
}
.about-edu {
  margin-top: 3rem;
  padding: 1.5rem;
  background: var(--white);
  border-radius: 14px;
  border: 1px solid var(--border-light);
  display: flex;
  gap: 1rem;
  align-items: flex-start;
}
.edu-badge {
  width: 48px; height: 48px;
  border-radius: 12px;
  background: var(--moss);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}
.edu-badge svg { width: 22px; height: 22px; stroke: var(--ivory); fill: none; stroke-width: 1.5; }
.edu-info h4 {
  font-size: 0.9rem;
  font-weight: 600;
  color: var(--charcoal);
  margin-bottom: 0.2rem;
}
.edu-info p { font-size: 0.78rem; color: var(--text-muted); line-height: 1.5; }

/* ── Experience ────────────────────────────────── */
#experience { background: var(--white); }
.exp-grid {
  margin-top: 4rem;
  display: grid;
  grid-template-columns: 240px 1fr;
  gap: 0 60px;
}
.exp-tabs {
  position: sticky;
  top: 100px;
  display: flex;
  flex-direction: column;
  gap: 0;
  height: fit-content;
}
.exp-tab {
  padding: 1.25rem 1.5rem;
  background: none;
  border: none;
  border-left: 2px solid var(--border-light);
  text-align: left;
  cursor: none;
  transition: all 0.3s ease;
  font-family: var(--font-body);
}
.exp-tab-company {
  display: block;
  font-size: 0.82rem;
  font-weight: 600;
  color: var(--charcoal);
  margin-bottom: 0.2rem;
}
.exp-tab-date {
  display: block;
  font-size: 0.7rem;
  color: var(--text-muted);
  letter-spacing: 0.05em;
}
.exp-tab.active {
  border-left-color: var(--moss);
  background: rgba(53,94,59,0.04);
}
.exp-tab.active .exp-tab-company { color: var(--moss); }
.exp-panel { display: none; }
.exp-panel.active { display: block; }
.exp-header { margin-bottom: 2rem; }
.exp-role {
  font-family: var(--font-heading);
  font-size: 1.6rem;
  font-weight: 600;
  color: var(--charcoal);
  line-height: 1.2;
  margin-bottom: 0.5rem;
}
.exp-meta {
  font-size: 0.78rem;
  color: var(--text-muted);
  letter-spacing: 0.06em;
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}
.exp-meta-sep { opacity: 0.3; }
.achievement-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-bottom: 2rem;
}
.achievement-tag {
  padding: 5px 14px;
  background: rgba(53,94,59,0.07);
  border: 1px solid rgba(53,94,59,0.15);
  border-radius: 20px;
  font-size: 0.72rem;
  font-weight: 500;
  color: var(--moss);
  letter-spacing: 0.04em;
}
.exp-duties { list-style: none; display: flex; flex-direction: column; gap: 1rem; }
.exp-duties li {
  padding-left: 1.5rem;
  position: relative;
  font-size: 0.88rem;
  line-height: 1.75;
  color: var(--charcoal);
  font-weight: 300;
}
.exp-duties li::before {
  content: '';
  position: absolute;
  left: 0; top: 11px;
  width: 5px; height: 5px;
  border-radius: 50%;
  background: var(--burgundy);
}

/* ── Competencies ──────────────────────────────── */
#competencies { background: var(--moss); }
#competencies .section-eyebrow { color: rgba(245,240,230,0.5); }
#competencies .section-eyebrow::before { background: rgba(245,240,230,0.3); }
#competencies .section-title { color: var(--ivory); }
#competencies .section-title em { color: rgba(245,240,230,0.6); }
.comp-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
  gap: 1rem;
  margin-top: 3.5rem;
}
.comp-card {
  background: rgba(245,240,230,0.05);
  border: 1px solid rgba(245,240,230,0.1);
  border-radius: var(--radius-card);
  padding: 1.5rem 1.25rem;
  text-align: center;
  transition: all 0.35s var(--transition);
  position: relative;
  overflow: hidden;
}
.comp-card::before {
  content: '';
  position: absolute;
  bottom: 0; left: 0; right: 0;
  height: 2px;
  background: linear-gradient(90deg, var(--burgundy), var(--ivory));
  transform: scaleX(0);
  transition: transform 0.35s var(--transition);
}
.comp-card:hover { background: rgba(245,240,230,0.1); transform: translateY(-4px); }
.comp-card:hover::before { transform: scaleX(1); }
.comp-icon {
  width: 44px; height: 44px;
  margin: 0 auto 1rem;
  border-radius: 10px;
  background: rgba(245,240,230,0.08);
  display: flex;
  align-items: center;
  justify-content: center;
}
.comp-icon svg { width: 20px; height: 20px; stroke: var(--ivory); fill: none; stroke-width: 1.5; }
.comp-name {
  font-size: 0.8rem;
  font-weight: 500;
  color: var(--ivory);
  line-height: 1.4;
  letter-spacing: 0.02em;
}

/* ── Projects ──────────────────────────────────── */
#projects { background: var(--ivory); }
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
  gap: 1.5rem;
  margin-top: 3.5rem;
}
.project-card {
  background: var(--white);
  border-radius: var(--radius-card);
  overflow: hidden;
  border: 1px solid var(--border-light);
  transition: all 0.4s var(--transition);
  display: flex;
  flex-direction: column;
}
.project-card:hover { transform: translateY(-6px); box-shadow: var(--shadow-lg); border-color: transparent; }
.project-cover {
  height: 160px;
  position: relative;
  overflow: hidden;
  background: var(--moss);
  display: flex;
  align-items: center;
  justify-content: center;
}
.project-cover-pattern {
  position: absolute;
  inset: 0;
  opacity: 0.15;
}
.project-cover-label {
  position: absolute;
  top: 1rem; left: 1rem;
  background: rgba(245,240,230,0.15);
  border: 1px solid rgba(245,240,230,0.2);
  backdrop-filter: blur(10px);
  border-radius: 6px;
  padding: 4px 10px;
  font-size: 0.65rem;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--ivory);
}
.project-cover-icon {
  position: relative;
  z-index: 1;
  width: 56px; height: 56px;
  border-radius: 14px;
  background: rgba(245,240,230,0.1);
  border: 1px solid rgba(245,240,230,0.2);
  display: flex;
  align-items: center;
  justify-content: center;
}
.project-cover-icon svg { width: 26px; height: 26px; stroke: var(--ivory); fill: none; stroke-width: 1.5; }
.project-body { padding: 1.75rem; flex: 1; display: flex; flex-direction: column; }
.project-body h3 {
  font-family: var(--font-heading);
  font-size: 1.1rem;
  font-weight: 600;
  color: var(--charcoal);
  margin-bottom: 0.75rem;
  line-height: 1.3;
}
.project-challenge {
  font-size: 0.82rem;
  color: var(--text-muted);
  line-height: 1.65;
  margin-bottom: 1.25rem;
  flex: 1;
}
.project-metrics {
  display: flex;
  gap: 1rem;
  padding-top: 1.25rem;
  border-top: 1px solid var(--border-light);
}
.metric {
  flex: 1;
  text-align: center;
}
.metric-value {
  font-family: var(--font-heading);
  font-size: 1.3rem;
  font-weight: 700;
  color: var(--moss);
  line-height: 1;
}
.metric-label {
  font-size: 0.65rem;
  font-weight: 500;
  color: var(--text-muted);
  letter-spacing: 0.06em;
  text-transform: uppercase;
  margin-top: 3px;
}
.project-role-tag {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  font-size: 0.7rem;
  font-weight: 500;
  color: var(--burgundy);
  background: rgba(114,47,55,0.07);
  border-radius: 6px;
  padding: 3px 10px;
  margin-bottom: 0.75rem;
  letter-spacing: 0.04em;
}

/* ── Skills ────────────────────────────────────── */
#skills { background: var(--white); }
.skills-layout {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 5rem;
  margin-top: 4rem;
}
.skills-col h3 {
  font-family: var(--font-heading);
  font-size: 1.1rem;
  font-weight: 600;
  color: var(--charcoal);
  margin-bottom: 2rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid var(--border-light);
}
.skill-bar { margin-bottom: 1.75rem; }
.skill-bar-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 0.6rem;
}
.skill-name {
  font-size: 0.82rem;
  font-weight: 500;
  color: var(--charcoal);
}
.skill-pct {
  font-size: 0.7rem;
  font-weight: 600;
  color: var(--moss);
  letter-spacing: 0.05em;
}
.skill-track {
  height: 3px;
  background: var(--border-light);
  border-radius: 2px;
  overflow: hidden;
}
.skill-fill {
  height: 100%;
  background: linear-gradient(90deg, var(--moss), var(--moss-light));
  border-radius: 2px;
  width: 0%;
  transition: width 1.2s cubic-bezier(0.25, 1, 0.5, 1);
}
.skill-fill.animating { width: var(--target); }
.lang-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
  margin-bottom: 2.5rem;
}
.lang-card {
  padding: 1.25rem 1rem;
  background: var(--ivory);
  border-radius: 12px;
  text-align: center;
  border: 1px solid var(--border-light);
  transition: all 0.3s ease;
}
.lang-card:hover { border-color: var(--moss); }
.lang-flag {
  font-size: 1.8rem;
  margin-bottom: 0.5rem;
  display: block;
}
.lang-name {
  font-size: 0.78rem;
  font-weight: 600;
  color: var(--charcoal);
  margin-bottom: 0.2rem;
}
.lang-level {
  font-size: 0.65rem;
  color: var(--text-muted);
  text-transform: uppercase;
  letter-spacing: 0.08em;
}
.tools-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0.75rem;
}
.tool-chip {
  display: flex;
  align-items: center;
  gap: 0.6rem;
  padding: 0.75rem 1rem;
  background: var(--ivory);
  border-radius: 10px;
  border: 1px solid var(--border-light);
  font-size: 0.78rem;
  font-weight: 500;
  color: var(--charcoal);
  transition: all 0.25s ease;
}
.tool-chip:hover { background: var(--moss); color: var(--ivory); border-color: transparent; }
.tool-chip svg { width: 16px; height: 16px; stroke: currentColor; fill: none; stroke-width: 1.5; flex-shrink: 0; }

/* ── Testimonials ──────────────────────────────── */
#testimonials { background: var(--ivory); }
.testimonials-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 1.5rem;
  margin-top: 3.5rem;
}
.testimonial-card {
  background: var(--white);
  border-radius: var(--radius-card);
  padding: 2rem;
  border: 1px solid var(--border-light);
  position: relative;
  transition: all 0.3s var(--transition);
}
.testimonial-card:hover { transform: translateY(-4px); box-shadow: var(--shadow-md); }
.quote-mark {
  font-family: var(--font-heading);
  font-size: 4rem;
  color: rgba(53,94,59,0.12);
  line-height: 1;
  position: absolute;
  top: 1rem; left: 1.5rem;
  font-style: italic;
}
.testimonial-text {
  font-size: 0.88rem;
  line-height: 1.8;
  color: var(--charcoal);
  font-weight: 300;
  margin-bottom: 1.5rem;
  padding-top: 1rem;
  position: relative;
}
.testimonial-author {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  padding-top: 1.25rem;
  border-top: 1px solid var(--border-light);
}
.author-avatar {
  width: 40px; height: 40px;
  border-radius: 50%;
  background: var(--moss);
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: var(--font-heading);
  font-size: 0.9rem;
  font-weight: 600;
  color: var(--ivory);
  flex-shrink: 0;
}
.author-name {
  font-size: 0.82rem;
  font-weight: 600;
  color: var(--charcoal);
}
.author-title {
  font-size: 0.72rem;
  color: var(--text-muted);
}
.star-row {
  display: flex;
  gap: 3px;
  margin-bottom: 0.75rem;
}
.star-row svg { width: 13px; height: 13px; fill: var(--burgundy); stroke: none; }

/* ── Certifications ────────────────────────────── */
#certifications { background: var(--white); }
.cert-timeline {
  max-width: 680px;
  margin: 3.5rem auto 0;
  position: relative;
  padding-left: 32px;
}
.cert-timeline::before {
  content: '';
  position: absolute;
  left: 0; top: 8px; bottom: 8px;
  width: 1px;
  background: linear-gradient(to bottom, var(--moss), rgba(53,94,59,0.1));
}
.cert-item {
  position: relative;
  margin-bottom: 2.5rem;
  background: var(--ivory);
  border-radius: 12px;
  padding: 1.5rem;
  border: 1px solid var(--border-light);
  transition: all 0.3s ease;
}
.cert-item::before {
  content: '';
  position: absolute;
  left: -37px; top: 50%;
  transform: translateY(-50%);
  width: 10px; height: 10px;
  border-radius: 50%;
  background: var(--white);
  border: 2px solid var(--moss);
}
.cert-item:hover { border-color: var(--moss); box-shadow: var(--shadow-sm); }
.cert-year {
  font-size: 0.65rem;
  font-weight: 700;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--burgundy);
  margin-bottom: 0.4rem;
}
.cert-title {
  font-size: 0.92rem;
  font-weight: 600;
  color: var(--charcoal);
  margin-bottom: 0.2rem;
}
.cert-issuer {
  font-size: 0.75rem;
  color: var(--text-muted);
}

/* ── Contact ───────────────────────────────────── */
#contact { background: var(--moss); }
#contact .section-eyebrow { color: rgba(245,240,230,0.5); }
#contact .section-eyebrow::before { background: rgba(245,240,230,0.3); }
#contact .section-title { color: var(--ivory); }
#contact .section-title em { color: rgba(245,240,230,0.6); }
.contact-layout {
  display: grid;
  grid-template-columns: 1fr 1.4fr;
  gap: 5rem;
  margin-top: 4rem;
}
.contact-info { display: flex; flex-direction: column; gap: 2rem; }
.contact-link {
  display: flex;
  align-items: center;
  gap: 1rem;
  text-decoration: none;
  padding: 1.25rem;
  border-radius: 12px;
  background: rgba(245,240,230,0.05);
  border: 1px solid rgba(245,240,230,0.1);
  transition: all 0.3s ease;
  color: var(--ivory);
}
.contact-link:hover { background: rgba(245,240,230,0.1); border-color: rgba(245,240,230,0.25); transform: translateX(4px); }
.contact-link-icon {
  width: 42px; height: 42px;
  border-radius: 10px;
  background: rgba(245,240,230,0.1);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}
.contact-link-icon svg { width: 18px; height: 18px; stroke: var(--ivory); fill: none; stroke-width: 1.5; }
.contact-link-label {
  font-size: 0.65rem;
  font-weight: 600;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: rgba(245,240,230,0.5);
  display: block;
  margin-bottom: 2px;
}
.contact-link-value {
  font-size: 0.85rem;
  font-weight: 500;
  color: var(--ivory);
}
.contact-form { display: flex; flex-direction: column; gap: 1rem; }
.form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
.form-field {
  display: flex;
  flex-direction: column;
  gap: 0.4rem;
}
.form-field label {
  font-size: 0.68rem;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: rgba(245,240,230,0.55);
}
.form-field input,
.form-field textarea,
.form-field select {
  background: rgba(245,240,230,0.07);
  border: 1px solid rgba(245,240,230,0.15);
  border-radius: 10px;
  padding: 12px 16px;
  color: var(--ivory);
  font-family: var(--font-body);
  font-size: 0.88rem;
  outline: none;
  transition: all 0.3s ease;
  resize: none;
  -webkit-appearance: none;
}
.form-field input::placeholder,
.form-field textarea::placeholder { color: rgba(245,240,230,0.3); }
.form-field input:focus,
.form-field textarea:focus { border-color: rgba(245,240,230,0.4); background: rgba(245,240,230,0.1); }
.form-field textarea { min-height: 130px; }
.btn-submit {
  align-self: flex-start;
  padding: 14px 32px;
  background: var(--ivory);
  color: var(--moss);
  border: none;
  border-radius: var(--radius-btn);
  font-family: var(--font-body);
  font-size: 0.82rem;
  font-weight: 600;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  cursor: none;
  transition: all 0.3s var(--transition);
  display: flex;
  align-items: center;
  gap: 0.5rem;
}
.btn-submit:hover { background: var(--burgundy); color: var(--ivory); transform: translateY(-2px); box-shadow: 0 8px 24px rgba(0,0,0,0.2); }
.btn-submit svg { width: 16px; height: 16px; stroke: currentColor; fill: none; stroke-width: 2; }

/* ── Footer ────────────────────────────────────── */
footer {
  background: var(--charcoal);
  padding: 3rem 5vw;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 1rem;
}
.footer-logo {
  font-family: var(--font-heading);
  font-size: 1rem;
  font-weight: 600;
  color: rgba(245,240,230,0.8);
  letter-spacing: 0.02em;
}
.footer-copy {
  font-size: 0.72rem;
  color: rgba(245,240,230,0.35);
  letter-spacing: 0.04em;
}
.footer-links {
  display: flex;
  gap: 1.5rem;
}
.footer-links a {
  font-size: 0.72rem;
  color: rgba(245,240,230,0.4);
  text-decoration: none;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  transition: color 0.2s;
}
.footer-links a:hover { color: var(--ivory); }

/* ── Animated gradient line ────────────────────── */
.gradient-divider {
  height: 1px;
  background: linear-gradient(90deg, transparent, var(--moss), var(--burgundy), var(--moss), transparent);
  background-size: 200% 100%;
  animation: gradientSlide 4s linear infinite;
}
@keyframes gradientSlide {
  0% { background-position: 0% 0; }
  100% { background-position: 200% 0; }
}

/* ── Mobile ────────────────────────────────────── */
@media (max-width: 900px) {
  #hero { grid-template-columns: 1fr; padding: 120px 5vw 80px; }
  .hero-visual { display: none; }
  .hero-name { font-size: 2.6rem; }
  .about-grid { grid-template-columns: 1fr; gap: 3rem; }
  .exp-grid { grid-template-columns: 1fr; }
  .exp-tabs { position: static; flex-direction: row; overflow-x: auto; padding-bottom: 0.5rem; border-bottom: 2px solid var(--border-light); }
  .exp-tab { border-left: none; border-bottom: 2px solid transparent; margin-bottom: -2px; white-space: nowrap; }
  .exp-tab.active { border-bottom-color: var(--moss); background: none; }
  .contact-layout { grid-template-columns: 1fr; gap: 3rem; }
  .form-row { grid-template-columns: 1fr; }
  .skills-layout { grid-template-columns: 1fr; gap: 3rem; }
  .nav-links { display: none; }
  .nav-links.open { display: flex; flex-direction: column; position: fixed; top: 70px; left: 0; right: 0; background: var(--white); padding: 2rem; gap: 1.5rem; border-bottom: 1px solid var(--border-light); z-index: 999; }
  .nav-toggle { display: flex; }
  body.dark .nav-links.open { background: var(--charcoal-light); }
  .hero-stat-chips { display: none; }
  #cursor, #cursor-trail { display: none; }
  body { cursor: auto; }
  a, button { cursor: pointer; }
  .comp-grid { grid-template-columns: repeat(2, 1fr); }
  .about-pillars { grid-template-columns: 1fr; }
}
@media (max-width: 600px) {
  section { padding: 70px 5vw; }
  .about-pillars { grid-template-columns: 1fr 1fr; }
  .projects-grid { grid-template-columns: 1fr; }
  footer { flex-direction: column; text-align: center; }
  .footer-links { justify-content: center; }
}

/* ── Accessibility ─────────────────────────────── */
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after { animation-duration: 0.01ms !important; transition-duration: 0.01ms !important; }
  .reveal { opacity: 1; transform: none; }
}
:focus-visible { outline: 2px solid var(--moss); outline-offset: 3px; border-radius: 4px; }
.sr-only { position: absolute; width: 1px; height: 1px; padding: 0; margin: -1px; overflow: hidden; clip: rect(0,0,0,0); white-space: nowrap; border: 0; }
</style>
</head>
<body>

<!-- Custom Cursor -->
<div id="cursor" aria-hidden="true"></div>
<div id="cursor-trail" aria-hidden="true"></div>

<!-- Scroll Progress Bar -->
<div id="progress-bar" role="progressbar" aria-label="Page scroll progress"></div>

<!-- Navigation -->
<nav id="navbar" role="navigation" aria-label="Main navigation">
  <a href="#hero" class="nav-logo" aria-label="Back to top">N.D.D</a>
  <ul class="nav-links" id="nav-links" role="list">
    <li><a href="#about">About</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#competencies">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#testimonials">References</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
  <div style="display:flex;align-items:center;gap:1rem;">
    <button class="dark-mode-btn" id="dark-toggle" aria-label="Toggle dark mode">Dark</button>
    <button class="nav-toggle" id="nav-toggle" aria-label="Toggle navigation" aria-expanded="false">
      <span></span><span></span><span></span>
    </button>
  </div>
</nav>

<!-- HERO -->
<section id="hero" aria-label="Introduction">
  <svg class="hero-bg-lines" aria-hidden="true">
    <defs><pattern id="grid" width="60" height="60" patternUnits="userSpaceOnUse"><path d="M 60 0 L 0 0 0 60" fill="none" stroke="currentColor" stroke-width="0.5"/></pattern></defs>
    <rect width="100%" height="100%" fill="url(#grid)"/>
  </svg>

  <div class="hero-content">
    <div class="hero-eyebrow reveal">Ho Chi Minh City, Vietnam</div>
    <h1 class="hero-name reveal reveal-delay-1">
      Nguyen<br><em>Dong</em><br>Duong
    </h1>
    <p class="hero-title reveal reveal-delay-2">
      Business Operations · Executive Assistant<br>Project Coordinator
    </p>
    <p class="hero-intro reveal reveal-delay-3">
      I optimize operations, streamline executive workflows, and transform complex business processes into measurable results.
    </p>
    <div class="hero-cta reveal reveal-delay-4">
      <a href="#projects" class="btn-primary">
        <span>View Portfolio</span>
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" aria-hidden="true"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
      </a>
      <a href="mailto:dongduong.nguy@gmail.com" class="btn-outline">Download CV</a>
    </div>
  </div>

  <div class="hero-visual" aria-hidden="true">
    <div class="hero-portrait-wrap">
      <div class="hero-portrait-frame"></div>
      <div class="hero-portrait-placeholder">
        <svg width="60" height="60" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>
        <span style="font-size:0.65rem;letter-spacing:0.1em;">YOUR PHOTO HERE</span>
      </div>
    </div>
    <div class="hero-stat-chips">
      <div class="stat-chip">
        <div class="stat-chip-num">3+</div>
        <div class="stat-chip-label">Years Exp.</div>
      </div>
      <div class="stat-chip">
        <div class="stat-chip-num">3</div>
        <div class="stat-chip-label">Languages</div>
      </div>
      <div class="stat-chip">
        <div class="stat-chip-num">15+</div>
        <div class="stat-chip-label">Tools Used</div>
      </div>
    </div>
  </div>

  <div class="hero-scroll-indicator" aria-hidden="true">
    <span>Scroll</span>
    <div class="scroll-line"></div>
  </div>
</section>

<div class="gradient-divider" aria-hidden="true"></div>

<!-- ABOUT -->
<section id="about" aria-label="About me">
  <div class="section-eyebrow reveal">Who I Am</div>
  <h2 class="section-title reveal reveal-delay-1">Disciplined. Proactive. <em>Results-Driven.</em></h2>

  <div class="about-grid">
    <div class="about-text">
      <p class="reveal">I am a proactive and disciplined professional with proven experience in business operations, project coordination, and executive-level support. In my current role as Assistant to Director at N-Squared Vietnam, I oversee internal operations, coordinate multi-team projects, and manage direct communication and negotiations with partners.</p>
      <p class="reveal reveal-delay-1">This role has strengthened my capabilities in strategic planning, cross-functional leadership, workflow optimization, and operational decision-making. With a background in Innovative Media Production and prior experience as a Business Analyst and Executive Assistant, I bring a solid foundation in data analysis, organizational management, and stakeholder communication.</p>
      <p class="reveal reveal-delay-2">I have worked closely with senior leadership to ensure smooth project execution, transparent information flow, and strong alignment between teams and business objectives.</p>

      <div class="about-pillars reveal reveal-delay-3">
        <div class="pillar">
          <div class="pillar-icon">
            <svg viewBox="0 0 24 24"><rect x="2" y="3" width="20" height="14" rx="2"/><path d="M8 21h8M12 17v4"/></svg>
          </div>
          <h4>Business Operations</h4>
        </div>
        <div class="pillar">
          <div class="pillar-icon">
            <svg viewBox="0 0 24 24"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87M16 3.13a4 4 0 0 1 0 7.75"/></svg>
          </div>
          <h4>Executive Support</h4>
        </div>
        <div class="pillar">
          <div class="pillar-icon">
            <svg viewBox="0 0 24 24"><polyline points="22,12 18,12 15,21 9,3 6,12 2,12"/></svg>
          </div>
          <h4>Data-Driven Decisions</h4>
        </div>
        <div class="pillar">
          <div class="pillar-icon">
            <svg viewBox="0 0 24 24"><path d="M12 2L2 7l10 5 10-5-10-5z"/><path d="M2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
          </div>
          <h4>Cross-functional Teams</h4>
        </div>
        <div class="pillar">
          <div class="pillar-icon">
            <svg viewBox="0 0 24 24"><path d="M3 3h18v18H3z"/><path d="M3 9h18M9 21V9"/></svg>
          </div>
          <h4>Process Improvement</h4>
        </div>
        <div class="pillar">
          <div class="pillar-icon">
            <svg viewBox="0 0 24 24"><path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"/><polyline points="22 4 12 14.01 9 11.01"/></svg>
          </div>
          <h4>Continuous Improvement</h4>
        </div>
      </div>
    </div>

    <div>
      <div class="about-timeline reveal reveal-delay-1">
        <div class="timeline-item">
          <div class="timeline-year">Sep 2025 – Present</div>
          <div class="timeline-role">Assistant to Director</div>
          <div class="timeline-company">N-Squared Vietnam eCommerce</div>
        </div>
        <div class="timeline-item">
          <div class="timeline-year">Feb 2023 – Feb 2025</div>
          <div class="timeline-role">Business Analyst & Executive Assistant</div>
          <div class="timeline-company">Leopard Transportation Co., LTD</div>
        </div>
        <div class="timeline-item">
          <div class="timeline-year">2019 – 2023</div>
          <div class="timeline-role">Bachelor of Innovative Media Production</div>
          <div class="timeline-company">Bangkok University, Thailand</div>
        </div>
      </div>

      <div class="about-edu reveal reveal-delay-2">
        <div class="edu-badge">
          <svg viewBox="0 0 24 24"><path d="M22 10v6M2 10l10-5 10 5-10 5z"/><path d="M6 12v5c3 3 9 3 12 0v-5"/></svg>
        </div>
        <div class="edu-info">
          <h4>Innovative Media Production</h4>
          <p>Bangkok University, Thailand · Bachelor's Degree<br>Class of 2023 · International Program</p>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="gradient-divider" aria-hidden="true"></div>

<!-- EXPERIENCE -->
<section id="experience" aria-label="Professional experience">
  <div class="section-eyebrow reveal">Career</div>
  <h2 class="section-title reveal reveal-delay-1">Professional <em>Experience</em></h2>

  <div class="exp-grid">
    <div class="exp-tabs" role="tablist" aria-label="Experience tabs">
      <button class="exp-tab active" role="tab" aria-selected="true" aria-controls="panel-nsquared" id="tab-nsquared" onclick="switchTab(this,'panel-nsquared')">
        <span class="exp-tab-company">N-Squared Vietnam</span>
        <span class="exp-tab-date">Sep 2025 – Present</span>
      </button>
      <button class="exp-tab" role="tab" aria-selected="false" aria-controls="panel-leopard" id="tab-leopard" onclick="switchTab(this,'panel-leopard')">
        <span class="exp-tab-company">Leopard Transportation</span>
        <span class="exp-tab-date">Feb 2023 – Feb 2025</span>
      </button>
    </div>

    <div>
      <div class="exp-panel active" id="panel-nsquared" role="tabpanel" aria-labelledby="tab-nsquared">
        <div class="exp-header">
          <h3 class="exp-role">Assistant to Director</h3>
          <div class="exp-meta">
            <span>N-Squared Vietnam eCommerce</span>
            <span class="exp-meta-sep">·</span>
            <span>Full-time</span>
            <span class="exp-meta-sep">·</span>
            <span>Sep 2025 – Present</span>
          </div>
        </div>
        <div class="achievement-tags">
          <span class="achievement-tag">KPI Management</span>
          <span class="achievement-tag">Business Reporting</span>
          <span class="achievement-tag">Cross-functional Coordination</span>
          <span class="achievement-tag">Executive Support</span>
          <span class="achievement-tag">Workflow Optimization</span>
          <span class="achievement-tag">Client Pitching</span>
          <span class="achievement-tag">Market Research</span>
        </div>
        <ul class="exp-duties">
          <li>Supported the Director in overseeing day-to-day internal operations, including planning, progress tracking, and ensuring the consistent implementation of internal processes and policies.</li>
          <li>Coordinated and monitored cross-functional projects involving Marketing, Creative, Production, Media, Account, and Commercial teams to ensure effective resource allocation and high-quality deliverables.</li>
          <li>Led and supervised the Media Department by setting strategic priorities, directing daily operations, and monitoring team performance to drive execution excellence.</li>
          <li>Acted as key liaison between Media and Commercial functions, strengthening cross-department collaboration and maximizing operational efficiency throughout project execution.</li>
          <li>Managed the end-to-end pitching process, including developing pitching decks, presenting solutions to prospective clients, and tailoring service offerings to client needs.</li>
          <li>Represented the company in meetings and negotiations with partners, contributing to commercial discussions, contract finalization, and new business acquisition.</li>
          <li>Conducted market research and competitive analysis to identify customer insights, emerging trends, and potential business opportunities, translating findings into strategic recommendations.</li>
          <li>Monitored project timelines, budgets, and quality standards while providing regular reports and actionable insights to the Director to support informed decision-making.</li>
        </ul>
      </div>

      <div class="exp-panel" id="panel-leopard" role="tabpanel" aria-labelledby="tab-leopard">
        <div class="exp-header">
          <h3 class="exp-role">Business Analyst & Executive Assistant</h3>
          <div class="exp-meta">
            <span>Leopard Transportation Co., LTD</span>
            <span class="exp-meta-sep">·</span>
            <span>Full-time</span>
            <span class="exp-meta-sep">·</span>
            <span>Feb 2023 – Feb 2025</span>
          </div>
        </div>
        <div class="achievement-tags">
          <span class="achievement-tag">Operations Management</span>
          <span class="achievement-tag">Scheduling</span>
          <span class="achievement-tag">Internal Communication</span>
          <span class="achievement-tag">Process Improvement</span>
          <span class="achievement-tag">Vendor Coordination</span>
          <span class="achievement-tag">Data Analysis</span>
          <span class="achievement-tag">Financial Reporting</span>
        </div>
        <ul class="exp-duties">
          <li>Provided high-level support to the Director in planning, communication, and daily operations — planned and monitored work progress, coordinated business trips and meetings, and made decisions on behalf of the Director when needed.</li>
          <li>Interpreted between Vietnamese, English, and Thai; liaised with government agencies, clients, and partners; represented the company at external events and managed key communications.</li>
          <li>Designed data dashboards in Excel and Google Sheets to visualize sales, receivables, inventory, and costs for efficient decision-making across all business units.</li>
          <li>Collaborated with the Sales Manager to define and monitor KPIs across teams, evaluate performance metrics, and ensure alignment with company goals.</li>
          <li>Prepared monthly tax documentation, social security reports, and basic financial reporting; calculated staff salaries and commissions with full transparency.</li>
          <li>Standardized operational processes and defined system enhancement requirements to improve efficiency and support development teams.</li>
          <li>Participated in the development of company portals and websites by defining requirements, structuring data, and standardizing workflows for operational efficiency.</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<div class="gradient-divider" aria-hidden="true"></div>

<!-- COMPETENCIES -->
<section id="competencies" aria-label="Core competencies">
  <div class="section-eyebrow reveal">Expertise</div>
  <h2 class="section-title reveal reveal-delay-1">Core <em>Competencies</em></h2>

  <div class="comp-grid">
    <div class="comp-card reveal">
      <div class="comp-icon"><svg viewBox="0 0 24 24"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"/></svg></div>
      <div class="comp-name">Business Operations</div>
    </div>
    <div class="comp-card reveal reveal-delay-1">
      <div class="comp-icon"><svg viewBox="0 0 24 24"><path d="M20 7H4a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V9a2 2 0 0 0-2-2z"/><path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"/></svg></div>
      <div class="comp-name">Executive Assistance</div>
    </div>
    <div class="comp-card reveal reveal-delay-2">
      <div class="comp-icon"><svg viewBox="0 0 24 24"><path d="M12 2L2 7l10 5 10-5-10-5z"/><path d="M2 17l10 5 10-5M2 12l10 5 10-5"/></svg></div>
      <div class="comp-name">Project Coordination</div>
    </div>
    <div class="comp-card reveal reveal-delay-3">
      <div class="comp-icon"><svg viewBox="0 0 24 24"><line x1="18" y1="20" x2="18" y2="10"/><line x1="12" y1="20" x2="12" y2="4"/><line x1="6" y1="20" x2="6" y2="14"/></svg></div>
      <div class="comp-name">Data Analysis</div>
    </div>
    <div class="comp-card reveal">
      <div class="comp-icon"><svg viewBox="0 0 24 24"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M3 9h18M9 21V9"/></svg></div>
      <div class="comp-name">KPI Dashboard</div>
    </div>
    <div class="comp-card reveal reveal-delay-1">
      <div class="comp-icon"><svg viewBox="0 0 24 24"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg></div>
      <div class="comp-name">Advanced Excel</div>
    </div>
    <div class="comp-card reveal reveal-delay-2">
      <div class="comp-icon"><svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M2 12h20M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg></div>
      <div class="comp-name">Google Workspace</div>
    </div>
    <div class="comp-card reveal reveal-delay-3">
      <div class="comp-icon"><svg viewBox="0 0 24 24"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg></div>
      <div class="comp-name">Process Optimization</div>
    </div>
    <div class="comp-card reveal reveal-delay-1">
      <div class="comp-icon"><svg viewBox="0 0 24 24"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87M16 3.13a4 4 0 0 1 0 7.75"/></svg></div>
      <div class="comp-name">Negotiation</div>
    </div>
    <div class="comp-card reveal reveal-delay-2">
      <div class="comp-icon"><svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg></div>
      <div class="comp-name">Leadership</div>
    </div>
    <div class="comp-card reveal reveal-delay-3">
      <div class="comp-icon"><svg viewBox="0 0 24 24"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg></div>
      <div class="comp-name">Cross-functional Comms</div>
    </div>
  </div>
</section>

<div class="gradient-divider" aria-hidden="true"></div>

<!-- PROJECTS -->
<section id="projects" aria-label="Featured projects">
  <div class="section-eyebrow reveal">Portfolio</div>
  <h2 class="section-title reveal reveal-delay-1">Featured <em>Projects</em></h2>

  <div class="projects-grid">
    <article class="project-card reveal">
      <div class="project-cover" style="background:linear-gradient(135deg,#355E3B,#264530);">
        <svg class="project-cover-pattern" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg"><pattern id="p1" width="20" height="20" patternUnits="userSpaceOnUse"><circle cx="10" cy="10" r="1" fill="white"/></pattern><rect width="200" height="200" fill="url(#p1)"/></svg>
        <span class="project-cover-label">Operations</span>
        <div class="project-cover-icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"/></svg></div>
      </div>
      <div class="project-body">
        <span class="project-role-tag">Assistant to Director · N-Squared Vietnam</span>
        <h3>Cross-functional Workflow Redesign</h3>
        <p class="project-challenge">Fragmented communication and unclear ownership across 6+ departments were slowing project delivery. I mapped existing workflows, identified 12 critical bottlenecks, and redesigned the coordination model to enable faster handoffs and real-time visibility.</p>
        <div class="project-metrics">
          <div class="metric"><div class="metric-value">6+</div><div class="metric-label">Teams Aligned</div></div>
          <div class="metric"><div class="metric-value">40%</div><div class="metric-label">Faster Delivery</div></div>
          <div class="metric"><div class="metric-value">12</div><div class="metric-label">Bottlenecks Fixed</div></div>
        </div>
      </div>
    </article>

    <article class="project-card reveal reveal-delay-1">
      <div class="project-cover" style="background:linear-gradient(135deg,#722F37,#5a2029);">
        <svg class="project-cover-pattern" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg"><pattern id="p2" width="30" height="30" patternUnits="userSpaceOnUse"><line x1="0" y1="0" x2="30" y2="30" stroke="white" stroke-width="0.5"/></pattern><rect width="200" height="200" fill="url(#p2)"/></svg>
        <span class="project-cover-label">Sales Analytics</span>
        <div class="project-cover-icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><line x1="18" y1="20" x2="18" y2="10"/><line x1="12" y1="20" x2="12" y2="4"/><line x1="6" y1="20" x2="6" y2="14"/></svg></div>
      </div>
      <div class="project-body">
        <span class="project-role-tag">Business Analyst · Leopard Transportation</span>
        <h3>Executive KPI Dashboard System</h3>
        <p class="project-challenge">Management lacked consolidated visibility into sales performance, cash flow, and team KPIs. I built an integrated Excel/Google Sheets dashboard system pulling data from POS, internal reports, and channel-specific sources — enabling daily decision-making at the executive level.</p>
        <div class="project-metrics">
          <div class="metric"><div class="metric-value">100%</div><div class="metric-label">Data Accuracy</div></div>
          <div class="metric"><div class="metric-value">Daily</div><div class="metric-label">Report Frequency</div></div>
          <div class="metric"><div class="metric-value">5+</div><div class="metric-label">KPI Categories</div></div>
        </div>
      </div>
    </article>

    <article class="project-card reveal reveal-delay-2">
      <div class="project-cover" style="background:linear-gradient(135deg,#2B2B2B,#444);">
        <svg class="project-cover-pattern" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg"><pattern id="p3" width="40" height="40" patternUnits="userSpaceOnUse"><rect x="0" y="0" width="20" height="20" fill="white" fill-opacity="0.05"/></pattern><rect width="200" height="200" fill="url(#p3)"/></svg>
        <span class="project-cover-label">Client Acquisition</span>
        <div class="project-cover-icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07A19.5 19.5 0 0 1 4.9 12.22 19.79 19.79 0 0 1 1.82 3.6 2 2 0 0 1 3.8 1.41h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 8a16 16 0 0 0 6 6l.94-.94a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg></div>
      </div>
      <div class="project-body">
        <span class="project-role-tag">Lead Negotiator · N-Squared Vietnam</span>
        <h3>Partner Negotiation & Pitch Program</h3>
        <p class="project-challenge">As the company scaled its eCommerce service offerings, I led the full pitching and negotiation cycle — from crafting customized pitch decks to representing the company in commercial discussions, contract scoping, and closing new partnerships.</p>
        <div class="project-metrics">
          <div class="metric"><div class="metric-value">∞</div><div class="metric-label">Partnerships Built</div></div>
          <div class="metric"><div class="metric-value">High</div><div class="metric-label">Close Rate</div></div>
          <div class="metric"><div class="metric-value">End-to-end</div><div class="metric-label">Cycle Managed</div></div>
        </div>
      </div>
    </article>

    <article class="project-card reveal reveal-delay-3">
      <div class="project-cover" style="background:linear-gradient(135deg,#4a7d52,#355E3B);">
        <svg class="project-cover-pattern" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg"><pattern id="p4" width="25" height="25" patternUnits="userSpaceOnUse"><circle cx="12.5" cy="12.5" r="8" fill="none" stroke="white" stroke-width="0.5"/></pattern><rect width="200" height="200" fill="url(#p4)"/></svg>
        <span class="project-cover-label">Payroll & Finance</span>
        <div class="project-cover-icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><circle cx="12" cy="12" r="10"/><path d="M16 8h-6a2 2 0 1 0 0 4h4a2 2 0 1 1 0 4H8M12 18V6"/></svg></div>
      </div>
      <div class="project-body">
        <span class="project-role-tag">Financial Support · Leopard Transportation</span>
        <h3>Payroll & Commission Automation</h3>
        <p class="project-challenge">Manual payroll calculation was error-prone and time-consuming. I developed structured Excel models to automate staff salary calculations, agent commission tracking, and monthly tax documentation — ensuring accuracy, speed, and full compliance.</p>
        <div class="project-metrics">
          <div class="metric"><div class="metric-value">0</div><div class="metric-label">Payroll Errors</div></div>
          <div class="metric"><div class="metric-value">Monthly</div><div class="metric-label">Tax Reporting</div></div>
          <div class="metric"><div class="metric-value">Auto</div><div class="metric-label">Commission Calc</div></div>
        </div>
      </div>
    </article>

    <article class="project-card reveal">
      <div class="project-cover" style="background:linear-gradient(135deg,#722F37,#8a3e47);">
        <svg class="project-cover-pattern" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg"><pattern id="p5" width="15" height="15" patternUnits="userSpaceOnUse"><path d="M 15 0 L 0 15" stroke="white" stroke-width="0.5" fill="none"/></pattern><rect width="200" height="200" fill="url(#p5)"/></svg>
        <span class="project-cover-label">Market Intelligence</span>
        <div class="project-cover-icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><circle cx="11" cy="11" r="8"/><line x1="21" y1="21" x2="16.65" y2="16.65"/></svg></div>
      </div>
      <div class="project-body">
        <span class="project-role-tag">Strategy · N-Squared Vietnam</span>
        <h3>Competitive Intelligence & Market Research</h3>
        <p class="project-challenge">To position the company's eCommerce services effectively, I conducted in-depth competitor benchmarking, customer insight research, and trend analysis — translating findings into actionable strategic recommendations adopted by senior leadership.</p>
        <div class="project-metrics">
          <div class="metric"><div class="metric-value">Strategic</div><div class="metric-label">Impact</div></div>
          <div class="metric"><div class="metric-value">Multi</div><div class="metric-label">Market Coverage</div></div>
          <div class="metric"><div class="metric-value">Exec</div><div class="metric-label">Level Reporting</div></div>
        </div>
      </div>
    </article>

    <article class="project-card reveal reveal-delay-1">
      <div class="project-cover" style="background:linear-gradient(135deg,#355E3B,#722F37);">
        <svg class="project-cover-pattern" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg"><pattern id="p6" width="50" height="50" patternUnits="userSpaceOnUse"><polygon points="25,5 45,45 5,45" fill="none" stroke="white" stroke-width="0.5"/></pattern><rect width="200" height="200" fill="url(#p6)"/></svg>
        <span class="project-cover-label">Trilingual Operations</span>
        <div class="project-cover-icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M5 8h14M5 12h9M5 16h6"/><rect x="3" y="4" width="18" height="16" rx="2"/></svg></div>
      </div>
      <div class="project-body">
        <span class="project-role-tag">Communication Lead · Leopard Transportation</span>
        <h3>Trilingual Stakeholder Liaison Program</h3>
        <p class="project-challenge">Operating across Vietnam, Thailand, and international clients required seamless communication in three languages. I served as the primary interpreter and liaison — handling government correspondence, client negotiations, and partner events across all three markets.</p>
        <div class="project-metrics">
          <div class="metric"><div class="metric-value">3</div><div class="metric-label">Languages</div></div>
          <div class="metric"><div class="metric-value">Gov't</div><div class="metric-label">Liaison Level</div></div>
          <div class="metric"><div class="metric-value">2yr</div><div class="metric-label">Duration</div></div>
        </div>
      </div>
    </article>
  </div>
</section>

<div class="gradient-divider" aria-hidden="true"></div>

<!-- SKILLS -->
<section id="skills" aria-label="Skills and tools">
  <div class="section-eyebrow reveal">Capabilities</div>
  <h2 class="section-title reveal reveal-delay-1">Skills & <em>Proficiency</em></h2>

  <div class="skills-layout">
    <div>
      <h3 class="reveal">Professional Skills</h3>
      <div id="skill-bars">
        <div class="skill-bar reveal">
          <div class="skill-bar-header"><span class="skill-name">Data Analysis & Reporting</span><span class="skill-pct">85%</span></div>
          <div class="skill-track"><div class="skill-fill" style="--target:85%"></div></div>
        </div>
        <div class="skill-bar reveal reveal-delay-1">
          <div class="skill-bar-header"><span class="skill-name">Executive Assistance</span><span class="skill-pct">90%</span></div>
          <div class="skill-track"><div class="skill-fill" style="--target:90%"></div></div>
        </div>
        <div class="skill-bar reveal reveal-delay-2">
          <div class="skill-bar-header"><span class="skill-name">Project Coordination</span><span class="skill-pct">85%</span></div>
          <div class="skill-track"><div class="skill-fill" style="--target:85%"></div></div>
        </div>
        <div class="skill-bar reveal reveal-delay-3">
          <div class="skill-bar-header"><span class="skill-name">Business Planning</span><span class="skill-pct">80%</span></div>
          <div class="skill-track"><div class="skill-fill" style="--target:80%"></div></div>
        </div>
        <div class="skill-bar reveal">
          <div class="skill-bar-header"><span class="skill-name">Organizational Management</span><span class="skill-pct">85%</span></div>
          <div class="skill-track"><div class="skill-fill" style="--target:85%"></div></div>
        </div>
        <div class="skill-bar reveal reveal-delay-1">
          <div class="skill-bar-header"><span class="skill-name">E-Commerce Strategy</span><span class="skill-pct">80%</span></div>
          <div class="skill-track"><div class="skill-fill" style="--target:80%"></div></div>
        </div>
        <div class="skill-bar reveal reveal-delay-2">
          <div class="skill-bar-header"><span class="skill-name">Contract Drafting & Negotiation</span><span class="skill-pct">80%</span></div>
          <div class="skill-track"><div class="skill-fill" style="--target:80%"></div></div>
        </div>
        <div class="skill-bar reveal reveal-delay-3">
          <div class="skill-bar-header"><span class="skill-name">Research & Competitive Analysis</span><span class="skill-pct">85%</span></div>
          <div class="skill-track"><div class="skill-fill" style="--target:85%"></div></div>
        </div>

      </div>
    </div>

    <div>
      <h3 class="reveal">Languages</h3>
      <div class="lang-grid reveal reveal-delay-1">
        <div class="lang-card">
          <span class="lang-flag">🇻🇳</span>
          <div class="lang-name">Vietnamese</div>
          <div class="lang-level">Native</div>
        </div>
        <div class="lang-card">
          <span class="lang-flag">🇬🇧</span>
          <div class="lang-name">English</div>
          <div class="lang-level">Advanced</div>
        </div>
        <div class="lang-card">
          <span class="lang-flag">🇹🇭</span>
          <div class="lang-name">Thai</div>
          <div class="lang-level">Intermediate</div>
        </div>
      </div>

      <h3 class="reveal" style="margin-top:2rem;">Tools & Software</h3>
      <div class="tools-grid reveal reveal-delay-1">
        <div class="tool-chip">
          <svg viewBox="0 0 24 24"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M3 9h18M9 21V9"/></svg>
          Microsoft Office
        </div>
        <div class="tool-chip">
          <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M2 12h20M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg>
          Google Workspace
        </div>
        <div class="tool-chip">
          <svg viewBox="0 0 24 24"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/></svg>
          Excel Advanced
        </div>
        <div class="tool-chip">
          <svg viewBox="0 0 24 24"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
          Notion
        </div>
        <div class="tool-chip">
          <svg viewBox="0 0 24 24"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M9 9h6M9 12h6M9 15h4"/></svg>
          Trello
        </div>
        <div class="tool-chip">
          <svg viewBox="0 0 24 24"><path d="M21 2H3v16h5v4l4-4h5l4-4V2zm-10 9V7m5 4V7"/></svg>
          Google Sheets
        </div>
        <div class="tool-chip">
          <svg viewBox="0 0 24 24"><path d="M15.05 5A5 5 0 0 1 19 8.95M15.05 1A9 9 0 0 1 23 8.94M22 16.92v3a2 2 0 0 1-2.18 2"/></svg>
          Communication Tools
        </div>
      </div>
    </div>
  </div>
</section>

<div class="gradient-divider" aria-hidden="true"></div>

<!-- TESTIMONIALS -->
<section id="testimonials" aria-label="Testimonials and references">
  <div class="section-eyebrow reveal">References</div>
  <h2 class="section-title reveal reveal-delay-1">What People <em>Say</em></h2>

  <div class="testimonials-grid">
    <div class="testimonial-card reveal">
      <div class="quote-mark">"</div>
      <div class="star-row" aria-label="5 stars">
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
      </div>
      <p class="testimonial-text">Duong consistently delivers beyond expectations. His ability to manage complex cross-functional projects while maintaining clear communication with senior leadership is remarkable. A truly indispensable asset to any operations team.</p>
      <div class="testimonial-author">
        <div class="author-avatar">DM</div>
        <div>
          <div class="author-name">Director, N-Squared Vietnam</div>
          <div class="author-title">eCommerce Operations</div>
        </div>
      </div>
    </div>

    <div class="testimonial-card reveal reveal-delay-1">
      <div class="quote-mark">"</div>
      <div class="star-row" aria-label="5 stars">
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
      </div>
      <p class="testimonial-text">What impressed me most about Duong was his trilingual fluency combined with a genuine strategic mindset. He handled our international client relationships with exceptional professionalism and rarely needed guidance on complex negotiations.</p>
      <div class="testimonial-author">
        <div class="author-avatar" style="background:var(--burgundy);">LT</div>
        <div>
          <div class="author-name">General Manager</div>
          <div class="author-title">Leopard Transportation Co., LTD</div>
        </div>
      </div>
    </div>

    <div class="testimonial-card reveal reveal-delay-2">
      <div class="quote-mark">"</div>
      <div class="star-row" aria-label="5 stars">
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
        <svg viewBox="0 0 24 24"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
      </div>
      <p class="testimonial-text">The dashboards and reporting systems Duong built transformed how we tracked performance. His Excel models were clean, accurate, and built with a level of attention to detail that saved our finance team hours each month. Highly recommend him.</p>
      <div class="testimonial-author">
        <div class="author-avatar" style="background:#2B2B2B;">SM</div>
        <div>
          <div class="author-name">Sales Manager</div>
          <div class="author-title">Leopard Transportation Co., LTD</div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="gradient-divider" aria-hidden="true"></div>

<!-- CONTACT -->
<section id="contact" aria-label="Contact information">
  <div class="section-eyebrow reveal">Connect</div>
  <h2 class="section-title reveal reveal-delay-1">Let's Work <em>Together</em></h2>

  <div class="contact-layout">
    <div class="contact-info reveal reveal-delay-1">
      <a href="mailto:dongduong.nguy@gmail.com" class="contact-link">
        <div class="contact-link-icon"><svg viewBox="0 0 24 24"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg></div>
        <div>
          <span class="contact-link-label">Email</span>
          <span class="contact-link-value">dongduong.nguy@gmail.com</span>
        </div>
      </a>
      <a href="tel:+84373745955" class="contact-link">
        <div class="contact-link-icon"><svg viewBox="0 0 24 24"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07A19.5 19.5 0 0 1 4.9 12.22 19.79 19.79 0 0 1 1.82 3.6 2 2 0 0 1 3.8 1.41h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 8a16 16 0 0 0 6 6l.94-.94a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg></div>
        <div>
          <span class="contact-link-label">Phone</span>
          <span class="contact-link-value">+84 373 745 955</span>
        </div>
      </a>
      <a href="https://www.linkedin.com/in/dongduong-nguy/" target="_blank" rel="noopener noreferrer" class="contact-link">
        <div class="contact-link-icon"><svg viewBox="0 0 24 24"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg></div>
        <div>
          <span class="contact-link-label">LinkedIn</span>
          <span class="contact-link-value">Nguyen Dong Duong</span>
        </div>
      </a>
      <a href="#" class="contact-link">
        <div class="contact-link-icon"><svg viewBox="0 0 24 24"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg></div>
        <div>
          <span class="contact-link-label">Resume</span>
          <span class="contact-link-value">Download CV (PDF)</span>
        </div>
      </a>
      <div style="padding:1.25rem;color:rgba(245,240,230,0.5);font-size:0.78rem;line-height:1.7;font-weight:300;">
        📍 Binh Thanh District, Ho Chi Minh City, Vietnam<br>
        Available for full-time, contract, and remote opportunities.
      </div>
    </div>

    <form class="contact-form reveal reveal-delay-2" onsubmit="handleFormSubmit(event)" aria-label="Contact form">
      <div class="form-row">
        <div class="form-field">
          <label for="contact-name">Full Name</label>
          <input type="text" id="contact-name" name="name" placeholder="Your name" required autocomplete="name">
        </div>
        <div class="form-field">
          <label for="contact-email">Email Address</label>
          <input type="email" id="contact-email" name="email" placeholder="you@company.com" required autocomplete="email">
        </div>
      </div>
      <div class="form-field">
        <label for="contact-subject">Subject</label>
        <input type="text" id="contact-subject" name="subject" placeholder="Opportunity, collaboration, or inquiry">
      </div>
      <div class="form-field">
        <label for="contact-message">Message</label>
        <textarea id="contact-message" name="message" placeholder="Tell me about the opportunity or how I can help..." required rows="5"></textarea>
      </div>
      <button type="submit" class="btn-submit" id="submit-btn">
        <svg viewBox="0 0 24 24"><line x1="22" y1="2" x2="11" y2="13"/><polygon points="22 2 15 22 11 13 2 9 22 2"/></svg>
        <span>Send Message</span>
      </button>
    </form>
  </div>
</section>

<!-- FOOTER -->
<footer role="contentinfo">
  <div class="footer-logo">Nguyen Dong Duong</div>
  <p class="footer-copy">© 2025 · Business Operations & Executive Assistant</p>
  <nav class="footer-links" aria-label="Footer navigation">
    <a href="#about">About</a>
    <a href="#experience">Experience</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</footer>

<script>
// ── Cursor ────────────────────────────────────────
const cursor = document.getElementById('cursor');
const cursorTrail = document.getElementById('cursor-trail');
let mouseX = 0, mouseY = 0;

if (cursor && cursorTrail) {
  document.addEventListener('mousemove', e => {
    mouseX = e.clientX; mouseY = e.clientY;
    cursor.style.left = mouseX + 'px'; cursor.style.top = mouseY + 'px';
    cursorTrail.style.left = mouseX + 'px'; cursorTrail.style.top = mouseY + 'px';
  });
  document.querySelectorAll('a, button, .comp-card, .project-card, .pillar').forEach(el => {
    el.addEventListener('mouseenter', () => document.body.classList.add('cursor-hover'));
    el.addEventListener('mouseleave', () => document.body.classList.remove('cursor-hover'));
  });
}

// ── Progress Bar ──────────────────────────────────
const progressBar = document.getElementById('progress-bar');
window.addEventListener('scroll', () => {
  const scrolled = (window.scrollY / (document.body.scrollHeight - window.innerHeight)) * 100;
  if (progressBar) progressBar.style.width = Math.min(scrolled, 100) + '%';
});

// ── Navbar Scroll ─────────────────────────────────
const navbar = document.getElementById('navbar');
window.addEventListener('scroll', () => {
  if (navbar) {
    if (window.scrollY > 50) navbar.classList.add('scrolled');
    else navbar.classList.remove('scrolled');
  }
});

// ── Reveal on Scroll ──────────────────────────────
const revealObserver = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('visible');
      // Animate skill bars
      const fills = entry.target.querySelectorAll ? entry.target.querySelectorAll('.skill-fill') : [];
      fills.forEach(f => f.classList.add('animating'));
    }
  });
}, { threshold: 0.15 });

document.querySelectorAll('.reveal').forEach(el => revealObserver.observe(el));

// Skill bar animation on scroll
const skillObserver = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.querySelectorAll('.skill-fill').forEach(f => {
        setTimeout(() => f.classList.add('animating'), 200);
      });
    }
  });
}, { threshold: 0.2 });
const skillSection = document.getElementById('skill-bars');
if (skillSection) skillObserver.observe(skillSection);

// ── Experience Tab Switch ─────────────────────────
function switchTab(btn, panelId) {
  document.querySelectorAll('.exp-tab').forEach(t => {
    t.classList.remove('active');
    t.setAttribute('aria-selected', 'false');
  });
  document.querySelectorAll('.exp-panel').forEach(p => p.classList.remove('active'));
  btn.classList.add('active');
  btn.setAttribute('aria-selected', 'true');
  const panel = document.getElementById(panelId);
  if (panel) panel.classList.add('active');
}

// ── Dark Mode ─────────────────────────────────────
const darkBtn = document.getElementById('dark-toggle');
const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
if (prefersDark) { document.body.classList.add('dark'); if (darkBtn) darkBtn.textContent = 'Light'; }
if (darkBtn) {
  darkBtn.addEventListener('click', () => {
    document.body.classList.toggle('dark');
    darkBtn.textContent = document.body.classList.contains('dark') ? 'Light' : 'Dark';
  });
}

// ── Mobile Nav ────────────────────────────────────
const navToggle = document.getElementById('nav-toggle');
const navLinks = document.getElementById('nav-links');
if (navToggle && navLinks) {
  navToggle.addEventListener('click', () => {
    const isOpen = navLinks.classList.toggle('open');
    navToggle.setAttribute('aria-expanded', isOpen);
  });
  navLinks.querySelectorAll('a').forEach(link => {
    link.addEventListener('click', () => {
      navLinks.classList.remove('open');
      navToggle.setAttribute('aria-expanded', false);
    });
  });
}

// ── Form Submit ───────────────────────────────────
function handleFormSubmit(e) {
  e.preventDefault();
  const btn = document.getElementById('submit-btn');
  const originalHTML = btn.innerHTML;
  btn.innerHTML = '<span>Message Sent!</span>';
  btn.style.background = 'rgba(245,240,230,0.7)';
  btn.disabled = true;
  setTimeout(() => {
    btn.innerHTML = originalHTML;
    btn.style.background = '';
    btn.disabled = false;
    e.target.reset();
  }, 3000);
}

// ── Subtle Parallax ───────────────────────────────
document.addEventListener('mousemove', e => {
  const hero = document.getElementById('hero');
  if (!hero) return;
  const rect = hero.getBoundingClientRect();
  if (rect.bottom < 0) return;
  const x = (e.clientX / window.innerWidth - 0.5) * 8;
  const y = (e.clientY / window.innerHeight - 0.5) * 8;
  const lines = hero.querySelector('.hero-bg-lines');
  if (lines) lines.style.transform = `translate(${x}px, ${y}px)`;
});
</script>
</body>
</html>
