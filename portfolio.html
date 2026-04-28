<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Maçal Gabriel — Game Developer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=Space+Mono:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #080c12;
    --bg2: #0d1420;
    --surface: #111927;
    --border: #1e2d42;
    --accent: #3b82f6;
    --accent2: #60a5fa;
    --moon: #c8d8f0;
    --text: #e2eaf5;
    --muted: #6b7fa3;
    --tag-bg: #152035;
    --tag-color: #60a5fa;
    --card-hover: #131f30;
    --jungle: #22c55e;
    --wyzard: #a855f7;
    --bricks: #f97316;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Space Mono', monospace;
    font-size: 14px;
    line-height: 1.7;
    overflow-x: hidden;
  }

  /* ── NOISE OVERLAY ── */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 0;
    opacity: .4;
  }

  /* ── STAR FIELD ── */
  .stars {
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 0;
    overflow: hidden;
  }
  .stars span {
    position: absolute;
    background: var(--moon);
    border-radius: 50%;
    animation: twinkle var(--d, 4s) var(--delay, 0s) infinite alternate ease-in-out;
    opacity: 0;
  }
  @keyframes twinkle {
    0% { opacity: 0; transform: scale(1); }
    100% { opacity: var(--op, .7); transform: scale(1.4); }
  }

  /* ── NAV ── */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 60px;
    background: linear-gradient(to bottom, rgba(8,12,18,.95), transparent);
    backdrop-filter: blur(2px);
  }
  .nav-logo {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: 18px;
    color: var(--moon);
    letter-spacing: 0.02em;
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .nav-links {
    display: flex;
    gap: 36px;
    list-style: none;
  }
  .nav-links a {
    color: var(--muted);
    text-decoration: none;
    font-size: 12px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    transition: color .2s;
  }
  .nav-links a:hover { color: var(--accent2); }

  /* ── HERO ── */
  .hero {
    position: relative;
    z-index: 1;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 120px 60px 80px;
    overflow: hidden;
  }
  .hero-glow {
    position: absolute;
    width: 600px; height: 600px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(59,130,246,.12) 0%, transparent 70%);
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    pointer-events: none;
  }
  .hero-glow2 {
    position: absolute;
    width: 300px; height: 300px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(200,216,240,.06) 0%, transparent 70%);
    top: 20%; right: 10%;
    pointer-events: none;
  }
  .hero-eyebrow {
    font-size: 11px;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 12px;
  }
  .hero-eyebrow::before {
    content: '';
    display: block;
    width: 40px; height: 1px;
    background: var(--accent);
  }
  .hero-name {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: clamp(52px, 7vw, 110px);
    line-height: 0.92;
    color: var(--moon);
    letter-spacing: -0.02em;
    margin-bottom: 28px;
  }
  .hero-name .accent-dot { color: var(--accent); }
  .hero-title {
    font-family: 'Syne', sans-serif;
    font-size: clamp(18px, 2vw, 26px);
    font-weight: 600;
    color: var(--muted);
    margin-bottom: 32px;
    letter-spacing: 0.01em;
  }
  .hero-bio {
    max-width: 620px;
    color: #8a9fc2;
    line-height: 1.8;
    font-size: 13px;
    margin-bottom: 48px;
  }
  .hero-ctas {
    display: flex;
    gap: 16px;
    flex-wrap: wrap;
  }
  .btn {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 14px 28px;
    border-radius: 4px;
    font-family: 'Space Mono', monospace;
    font-size: 12px;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    text-decoration: none;
    transition: all .25s;
    cursor: pointer;
    border: none;
  }
  .btn-primary {
    background: var(--accent);
    color: #fff;
    box-shadow: 0 0 24px rgba(59,130,246,.3);
  }
  .btn-primary:hover {
    background: var(--accent2);
    box-shadow: 0 0 36px rgba(59,130,246,.5);
    transform: translateY(-2px);
  }
  .btn-outline {
    border: 1px solid var(--border);
    color: var(--muted);
    background: transparent;
  }
  .btn-outline:hover {
    border-color: var(--accent);
    color: var(--accent2);
    transform: translateY(-2px);
  }

  /* ── SECTION ── */
  section {
    position: relative;
    z-index: 1;
    padding: 100px 60px;
  }
  .section-label {
    font-size: 11px;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 12px;
    display: flex;
    align-items: center;
    gap: 12px;
  }
  .section-label::before {
    content: '';
    display: block;
    width: 28px; height: 1px;
    background: var(--accent);
  }
  .section-title {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: clamp(32px, 4vw, 56px);
    line-height: 1.05;
    color: var(--moon);
    margin-bottom: 60px;
    letter-spacing: -0.01em;
  }

  /* ── DIVIDER ── */
  .divider {
    width: 100%;
    height: 1px;
    background: linear-gradient(to right, transparent, var(--border), transparent);
    margin: 0 60px;
    width: calc(100% - 120px);
    position: relative;
    z-index: 1;
  }

  /* ── FEATURED GAMES ── */
  .featured-games {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 28px;
    margin-bottom: 60px;
  }

  .game-card-featured {
    position: relative;
    border-radius: 12px;
    overflow: hidden;
    background: var(--surface);
    border: 1px solid var(--border);
    transition: all .35s;
    cursor: pointer;
    text-decoration: none;
    display: block;
  }
  .game-card-featured:hover {
    transform: translateY(-6px);
    border-color: var(--accent);
    box-shadow: 0 20px 60px rgba(0,0,0,.5), 0 0 0 1px var(--accent);
  }

  .game-card-featured.jungle:hover { border-color: var(--jungle); box-shadow: 0 20px 60px rgba(0,0,0,.5), 0 0 30px rgba(34,197,94,.15); }
  .game-card-featured.wyzard:hover { border-color: var(--wyzard); box-shadow: 0 20px 60px rgba(0,0,0,.5), 0 0 30px rgba(168,85,247,.15); }
  .game-card-featured.bricks:hover { border-color: var(--bricks); box-shadow: 0 20px 60px rgba(0,0,0,.5), 0 0 30px rgba(249,115,22,.15); }

  .game-banner {
    width: 100%;
    height: 200px;
    object-fit: cover;
    display: block;
  }
  .game-banner-placeholder {
    width: 100%;
    height: 200px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 64px;
    position: relative;
    overflow: hidden;
  }
  .jungle .game-banner-placeholder {
    background: linear-gradient(135deg, #0a2515 0%, #1a4a25 50%, #0f3820 100%);
  }
  .wyzard .game-banner-placeholder {
    background: linear-gradient(135deg, #1a0a35 0%, #3b1a6b 50%, #250a45 100%);
  }
  .bricks .game-banner-placeholder {
    background: linear-gradient(135deg, #1f0a00 0%, #7c2d12 50%, #431407 100%);
  }
  .game-banner-placeholder::before {
    content: '';
    position: absolute;
    inset: 0;
    background: repeating-linear-gradient(
      45deg,
      transparent,
      transparent 20px,
      rgba(255,255,255,.02) 20px,
      rgba(255,255,255,.02) 40px
    );
  }
  .game-banner-img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    display: block;
  }
  .featured-badge {
    position: absolute;
    top: 14px;
    left: 14px;
    padding: 4px 10px;
    border-radius: 3px;
    font-size: 9px;
    font-weight: 700;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    display: flex;
    align-items: center;
    gap: 5px;
  }
  .jungle .featured-badge {
    background: rgba(34,197,94,.2);
    color: var(--jungle);
    border: 1px solid rgba(34,197,94,.4);
  }
  .wyzard .featured-badge {
    background: rgba(168,85,247,.2);
    color: var(--wyzard);
    border: 1px solid rgba(168,85,247,.4);
  }
  .bricks .featured-badge {
    background: rgba(249,115,22,.2);
    color: var(--bricks);
    border: 1px solid rgba(249,115,22,.4);
  }
  .featured-badge::before {
    content: '★';
    font-size: 10px;
  }

  .game-body {
    padding: 24px;
  }
  .game-name {
    font-family: 'Syne', sans-serif;
    font-size: 22px;
    font-weight: 800;
    color: var(--moon);
    margin-bottom: 8px;
  }
  .game-studio-tag {
    font-size: 10px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 12px;
  }
  .game-desc {
    font-size: 12px;
    color: #7a92b8;
    line-height: 1.7;
    margin-bottom: 18px;
  }
  .game-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 20px;
  }
  .tag {
    padding: 4px 10px;
    border-radius: 3px;
    font-size: 10px;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    background: var(--tag-bg);
    color: var(--tag-color);
    border: 1px solid rgba(59,130,246,.15);
  }
  .jungle .tag {
    background: rgba(34,197,94,.08);
    color: #4ade80;
    border-color: rgba(34,197,94,.15);
  }
  .wyzard .tag {
    background: rgba(168,85,247,.08);
    color: #c084fc;
    border-color: rgba(168,85,247,.15);
  }
  .bricks .tag {
    background: rgba(249,115,22,.08);
    color: #fb923c;
    border-color: rgba(249,115,22,.15);
  }

  /* ── DOWNLOAD STAT ── */
  .download-stat {
    display: flex;
    align-items: center;
    gap: 12px;
    background: rgba(249,115,22,.07);
    border: 1px solid rgba(249,115,22,.2);
    border-radius: 8px;
    padding: 14px 18px;
    margin-bottom: 18px;
  }
  .download-stat-icon {
    font-size: 26px;
    flex-shrink: 0;
  }
  .download-stat-number {
    font-family: 'Syne', sans-serif;
    font-size: 26px;
    font-weight: 800;
    color: var(--bricks);
    line-height: 1;
  }
  .download-stat-label {
    font-size: 10px;
    color: var(--muted);
    letter-spacing: 0.1em;
    text-transform: uppercase;
    margin-top: 2px;
  }
  .download-stat-divider {
    width: 1px;
    height: 36px;
    background: rgba(249,115,22,.2);
    margin: 0 4px;
  }
  .rating-row {
    display: flex;
    align-items: center;
    gap: 4px;
  }
  .rating-stars {
    color: #fbbf24;
    font-size: 12px;
    letter-spacing: -1px;
  }
  .rating-val {
    font-family: 'Syne', sans-serif;
    font-size: 16px;
    font-weight: 700;
    color: #fbbf24;
  }
  .rating-count {
    font-size: 10px;
    color: var(--muted);
  }

  /* ── STORE LINKS ── */
  .store-links {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
  }
  .store-link {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-size: 11px;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--muted);
    transition: color .2s;
    text-decoration: none;
    border: 1px solid var(--border);
    padding: 6px 12px;
    border-radius: 4px;
    background: rgba(255,255,255,.02);
    transition: all .2s;
  }
  .store-link:hover {
    color: var(--bricks);
    border-color: rgba(249,115,22,.4);
    background: rgba(249,115,22,.05);
  }
  .bricks .game-link:hover { color: var(--bricks); }
  .game-link {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-size: 11px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--muted);
    transition: color .2s;
  }
  .jungle .game-link:hover { color: var(--jungle); }
  .wyzard .game-link:hover { color: var(--wyzard); }
  .game-link:hover { color: var(--accent2); }
  .steam-icon {
    width: 16px; height: 16px;
    fill: currentColor;
  }
  .coming-soon-pill {
    display: inline-flex;
    align-items: center;
    gap: 5px;
    padding: 3px 10px;
    border-radius: 20px;
    font-size: 10px;
    font-weight: 700;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    margin-left: 10px;
  }
  .jungle .coming-soon-pill {
    background: rgba(34,197,94,.1);
    color: var(--jungle);
    border: 1px solid rgba(34,197,94,.2);
  }
  .coming-soon-pill .pulse {
    width: 5px; height: 5px;
    border-radius: 50%;
    background: currentColor;
    animation: pulse 1.4s infinite;
  }
  @keyframes pulse {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.3; }
  }

  /* ── SKILLS ── */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 24px;
  }
  .skill-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 28px;
    transition: all .3s;
  }
  .skill-card:hover {
    border-color: rgba(59,130,246,.4);
    background: var(--card-hover);
    transform: translateY(-3px);
  }
  .skill-icon {
    font-size: 28px;
    margin-bottom: 16px;
    display: block;
  }
  .skill-name {
    font-family: 'Syne', sans-serif;
    font-size: 16px;
    font-weight: 700;
    color: var(--moon);
    margin-bottom: 10px;
  }
  .skill-desc {
    font-size: 12px;
    color: var(--muted);
    line-height: 1.7;
    margin-bottom: 16px;
  }
  .skill-bars {
    display: flex;
    flex-direction: column;
    gap: 8px;
  }
  .skill-bar-row {
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .skill-bar-label {
    font-size: 10px;
    color: var(--muted);
    width: 70px;
    flex-shrink: 0;
    letter-spacing: 0.05em;
  }
  .skill-bar-track {
    flex: 1;
    height: 3px;
    background: var(--border);
    border-radius: 2px;
    overflow: hidden;
  }
  .skill-bar-fill {
    height: 100%;
    border-radius: 2px;
    background: linear-gradient(to right, var(--accent), var(--accent2));
    transform-origin: left;
    animation: fillBar 1.2s cubic-bezier(.4,0,.2,1) forwards;
    transform: scaleX(0);
  }
  @keyframes fillBar {
    to { transform: scaleX(1); }
  }

  /* ── ABOUT / BIO ── */
  .about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    align-items: center;
  }
  .about-text h3 {
    font-family: 'Syne', sans-serif;
    font-size: 28px;
    font-weight: 700;
    color: var(--moon);
    margin-bottom: 20px;
  }
  .about-text p {
    font-size: 13px;
    color: #8a9fc2;
    line-height: 1.85;
    margin-bottom: 16px;
  }
  .stats-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }
  .stats-grid .stat-card:first-child {
    grid-column: span 2;
    background: linear-gradient(135deg, rgba(249,115,22,.08), rgba(249,115,22,.03));
    border-color: rgba(249,115,22,.2);
  }
  .stats-grid .stat-card:first-child .stat-number {
    color: var(--bricks);
    font-size: 52px;
  }
  .stat-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 24px 20px;
    text-align: center;
  }
  .stat-number {
    font-family: 'Syne', sans-serif;
    font-size: 40px;
    font-weight: 800;
    color: var(--accent2);
    line-height: 1;
    margin-bottom: 8px;
  }
  .stat-label {
    font-size: 11px;
    color: var(--muted);
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  /* ── FOOTER ── */
  footer {
    position: relative;
    z-index: 1;
    padding: 60px;
    border-top: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
  }
  .footer-brand {
    font-family: 'Syne', sans-serif;
    font-size: 20px;
    font-weight: 800;
    color: var(--moon);
  }
  .footer-copy {
    font-size: 11px;
    color: var(--muted);
    margin-top: 4px;
  }
  .footer-links {
    display: flex;
    gap: 24px;
  }
  .footer-links a {
    color: var(--muted);
    text-decoration: none;
    font-size: 12px;
    transition: color .2s;
    display: flex;
    align-items: center;
    gap: 6px;
  }
  .footer-links a:hover { color: var(--accent2); }

  /* ── SCROLL ANIMATIONS ── */
  .reveal {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity .7s cubic-bezier(.4,0,.2,1), transform .7s cubic-bezier(.4,0,.2,1);
  }
  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }
  .reveal-delay-1 { transition-delay: .1s; }
  .reveal-delay-2 { transition-delay: .2s; }
  .reveal-delay-3 { transition-delay: .3s; }

  @media (max-width: 900px) {
    nav { padding: 20px 24px; }
    .hero { padding: 120px 24px 60px; }
    section { padding: 60px 24px; }
    .divider { margin: 0 24px; width: calc(100% - 48px); }
    .featured-games { grid-template-columns: 1fr; }
    .skills-grid { grid-template-columns: 1fr; }
    .about-grid { grid-template-columns: 1fr; gap: 40px; }
    footer { padding: 40px 24px; flex-direction: column; align-items: flex-start; }
    .nav-links { display: none; }
  }
