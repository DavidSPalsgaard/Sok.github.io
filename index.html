<!DOCTYPE html>
<html lang="da">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Søllerød OK — Find vej. Find dig selv.</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,400;0,9..144,600;0,9..144,800;1,9..144,400&family=JetBrains+Mono:wght@300;400;500&family=Inter+Tight:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --ink: #0a1628;
    --paper: #f5efe0;
    --paper-warm: #ece4cf;
    --forest: #1e4d3b;
    --moss: #2d6a4f;
    --blue: #1e3a6f;
    --blue-deep: #0f2749;
    --blue-bright: #2d5aa0;
    --yellow: #f2c94c;
    --yellow-warm: #e5b635;
    --green: #2d6a4f;
    --green-bright: #3d8b66;
    --post: #1e3a6f;
    --post-glow: #2d5aa0;
    --contour: #8a7a4a;
    --accent: #f2c94c;
    --mono: 'JetBrains Mono', monospace;
    --display: 'Fraunces', serif;
    --body: 'Inter Tight', sans-serif;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--paper);
    color: var(--ink);
    font-family: var(--body);
    line-height: 1.5;
    overflow-x: hidden;
  }

  /* Topographic background pattern */
  .topo-bg {
    position: fixed;
    inset: 0;
    z-index: -1;
    opacity: 0.08;
    pointer-events: none;
    background-image: 
      radial-gradient(ellipse 800px 400px at 20% 30%, transparent 40%, var(--contour) 40.5%, transparent 41%),
      radial-gradient(ellipse 700px 350px at 20% 30%, transparent 50%, var(--contour) 50.5%, transparent 51%),
      radial-gradient(ellipse 600px 300px at 20% 30%, transparent 60%, var(--contour) 60.5%, transparent 61%),
      radial-gradient(ellipse 900px 500px at 80% 70%, transparent 35%, var(--contour) 35.5%, transparent 36%),
      radial-gradient(ellipse 800px 450px at 80% 70%, transparent 45%, var(--contour) 45.5%, transparent 46%),
      radial-gradient(ellipse 700px 400px at 80% 70%, transparent 55%, var(--contour) 55.5%, transparent 56%);
  }

  /* Grain overlay */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    z-index: 1;
    pointer-events: none;
    opacity: 0.04;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
  }

  /* === NAVIGATION === */
  nav {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 100;
    padding: 1.25rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgba(244, 234, 213, 0.85);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid rgba(15, 26, 18, 0.1);
  }

  .logo {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    font-family: var(--display);
    font-weight: 800;
    font-size: 1.15rem;
    letter-spacing: -0.02em;
  }

  .logo-mark {
    width: 32px;
    height: 32px;
    position: relative;
  }

  .logo-mark::before,
  .logo-mark::after {
    content: '';
    position: absolute;
  }
  .logo-mark::before {
    inset: 0 50% 0 0;
    background: var(--blue);
  }
  .logo-mark::after {
    inset: 50% 0 0 50%;
    background: var(--yellow);
    border: 2px solid var(--blue);
  }

  nav ul {
    display: flex;
    gap: 2.5rem;
    list-style: none;
    font-family: var(--mono);
    font-size: 0.8rem;
    text-transform: uppercase;
    letter-spacing: 0.1em;
  }

  nav a {
    color: var(--ink);
    text-decoration: none;
    position: relative;
    padding: 0.25rem 0;
    transition: color 0.2s;
  }

  nav a::after {
    content: '';
    position: absolute;
    left: 0;
    bottom: -2px;
    width: 0;
    height: 1px;
    background: var(--post);
    transition: width 0.3s;
  }

  nav a:hover::after { width: 100%; }
  nav a:hover { color: var(--post); }

  .nav-cta {
    background: var(--ink);
    color: var(--paper) !important;
    padding: 0.6rem 1.2rem !important;
    border-radius: 2px;
    font-weight: 500;
    transition: background 0.2s !important;
  }
  .nav-cta:hover { background: var(--post); }
  .nav-cta::after { display: none; }

  /* === HERO === */
  .hero {
    min-height: 100vh;
    padding: 8rem 2rem 4rem;
    position: relative;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
    max-width: 1400px;
    margin: 0 auto;
  }

  .hero-coords {
    position: absolute;
    top: 7rem;
    right: 2rem;
    font-family: var(--mono);
    font-size: 0.7rem;
    color: var(--ink);
    opacity: 0.4;
    letter-spacing: 0.08em;
  }

  .hero-eyebrow {
    font-family: var(--mono);
    font-size: 0.8rem;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    color: var(--blue);
    margin-bottom: 1.5rem;
    display: flex;
    align-items: center;
    gap: 0.75rem;
    opacity: 0;
    animation: fadeUp 0.8s 0.1s forwards;
  }

  .hero-eyebrow::before {
    content: '';
    width: 30px;
    height: 3px;
    background: var(--yellow);
  }

  .hero h1 {
    font-family: var(--display);
    font-weight: 400;
    font-size: clamp(3rem, 7vw, 6rem);
    line-height: 0.95;
    letter-spacing: -0.03em;
    margin-bottom: 2rem;
    opacity: 0;
    animation: fadeUp 0.8s 0.2s forwards;
  }

  .hero h1 em {
    font-style: italic;
    font-weight: 300;
    color: var(--green);
  }

  .hero h1 .strike {
    position: relative;
    display: inline-block;
  }

  .hero h1 .strike::after {
    content: '';
    position: absolute;
    left: -5%;
    right: -5%;
    top: 55%;
    height: 4px;
    background: var(--yellow);
    transform: rotate(-2deg);
    animation: strikeIn 0.6s 1.2s forwards;
    transform-origin: left;
    scale: 0 1;
  }

  @keyframes strikeIn {
    to { scale: 1 1; }
  }

  .hero-lead {
    font-size: 1.2rem;
    max-width: 30rem;
    margin-bottom: 2.5rem;
    color: rgba(15, 26, 18, 0.75);
    opacity: 0;
    animation: fadeUp 0.8s 0.35s forwards;
  }

  .hero-actions {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
    opacity: 0;
    animation: fadeUp 0.8s 0.5s forwards;
  }

  .btn {
    display: inline-flex;
    align-items: center;
    gap: 0.75rem;
    padding: 1rem 1.75rem;
    font-family: var(--mono);
    font-size: 0.85rem;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    text-decoration: none;
    transition: all 0.25s;
    border: none;
    cursor: pointer;
  }

  .btn-primary {
    background: var(--post);
    color: white;
    position: relative;
    overflow: hidden;
  }

  .btn-primary::before {
    content: '';
    position: absolute;
    inset: 0;
    background: var(--ink);
    transform: translateY(100%);
    transition: transform 0.3s;
  }

  .btn-primary span { position: relative; z-index: 1; }
  .btn-primary:hover::before { transform: translateY(0); }

  .btn-secondary {
    background: transparent;
    color: var(--ink);
    border: 1px solid var(--ink);
  }

  .btn-secondary:hover {
    background: var(--ink);
    color: var(--paper);
  }

  /* Hero visual — stylized map */
  .hero-visual {
    position: relative;
    aspect-ratio: 1;
    max-width: 500px;
    justify-self: end;
    opacity: 0;
    animation: fadeIn 1.2s 0.6s forwards;
  }

  .map-frame {
    position: relative;
    width: 100%;
    height: 100%;
    background: #e8dcb8;
    border: 1px solid var(--ink);
    box-shadow: 
      8px 8px 0 var(--ink),
      8px 8px 0 1px var(--ink);
    overflow: hidden;
  }

  .map-svg {
    width: 100%;
    height: 100%;
    display: block;
  }

  .map-label {
    position: absolute;
    font-family: var(--mono);
    font-size: 0.65rem;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: var(--ink);
    opacity: 0.6;
  }

  .map-label.tl { top: 0.75rem; left: 0.75rem; }
  .map-label.br { bottom: 0.75rem; right: 0.75rem; }

  /* === STATS STRIP === */
  .stats {
    background: var(--ink);
    color: var(--paper);
    padding: 3rem 2rem;
    overflow: hidden;
    position: relative;
  }

  .stats-track {
    display: flex;
    gap: 4rem;
    animation: scroll 30s linear infinite;
    white-space: nowrap;
    font-family: var(--display);
    font-style: italic;
    font-size: 2.5rem;
    font-weight: 300;
  }

  .stats-track span {
    display: flex;
    align-items: center;
    gap: 4rem;
  }

  .stats-track span::after {
    content: '✦';
    color: var(--post);
    font-style: normal;
  }

  @keyframes scroll {
    to { transform: translateX(-50%); }
  }

  /* === SECTION: HVAD ER ORIENTERING === */
  .what {
    padding: 8rem 2rem;
    max-width: 1400px;
    margin: 0 auto;
  }

  .section-label {
    font-family: var(--mono);
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    color: var(--post);
    margin-bottom: 1rem;
    display: flex;
    align-items: center;
    gap: 1rem;
  }

  .section-label .num {
    background: var(--post);
    color: white;
    padding: 0.25rem 0.6rem;
    font-weight: 500;
  }

  .what-grid {
    display: grid;
    grid-template-columns: 1fr 1.3fr;
    gap: 6rem;
    align-items: start;
  }

  .what h2 {
    font-family: var(--display);
    font-size: clamp(2.5rem, 5vw, 4rem);
    font-weight: 400;
    line-height: 1;
    letter-spacing: -0.02em;
  }

  .what h2 em {
    font-style: italic;
    font-weight: 300;
  }

  .what-body p {
    font-size: 1.15rem;
    margin-bottom: 1.5rem;
    color: rgba(15, 26, 18, 0.8);
  }

  .what-body p:first-child::first-letter {
    font-family: var(--display);
    font-size: 4.5rem;
    float: left;
    line-height: 0.85;
    padding: 0.25rem 0.75rem 0 0;
    color: var(--post);
    font-weight: 300;
  }

  .pullquote {
    margin: 3rem 0;
    padding: 2rem;
    border-left: 3px solid var(--post);
    font-family: var(--display);
    font-style: italic;
    font-size: 1.5rem;
    line-height: 1.3;
    background: rgba(217, 78, 31, 0.04);
  }

  .pullquote cite {
    display: block;
    margin-top: 1rem;
    font-family: var(--mono);
    font-style: normal;
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: var(--post);
  }

  /* === HOW IT WORKS === */
  .how {
    background: var(--forest);
    color: var(--paper);
    padding: 8rem 2rem;
    position: relative;
    overflow: hidden;
  }

  .how::before {
    content: '';
    position: absolute;
    inset: 0;
    background-image: 
      radial-gradient(ellipse 1200px 600px at 30% 20%, transparent 30%, rgba(168, 139, 92, 0.1) 30.2%, transparent 30.4%),
      radial-gradient(ellipse 1000px 500px at 30% 20%, transparent 40%, rgba(168, 139, 92, 0.1) 40.2%, transparent 40.4%),
      radial-gradient(ellipse 800px 400px at 30% 20%, transparent 50%, rgba(168, 139, 92, 0.1) 50.2%, transparent 50.4%),
      radial-gradient(ellipse 1100px 550px at 70% 80%, transparent 35%, rgba(168, 139, 92, 0.1) 35.2%, transparent 35.4%),
      radial-gradient(ellipse 900px 450px at 70% 80%, transparent 45%, rgba(168, 139, 92, 0.1) 45.2%, transparent 45.4%);
    pointer-events: none;
  }

  .how-inner {
    max-width: 1400px;
    margin: 0 auto;
    position: relative;
  }

  .how h2 {
    font-family: var(--display);
    font-size: clamp(2.5rem, 5vw, 4rem);
    font-weight: 400;
    line-height: 1;
    letter-spacing: -0.02em;
    margin-bottom: 4rem;
    max-width: 18ch;
  }

  .how h2 em { font-style: italic; color: var(--yellow); }

  .steps {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 2rem;
    position: relative;
  }

  .steps::before {
    content: '';
    position: absolute;
    top: 2.5rem;
    left: 5%;
    right: 5%;
    height: 1px;
    background: repeating-linear-gradient(90deg, var(--contour) 0, var(--contour) 8px, transparent 8px, transparent 16px);
    opacity: 0.4;
  }

  .step {
    position: relative;
  }

  .step-num {
    width: 5rem;
    height: 5rem;
    border-radius: 50%;
    background: var(--yellow);
    color: var(--ink);
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: var(--display);
    font-size: 2rem;
    font-weight: 500;
    font-style: italic;
    margin-bottom: 1.5rem;
    position: relative;
    z-index: 1;
    border: 4px solid var(--forest);
  }

  .step h3 {
    font-family: var(--display);
    font-weight: 500;
    font-size: 1.5rem;
    margin-bottom: 0.75rem;
    letter-spacing: -0.01em;
  }

  .step p {
    color: rgba(244, 234, 213, 0.7);
    font-size: 0.95rem;
    line-height: 1.6;
  }

  /* === FAQ / CONCERNS === */
  .concerns {
    padding: 8rem 2rem;
    max-width: 1100px;
    margin: 0 auto;
  }

  .concerns h2 {
    font-family: var(--display);
    font-size: clamp(2.5rem, 5vw, 4rem);
    font-weight: 400;
    line-height: 1;
    letter-spacing: -0.02em;
    margin-bottom: 3rem;
    text-align: center;
  }

  .concerns h2 em { font-style: italic; color: var(--post); }

  .faq-list {
    list-style: none;
  }

  .faq-item {
    border-top: 1px solid rgba(15, 26, 18, 0.15);
    padding: 1.75rem 0;
    cursor: pointer;
    transition: padding 0.3s;
  }

  .faq-item:last-child {
    border-bottom: 1px solid rgba(15, 26, 18, 0.15);
  }

  .faq-q {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 2rem;
    font-family: var(--display);
    font-size: 1.4rem;
    font-weight: 500;
    letter-spacing: -0.01em;
  }

  .faq-toggle {
    width: 2rem;
    height: 2rem;
    flex-shrink: 0;
    position: relative;
    transition: transform 0.3s;
  }

  .faq-toggle::before,
  .faq-toggle::after {
    content: '';
    position: absolute;
    background: var(--post);
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
  .faq-toggle::before { width: 1rem; height: 2px; }
  .faq-toggle::after { width: 2px; height: 1rem; transition: transform 0.3s; }

  .faq-item.open .faq-toggle::after { transform: translate(-50%, -50%) rotate(90deg); }

  .faq-a {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.4s, margin 0.3s;
    color: rgba(15, 26, 18, 0.75);
    font-size: 1.05rem;
    line-height: 1.6;
    max-width: 55ch;
  }

  .faq-item.open .faq-a {
    max-height: 300px;
    margin-top: 1rem;
  }

  /* === TRAINING SCHEDULE === */
  .schedule {
    background: var(--paper-warm);
    padding: 8rem 2rem;
    position: relative;
  }

  .schedule-inner {
    max-width: 1200px;
    margin: 0 auto;
  }

  .schedule-head {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    margin-bottom: 3rem;
    flex-wrap: wrap;
    gap: 2rem;
  }

  .schedule h2 {
    font-family: var(--display);
    font-size: clamp(2.5rem, 5vw, 4rem);
    font-weight: 400;
    line-height: 1;
    letter-spacing: -0.02em;
    max-width: 14ch;
  }
  .schedule h2 em { font-style: italic; color: var(--post); }

  .schedule-legend {
    font-family: var(--mono);
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: rgba(15, 26, 18, 0.6);
  }

  .schedule-legend span {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    margin-right: 1.5rem;
  }

  .dot {
    width: 10px;
    height: 10px;
    border-radius: 50%;
    display: inline-block;
  }
  .dot.beginner { background: var(--post); }
  .dot.all { background: var(--forest); }

  .schedule-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1.5rem;
  }

  .event-card {
    background: var(--paper);
    border: 1px solid var(--ink);
    padding: 2rem;
    position: relative;
    transition: transform 0.25s, box-shadow 0.25s;
  }

  .event-card:hover {
    transform: translate(-4px, -4px);
    box-shadow: 6px 6px 0 var(--ink);
  }

  .event-date {
    font-family: var(--mono);
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.12em;
    color: var(--post);
    margin-bottom: 0.5rem;
  }

  .event-card h3 {
    font-family: var(--display);
    font-weight: 500;
    font-size: 1.4rem;
    margin-bottom: 1rem;
    letter-spacing: -0.01em;
  }

  .event-meta {
    font-family: var(--mono);
    font-size: 0.8rem;
    color: rgba(15, 26, 18, 0.7);
    line-height: 1.7;
    border-top: 1px dashed rgba(15, 26, 18, 0.3);
    padding-top: 1rem;
    margin-top: 1rem;
  }

  .event-meta div {
    display: flex;
    justify-content: space-between;
  }

  .event-badge {
    position: absolute;
    top: 0;
    right: 2rem;
    background: var(--yellow);
    color: var(--ink);
    font-family: var(--mono);
    font-size: 0.65rem;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    padding: 0.4rem 0.8rem;
    font-weight: 600;
    transform: translateY(-50%);
  }

  /* === CTA === */
  .cta {
    padding: 10rem 2rem;
    text-align: center;
    background: var(--ink);
    color: var(--paper);
    position: relative;
    overflow: hidden;
  }

  .cta::before {
    content: '';
    position: absolute;
    top: -100px;
    right: -100px;
    width: 400px;
    height: 400px;
    border-radius: 50%;
    background: radial-gradient(circle, var(--yellow) 0%, transparent 70%);
    opacity: 0.25;
    filter: blur(40px);
  }

  .cta h2 {
    font-family: var(--display);
    font-size: clamp(3rem, 8vw, 7rem);
    font-weight: 300;
    font-style: italic;
    line-height: 0.9;
    letter-spacing: -0.03em;
    margin-bottom: 2rem;
    position: relative;
  }

  .cta h2 .accent {
    font-style: normal;
    font-weight: 600;
    color: var(--yellow);
    display: block;
  }

  .cta p {
    max-width: 40ch;
    margin: 0 auto 3rem;
    font-size: 1.2rem;
    opacity: 0.8;
    position: relative;
  }

  /* === FOOTER === */
  footer {
    background: var(--ink);
    color: var(--paper);
    padding: 3rem 2rem 2rem;
    border-top: 1px solid rgba(244, 234, 213, 0.1);
  }

  .footer-inner {
    max-width: 1400px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 3rem;
    margin-bottom: 3rem;
  }

  .footer-brand {
    font-family: var(--display);
    font-size: 1.5rem;
    font-weight: 400;
    font-style: italic;
    margin-bottom: 1rem;
  }

  .footer-inner h4 {
    font-family: var(--mono);
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    margin-bottom: 1rem;
    color: var(--yellow);
  }

  .footer-inner ul {
    list-style: none;
    font-size: 0.9rem;
    line-height: 2;
  }

  .footer-inner a {
    color: rgba(244, 234, 213, 0.7);
    text-decoration: none;
    transition: color 0.2s;
  }

  .footer-inner a:hover { color: var(--yellow); }

  .footer-bottom {
    max-width: 1400px;
    margin: 0 auto;
    padding-top: 2rem;
    border-top: 1px solid rgba(244, 234, 213, 0.1);
    display: flex;
    justify-content: space-between;
    font-family: var(--mono);
    font-size: 0.75rem;
    color: rgba(244, 234, 213, 0.5);
    flex-wrap: wrap;
    gap: 1rem;
  }

  /* === ANIMATIONS === */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }
  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }

  .reveal {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.8s, transform 0.8s;
  }
  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }

  /* === RESPONSIVE === */
  @media (max-width: 900px) {
    nav ul { display: none; }
    nav { padding: 1rem; }
    .hero {
      grid-template-columns: 1fr;
      padding: 6rem 1.5rem 3rem;
      gap: 3rem;
    }
    .hero-visual { max-width: 100%; justify-self: stretch; }
    .hero-coords { display: none; }
    .what-grid { grid-template-columns: 1fr; gap: 2rem; }
    .steps { grid-template-columns: repeat(2, 1fr); }
    .steps::before { display: none; }
    .schedule-grid { grid-template-columns: 1fr; }
    .footer-inner { grid-template-columns: 1fr 1fr; }
    .what, .how, .concerns, .schedule { padding: 5rem 1.5rem; }
    .cta { padding: 6rem 1.5rem; }
  }

  @media (max-width: 500px) {
    .steps { grid-template-columns: 1fr; }
    .footer-inner { grid-template-columns: 1fr; }
    .hero-actions { flex-direction: column; align-items: stretch; }
    .btn { justify-content: center; }
  }