</style>
</head>
<body>

<!-- Stars -->
<div class="stars" id="stars"></div>

<!-- Nav -->
<nav>
  <div class="nav-logo">
    Maçal Gabriel
  </div>
  <ul class="nav-links">
    <li><a href="#games">Games</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="mailto:macalgabriel@email.com">Contact</a></li>
  </ul>
</nav>

<!-- Hero -->
<section class="hero">
  <div class="hero-glow"></div>
  <div class="hero-glow2"></div>

  <p class="hero-eyebrow">Game Developer &amp; Lead</p>
  <h1 class="hero-name">Maçal<br>Gabriel<span class="accent-dot">.</span></h1>
  <p class="hero-title">Multiplayer · Unreal Engine · Unity · AI Systems</p>
  <p class="hero-bio">
    Passionate about game development since graduating in Digital Games from Unoeste. Over three years of experience in multiplayer game development using Unreal Engine and Unity — specializing in dynamic gameplay systems, seamless online experiences, and AI behaviors. Project Manager and Lead Developer committed to delivering high-quality, captivating player experiences.
  </p>
  <div class="hero-ctas">
    <a href="#games" class="btn btn-primary">View My Games</a>
    <a href="#about" class="btn btn-outline">About Me</a>
  </div>
</section>

<div class="divider"></div>