</style>
</head>
<body>

<div class="topo-bg"></div>

<nav>
  <div class="logo">
    <div class="logo-mark"></div>
    <span>Søllerød OK</span>
  </div>
  <ul>
    <li><a href="#hvad">Hvad er det</a></li>
    <li><a href="#hvordan">Kom i gang</a></li>
    <li><a href="#traening">Træning</a></li>
    <li><a href="#sporgsmal">Spørgsmål</a></li>
  </ul>
  <a href="#tilmeld" class="nav-cta">Kom med næste tirsdag</a>
</nav>

<!-- === HERO === -->
<section class="hero">
  <div class="hero-coords">N 55°46'12" · E 12°31'44" · Skala 1:10.000</div>
  
  <div class="hero-content">
    <div class="hero-eyebrow">Orienteringsklub siden 1972</div>
    <h1>
      <span class="strike">Løb</span> <em>find vej</em><br>
      gennem skoven —<br>
      i dit eget tempo.
    </h1>
    <p class="hero-lead">
      Orientering er løb med kort og kompas. Men først og fremmest er det en undskyldning for at være ude mellem træerne. Vi hjælper dig i gang — også hvis du aldrig har kigget på et kort i dit liv.
    </p>
    <div class="hero-actions">
      <a href="#tilmeld" class="btn btn-primary">
        <span>Kom med til begynder­aften</span>
      </a>
      <a href="#hvad" class="btn btn-secondary">Fortæl mig mere →</a>
    </div>
  </div>

  <div class="hero-visual">
    <div class="map-frame">
      <span class="map-label tl">N · 1:10.000</span>
      <span class="map-label br">Søllerød · DK</span>
      <svg class="map-svg" viewBox="0 0 400 400" preserveAspectRatio="xMidYMid slice">
        <!-- Base color -->
        <rect width="400" height="400" fill="#ede3c6"/>
        
        <!-- Forest green areas -->
        <path d="M 0 80 Q 100 60, 180 100 T 400 90 L 400 180 Q 300 200, 200 180 T 0 200 Z" fill="#a8bf8a" opacity="0.75"/>
        <path d="M 0 240 Q 120 220, 220 260 T 400 250 L 400 340 Q 280 360, 180 340 T 0 360 Z" fill="#a8bf8a" opacity="0.55"/>
        
        <!-- Yellow open land (orienteering "rough open") -->
        <ellipse cx="280" cy="140" rx="55" ry="32" fill="#f2d97a" opacity="0.7"/>
        <ellipse cx="100" cy="300" rx="60" ry="35" fill="#f2d97a" opacity="0.6"/>
        
        <!-- Blue stream/water -->
        <path d="M 50 0 Q 80 100, 150 180 T 280 400" stroke="#2d5aa0" stroke-width="3" fill="none" opacity="0.7"/>
        
        <!-- Contour lines -->
        <g stroke="#8a7a4a" stroke-width="0.8" fill="none" opacity="0.55">
          <path d="M 80 120 Q 160 100, 240 130 T 380 140"/>
          <path d="M 70 140 Q 150 125, 230 155 T 380 165"/>
          <path d="M 60 165 Q 140 150, 220 180 T 380 190"/>
          <path d="M 50 240 Q 130 220, 210 250 T 380 260"/>
          <path d="M 40 265 Q 120 245, 200 275 T 380 285"/>
        </g>
        
        <!-- Trails -->
        <path d="M 0 220 Q 100 200, 200 220 T 400 210" stroke="#6b5228" stroke-width="1" stroke-dasharray="4 3" fill="none"/>
        <path d="M 150 0 Q 170 100, 190 200 T 220 400" stroke="#6b5228" stroke-width="1" stroke-dasharray="4 3" fill="none"/>
        
        <!-- Route line (blue dashes — club color) -->
        <path d="M 80 320 L 150 250 L 240 180 L 320 120" stroke="#1e3a6f" stroke-width="2.5" stroke-dasharray="6 4" fill="none"/>
        
        <!-- Start triangle -->
        <polygon points="80,320 70,335 90,335" fill="none" stroke="#1e3a6f" stroke-width="2.5"/>
        
        <!-- Control circles with numbers -->
        <g fill="none" stroke="#1e3a6f" stroke-width="2.5">
          <circle cx="150" cy="250" r="12"/>
          <circle cx="240" cy="180" r="12"/>
          <circle cx="320" cy="120" r="12"/>
        </g>
        <g font-family="JetBrains Mono, monospace" font-size="11" fill="#1e3a6f" font-weight="600">
          <text x="168" y="250" dominant-baseline="middle">1</text>
          <text x="258" y="180" dominant-baseline="middle">2</text>
          <text x="338" y="120" dominant-baseline="middle">3</text>
        </g>
        
        <!-- Finish double circle -->
        <circle cx="320" cy="120" r="16" fill="none" stroke="#1e3a6f" stroke-width="2"/>
      </svg>
    </div>
  </div>