<!-- Featured Games -->
<section id="games">
  <p class="section-label">Featured Projects</p>
  <h2 class="section-title">Games</h2>

  <div class="featured-games">

    <!-- Jungle Defenders -->
    <a class="game-card-featured jungle reveal" href="https://store.steampowered.com/app/3758070/Jungle_Defenders/" target="_blank" rel="noopener">
      <div class="featured-badge">Priority Release</div>
      <div class="game-banner-placeholder">
        <img
          class="game-banner-img"
          src="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/3758070/7782a9892d1a09e6e2e7c77ccd35125b271d2abe/header.jpg?t=1772065733"
          alt="Jungle Defenders"
          onerror="this.style.display='none'; this.parentElement.innerHTML += '🌿';"
        >
      </div>
      <div class="game-body">
        <div class="game-name">Jungle Defenders</div>
        <div class="game-studio-tag">LOS MONOS HERMANOS &nbsp;·&nbsp; Steam</div>
        <p class="game-desc">
          A wild third-person action roguelike bullet hell where nature strikes back. Play as fearless animals sworn to protect their forest from an invasion of resource-hungry robots bent on destroying the environment.
        </p>
        <div class="game-tags">
          <span class="tag">Roguelike</span>
          <span class="tag">Bullet Hell</span>
          <span class="tag">3rd Person</span>
          <span class="tag">Action</span>
        </div>
        <span class="game-link">
          <svg class="steam-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M11.979 0C5.678 0 .511 4.86.022 11.037l6.432 2.658c.545-.371 1.203-.59 1.912-.59.063 0 .125.004.188.006l2.861-4.142V8.91c0-2.495 2.028-4.524 4.524-4.524 2.494 0 4.524 2.029 4.524 4.524s-2.03 4.525-4.524 4.525h-.105l-4.076 2.911c0 .052.004.105.004.159 0 1.875-1.515 3.396-3.39 3.396-1.635 0-3.016-1.173-3.331-2.727L.436 15.27C1.862 20.307 6.486 24 11.979 24c6.627 0 11.999-5.373 11.999-12S18.606 0 11.979 0zM7.54 18.21l-1.473-.61c.262.543.714.999 1.314 1.25 1.297.539 2.793-.076 3.332-1.375.263-.63.264-1.319.005-1.949s-.75-1.121-1.377-1.383c-.624-.26-1.29-.249-1.878-.03l1.523.63c.956.4 1.409 1.5 1.009 2.455-.397.957-1.497 1.41-2.454 1.012H7.54zm11.415-9.303c0-1.662-1.353-3.015-3.015-3.015-1.665 0-3.015 1.353-3.015 3.015 0 1.665 1.35 3.015 3.015 3.015 1.662 0 3.015-1.35 3.015-3.015zm-5.273-.005c0-1.252 1.013-2.266 2.265-2.266 1.249 0 2.266 1.014 2.266 2.266 0 1.251-1.017 2.265-2.266 2.265-1.252 0-2.265-1.014-2.265-2.265z"/></svg>
          View on Steam
          <span class="coming-soon-pill">
            <span class="pulse"></span>
            Coming Soon
          </span>
        </span>
      </div>
    </a>

    <!-- Wyzards -->
    <a class="game-card-featured wyzard reveal reveal-delay-1" href="#" target="_blank" rel="noopener">
      <div class="featured-badge">Priority Release</div>
      <div class="game-banner-placeholder">
        🧙
      </div>
      <div class="game-body">
        <div class="game-name">Wyzards</div>
        <div class="game-studio-tag">In Development</div>
        <p class="game-desc">
          An arcane multiplayer experience where wizards battle for dominance through strategic spell-casting, arcane mastery, and tactical team play. Built on Unreal Engine with a deep Gameplay Ability System foundation.
        </p>
        <div class="game-tags">
          <span class="tag">Multiplayer</span>
          <span class="tag">Unreal Engine</span>
          <span class="tag">GAS</span>
          <span class="tag">Competitive</span>
        </div>
        <span class="game-link">
          <svg class="steam-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
          Coming Soon
        </span>
      </div>
    </a>

    <!-- Bricks King -->
    <div class="game-card-featured bricks reveal reveal-delay-2">
      <div class="featured-badge">5M+ Downloads</div>
      <div class="game-banner-placeholder">
        <img
          class="game-banner-img"
          src="https://play-lh.googleusercontent.com/PGZv4W_or-0Gj6-UVtVK_mZXqfMq6tINVhvZjIDPEn5xgGJqk1h4VRN7OOujGbMHznY=w526-h296"
          alt="Bricks King"
          onerror="this.style.display='none'; this.parentElement.innerHTML += '🧱';"
        >
      </div>
      <div class="game-body">
        <div class="game-name">Bricks King</div>
        <div class="game-studio-tag">Prota Games &nbsp;·&nbsp; Mobile</div>

        <div class="download-stat">
          <span class="download-stat-icon">📲</span>
          <div>
            <div class="download-stat-number">5M+</div>
            <div class="download-stat-label">Downloads</div>
          </div>
          <div class="download-stat-divider"></div>
          <div>
            <div class="rating-row">
              <span class="rating-stars">★★★★★</span>
              <span class="rating-val">4.6</span>
            </div>
            <div class="rating-count">17.8K reviews</div>
          </div>
        </div>

        <p class="game-desc">
          A casual brick-breaker with over 300 levels, unique power-ups, and addictive mechanics. One of the most downloaded mobile games in the portfolio, available on Android and iOS.
        </p>
        <div class="game-tags">
          <span class="tag">Mobile</span>
          <span class="tag">Casual</span>
          <span class="tag">Android</span>
          <span class="tag">iOS</span>
          <span class="tag">300+ Levels</span>
        </div>
        <div class="store-links">
          <a class="store-link" href="https://play.google.com/store/apps/details?id=com.protagames.bricks&hl=pt" target="_blank" rel="noopener">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M3.609 1.814L13.792 12 3.61 22.186a.996.996 0 01-.61-.92V2.734a1 1 0 01.609-.92zm10.89 10.893l2.302 2.302-10.937 6.333 8.635-8.635zm3.199-1.303a1 1 0 010 1.192L15.396 14.4l-2.595-2.596 2.595-2.595 2.302 1.895zM5.864 3.658L16.8 9.99l-2.302 2.302-8.635-8.634z"/></svg>
            Google Play
          </a>
          <a class="store-link" href="https://apps.apple.com/us/app/bricks-king/id6444596798" target="_blank" rel="noopener">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>
            App Store
          </a>
        </div>
      </div>
    </div>

  </div>