</section>

<!-- === STATS TICKER === -->
<section class="stats">
  <div class="stats-track">
    <span>240 medlemmer</span>
    <span>52 års historie</span>
    <span>Alle aldre velkomne</span>
    <span>Træning hver tirsdag</span>
    <span>Gratis prøveperiode</span>
    <span>240 medlemmer</span>
    <span>52 års historie</span>
    <span>Alle aldre velkomne</span>
    <span>Træning hver tirsdag</span>
    <span>Gratis prøveperiode</span>
  </div>
</section>

<!-- === HVAD ER DET === -->
<section class="what" id="hvad">
  <div class="section-label reveal"><span class="num">01</span> Om sporten</div>
  <div class="what-grid">
    <div class="reveal">
      <h2>Det handler <em>ikke</em> om at løbe hurtigst.</h2>
    </div>
    <div class="what-body reveal">
      <p>
        Orientering er at finde et antal poster i skoven ved hjælp af et kort. Du bestemmer selv ruten. Du bestemmer selv tempoet. Gå, hvis du vil gå. Løb, hvis du vil løbe. Sæt dig på en træstub og spis din frugt, hvis du har lyst.
      </p>
      <p>
        Den vigtigste færdighed er ikke kondition, men evnen til at tyde et kort og træffe små beslutninger — "over bakken eller udenom?" — igen og igen. Derfor vinder 60-årige ofte over 20-årige. Derfor er det sjovt.
      </p>
      <div class="pullquote">
        "Jeg troede det ville være et eliteløb. Det er mere som en skattejagt for voksne, hvor skoven er legepladsen."
        <cite>— Mette, nyt medlem 2024</cite>
      </div>
    </div>
  </div>
</section>

<!-- === HVORDAN KOMMER JEG I GANG === -->
<section class="how" id="hvordan">
  <div class="how-inner">
    <div class="section-label reveal" style="color: var(--yellow);"><span class="num" style="background: var(--yellow); color: var(--ink);">02</span> Fire skridt</div>
    <h2 class="reveal">Fra nysgerrig til <em>selvstændig</em> på fire tirsdage.</h2>
    <div class="steps">
      <div class="step reveal">
        <div class="step-num">1</div>
        <h3>Dukkop op</h3>
        <p>Tirsdag kl. 17.30 ved klubhuset. Kom i tøj der må blive beskidt. Resten låner du af os — sko, kort, kompas, alt.</p>
      </div>
      <div class="step reveal">
        <div class="step-num">2</div>
        <h3>Vælg en bane</h3>
        <p>Hvid bane er kortest og følger stier. Gul er lidt længere. Din instruktør hjælper dig med at vælge rigtigt.</p>
      </div>
      <div class="step reveal">
        <div class="step-num">3</div>
        <h3>Gå ud</h3>
        <p>Du går — ikke løber — i første omgang. Alene eller med en erfaren makker, som du foretrækker. Ingen tidtagning.</p>
      </div>
      <div class="step reveal">
        <div class="step-num">4</div>
        <h3>Kaffe og snak</h3>
        <p>Bagefter samles vi ved klubhuset. Vi drikker kaffe. Vi snakker om valgte ruter. Vi planlægger næste gang.</p>
      </div>
    </div>
  </div>