</section>

<div class="divider"></div>

<!-- Skills -->
<section id="skills">
  <p class="section-label">Expertise</p>
  <h2 class="section-title">Skills</h2>

  <div class="skills-grid">
    <div class="skill-card reveal">
      <span class="skill-icon">⚡</span>
      <div class="skill-name">Unreal Engine</div>
      <p class="skill-desc">Deep expertise in UE5, Blueprints, C++, Gameplay Ability System (GAS), multiplayer architecture, and AI behavior trees.</p>
      <div class="skill-bars">
        <div class="skill-bar-row">
          <span class="skill-bar-label">C++</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:90%"></div></div>
        </div>
        <div class="skill-bar-row">
          <span class="skill-bar-label">Blueprints</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:95%"></div></div>
        </div>
        <div class="skill-bar-row">
          <span class="skill-bar-label">GAS</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:88%"></div></div>
        </div>
      </div>
    </div>

    <div class="skill-card reveal reveal-delay-1">
      <span class="skill-icon">🎮</span>
      <div class="skill-name">Unity</div>
      <p class="skill-desc">Proficient in Unity game development using C#, with extensive experience in multiplayer networking and AI systems.</p>
      <div class="skill-bars">
        <div class="skill-bar-row">
          <span class="skill-bar-label">C#</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:92%"></div></div>
        </div>
        <div class="skill-bar-row">
          <span class="skill-bar-label">Netcode</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:85%"></div></div>
        </div>
        <div class="skill-bar-row">
          <span class="skill-bar-label">AI/NPC</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:87%"></div></div>
        </div>
      </div>
    </div>

    <div class="skill-card reveal reveal-delay-2">
      <span class="skill-icon">🌐</span>
      <div class="skill-name">Multiplayer</div>
      <p class="skill-desc">Specialized in building seamless online experiences — server architecture, replication, lag compensation, and lobby systems.</p>
      <div class="skill-bars">
        <div class="skill-bar-row">
          <span class="skill-bar-label">Replication</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:90%"></div></div>
        </div>
        <div class="skill-bar-row">
          <span class="skill-bar-label">Lobbies</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:88%"></div></div>
        </div>
        <div class="skill-bar-row">
          <span class="skill-bar-label">NetCode</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:84%"></div></div>
        </div>
      </div>
    </div>

    <div class="skill-card reveal">
      <span class="skill-icon">🤖</span>
      <div class="skill-name">AI Systems</div>
      <p class="skill-desc">Designing intelligent enemy behaviors, behavior trees, state machines, and perception systems for Unreal and Unity.</p>
      <div class="skill-bars">
        <div class="skill-bar-row">
          <span class="skill-bar-label">Behavior Tree</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:91%"></div></div>
        </div>
        <div class="skill-bar-row">
          <span class="skill-bar-label">Perception</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:86%"></div></div>
        </div>
      </div>
    </div>

    <div class="skill-card reveal reveal-delay-1">
      <span class="skill-icon">📋</span>
      <div class="skill-name">Project Management</div>
      <p class="skill-desc">Lead Developer and PM experience — guiding cross-functional teams, sprint planning, and shipping quality games on schedule.</p>
      <div class="skill-bars">
        <div class="skill-bar-row">
          <span class="skill-bar-label">Leadership</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:90%"></div></div>
        </div>
        <div class="skill-bar-row">
          <span class="skill-bar-label">Agile</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:85%"></div></div>
        </div>
      </div>
    </div>

    <div class="skill-card reveal reveal-delay-2">
      <span class="skill-icon">🛠️</span>
      <div class="skill-name">Gameplay Systems</div>
      <p class="skill-desc">Architecting robust gameplay loops, ability systems, progression mechanics, and game feel through careful design iteration.</p>
      <div class="skill-bars">
        <div class="skill-bar-row">
          <span class="skill-bar-label">Design</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:88%"></div></div>
        </div>
        <div class="skill-bar-row">
          <span class="skill-bar-label">Prototyping</span>
          <div class="skill-bar-track"><div class="skill-bar-fill" style="width:93%"></div></div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- About -->