</section>

<!-- === SPØRGSMÅL === -->
<section class="concerns" id="sporgsmal">
  <div class="section-label reveal" style="justify-content: center;"><span class="num">03</span> Ærlige svar</div>
  <h2 class="reveal">De <em>bekymringer</em> vi hører oftest.</h2>
  <ul class="faq-list">
    <li class="faq-item reveal">
      <div class="faq-q">
        <span>Jeg er virkelig ikke i form. Er det pinligt?</span>
        <div class="faq-toggle"></div>
      </div>
      <div class="faq-a">Nej. Halvdelen af vores medlemmer begyndte netop fordi de gerne ville ud i naturen og bevæge sig mere. På begynderbanerne går de fleste hele vejen. Du kan ikke være "for dårlig" — kun for nysgerrig eller ikke nysgerrig nok.</div>
    </li>
    <li class="faq-item reveal">
      <div class="faq-q">
        <span>Hvad nu hvis jeg farer vild?</span>
        <div class="faq-toggle"></div>
      </div>
      <div class="faq-a">Det kommer du til. Alle gør. Sporten handler netop om at finde vej igen. På begynderaftenerne har vi erfarne frivillige med fløjter, der patruljerer banerne. Og hver deltager registreres ind og ud — ingen går hjem uden vi ved det.</div>
    </li>
    <li class="faq-item reveal">
      <div class="faq-q">
        <span>Skal jeg have dyrt udstyr?</span>
        <div class="faq-toggle"></div>
      </div>
      <div class="faq-a">Nej. De første fire gange låner du alt af klubben — SportIdent-brik, kompas, kort. Almindelige løbesko eller vandresko er fint. Hvis du senere vil fortsætte, kan du købe specialsko til under 500 kr brugt.</div>
    </li>
    <li class="faq-item reveal">
      <div class="faq-q">
        <span>Er det kun for unge voksne?</span>
        <div class="faq-toggle"></div>
      </div>
      <div class="faq-a">Tværtimod. Vi har medlemmer fra 6 til 84 år. Det er en af meget få sportsgrene, hvor familier kan konkurrere på tværs af generationer — mormor mod teenage-barnebarn, med reelle chancer til begge sider.</div>
    </li>
    <li class="faq-item reveal">
      <div class="faq-q">
        <span>Jeg har ingen at komme med. Er det okay at komme alene?</span>
        <div class="faq-toggle"></div>
      </div>
      <div class="faq-a">Ja — og langt de fleste nye kommer alene. En fra bestyrelsen tager imod dig ved p-pladsen, og efter løbet er der fællesspisning (valgfri). Vi er en lille klub og ingen går hjem uden at have snakket med nogen.</div>
    </li>
  </ul>