<section id="about">
  <p class="section-label">Background</p>
  <h2 class="section-title">About Me</h2>

  <div class="about-grid">
    <div class="about-text reveal">
      <h3>Building Worlds,<br>One System at a Time</h3>
      <p>
        I'm Maçal Gabriel, a game developer and lead from Brazil. I graduated in Digital Games from Faculdade do Oeste Paulista (Unoeste) and have been building multiplayer experiences ever since — with a deep passion for systems design and online play.
      </p>
      <p>
        My core strength is making complex technical systems feel natural and fun. Whether it's architecting a Gameplay Ability System in Unreal Engine, programming emergent AI behavior, or leading a team through a tight production cycle — I love bringing ambitious ideas to life.
      </p>
      <p>
        Currently working on <strong style="color:var(--jungle)">Jungle Defenders</strong> and <strong style="color:var(--wyzard)">Wyzards</strong>, and co-developed <strong style="color:var(--bricks)">Bricks King</strong> — a mobile hit with over <strong style="color:var(--bricks)">5 million downloads</strong>.
      </p>
    </div>

    <div class="stats-grid reveal reveal-delay-1">
      <div class="stat-card">
        <div class="stat-number">5M+</div>
        <div class="stat-label">Mobile Downloads</div>
      </div>
      <div class="stat-card">
        <div class="stat-number">3+</div>
        <div class="stat-label">Years Experience</div>
      </div>
      <div class="stat-card">
        <div class="stat-number">3</div>
        <div class="stat-label">Featured Games</div>
      </div>
      <div class="stat-card">
        <div class="stat-number">UE5</div>
        <div class="stat-label">Primary Engine</div>
      </div>
      <div class="stat-card">
        <div class="stat-number">C++</div>
        <div class="stat-label">Core Language</div>
      </div>
    </div>
  </div>