</section>

<!-- === TRÆNING === -->
<section class="schedule" id="traening">
  <div class="schedule-inner">
    <div class="schedule-head">
      <div>
        <div class="section-label reveal"><span class="num">04</span> Næste gange</div>
        <h2 class="reveal">Kom forbi en <em>tirsdag</em>.</h2>
      </div>
      <div class="schedule-legend reveal">
        <span><span class="dot beginner"></span> Begynder­venligt</span>
        <span><span class="dot all"></span> Alle niveauer</span>
      </div>
    </div>
    <div class="schedule-grid">
      <div class="event-card reveal">
        <div class="event-badge">Anbefalet</div>
        <div class="event-date">Tirs · 28. april</div>
        <h3>Begynder­aften i Rude Skov</h3>
        <div class="event-meta">
          <div><span>Start</span><span>17.30</span></div>
          <div><span>Varighed</span><span>~90 min</span></div>
          <div><span>Niveau</span><span>● Begynder</span></div>
          <div><span>Pris</span><span>Gratis</span></div>
        </div>
      </div>
      <div class="event-card reveal">
        <div class="event-date">Lør · 2. maj</div>
        <h3>Familieløb ved Søen</h3>
        <div class="event-meta">
          <div><span>Start</span><span>10.00</span></div>
          <div><span>Varighed</span><span>~2 timer</span></div>
          <div><span>Niveau</span><span>● Begynder</span></div>
          <div><span>Pris</span><span>40 kr</span></div>
        </div>
      </div>
      <div class="event-card reveal">
        <div class="event-date">Tirs · 5. maj</div>
        <h3>Teknikaften · kompas</h3>
        <div class="event-meta">
          <div><span>Start</span><span>17.30</span></div>
          <div><span>Varighed</span><span>~90 min</span></div>
          <div><span>Niveau</span><span>● Begynder</span></div>
          <div><span>Pris</span><span>Gratis</span></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- === CTA === -->