</section>

<!-- Footer -->
<footer>
  <div>
    <div class="footer-brand">Maçal Gabriel</div>
    <div class="footer-copy">© 2025 Maçal Gabriel. All rights reserved.</div>
  </div>
  <div class="footer-links">
    <a href="https://store.steampowered.com/app/3758070/Jungle_Defenders/" target="_blank">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M11.979 0C5.678 0 .511 4.86.022 11.037l6.432 2.658c.545-.371 1.203-.59 1.912-.59.063 0 .125.004.188.006l2.861-4.142V8.91c0-2.495 2.028-4.524 4.524-4.524 2.494 0 4.524 2.029 4.524 4.524s-2.03 4.525-4.524 4.525h-.105l-4.076 2.911c0 .052.004.105.004.159 0 1.875-1.515 3.396-3.39 3.396-1.635 0-3.016-1.173-3.331-2.727L.436 15.27C1.862 20.307 6.486 24 11.979 24c6.627 0 11.999-5.373 11.999-12S18.606 0 11.979 0z"/></svg>
      Steam
    </a>
    <a href="https://github.com/" target="_blank">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0 1 12 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
      GitHub
    </a>
    <a href="mailto:macalgabriel@email.com">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
      Contact
    </a>
  </div>
</footer>

<script>
  // Stars
  const starsEl = document.getElementById('stars');
  for (let i = 0; i < 120; i++) {
    const s = document.createElement('span');
    const size = Math.random() * 2 + 0.5;
    s.style.cssText = `
      width:${size}px;height:${size}px;
      top:${Math.random()*100}%;
      left:${Math.random()*100}%;
      --d:${3+Math.random()*5}s;
      --delay:${Math.random()*6}s;
      --op:${0.3+Math.random()*0.6};
    `;
    starsEl.appendChild(s);
  }

  // Scroll reveal
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) {
        e.target.classList.add('visible');
        observer.unobserve(e.target);
      }
    });
  }, { threshold: 0.1 });
  document.querySelectorAll('.reveal').forEach(el => observer.observe(el));
</script>
</body>
</html>