<section class="cta" id="tilmeld">
  <h2>
    Din første tirsdag
    <span class="accent">— er gratis.</span>
  </h2>
  <p>Skriv dig op nedenfor, så sender vi en kort mail med hvad du skal medbringe, hvor du parkerer, og hvem der tager imod dig.</p>
  <a href="mailto:ny@sollerod-ok.dk" class="btn btn-primary" style="background: var(--yellow); color: var(--ink);">
    <span>Skriv mig op →</span>
  </a>
</section>

<!-- === FOOTER === -->
<footer>
  <div class="footer-inner">
    <div>
      <div class="footer-brand">Søllerød OK</div>
      <p style="opacity: 0.6; font-size: 0.9rem; max-width: 30ch;">En orienteringsklub for alle, der gerne vil bruge skoven som legeplads — uanset tempo, alder eller erfaring.</p>
    </div>
    <div>
      <h4>Find os</h4>
      <ul>
        <li>Klubhuset</li>
        <li>Skovrideren 42</li>
        <li>2840 Holte</li>
      </ul>
    </div>
    <div>
      <h4>Kontakt</h4>
      <ul>
        <li><a href="mailto:ny@sollerod-ok.dk">ny@sollerod-ok.dk</a></li>
        <li><a href="#">+45 12 34 56 78</a></li>
        <li><a href="#">Facebook</a></li>
        <li><a href="#">Instagram</a></li>
      </ul>
    </div>
    <div>
      <h4>Mere</h4>
      <ul>
        <li><a href="#">Dansk Orienterings­forbund</a></li>
        <li><a href="#">O-track resultater</a></li>
        <li><a href="#">Kortarkiv</a></li>
      </ul>
    </div>
  </div>
  <div class="footer-bottom">
    <div>© 2026 Søllerød OK · CVR 12345678</div>
    <div>Kort: Rudeskov · Geel Skov · Søllerød · 1:10.000</div>
  </div>
</footer>

<script>
  // FAQ accordion
  document.querySelectorAll('.faq-item').forEach(item => {
    item.addEventListener('click', () => {
      item.classList.toggle('open');
    });
  });

  // Scroll reveal
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, { threshold: 0.1 });

  document.querySelectorAll('.reveal').forEach(el => observer.observe(el));

  // Smooth scroll for nav links
  document.querySelectorAll('nav a[href^="#"]').forEach(link => {
    link.addEventListener('click', (e) => {
      const href = link.getAttribute('href');
      if (href.length > 1) {
        e.preventDefault();
        document.querySelector(href)?.scrollIntoView({ behavior: 'smooth' });
      }
    });
  });
</script>

</body>
</html>
