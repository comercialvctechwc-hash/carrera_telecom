<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Carrera Telecom | Representação Comercial em Telecomunicações</title>
  <meta name="description" content="Carrera Telecom: representação comercial em telecomunicações, conectando clientes a soluções de internet, TV, mobilidade, Wi‑Fi e tecnologia." />
  <meta name="keywords" content="Carrera Telecom, representação comercial telecom, telecomunicações, conectividade, fibra óptica, TV, móvel, Wi-Fi, Tijucas SC" />
  <meta name="author" content="Carrera Telecom" />
  <meta name="robots" content="index, follow" />
  <meta property="og:title" content="Carrera Telecom | Representação Comercial em Telecomunicações" />
  <meta property="og:description" content="Mais do que representar serviços, representamos soluções que conectam negócios e pessoas." />
  <meta property="og:type" content="website" />
  <meta property="og:locale" content="pt_BR" />
  <meta name="theme-color" content="#8d0f12" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
  <style>
    :root {
      --black: #090303;
      --black-2: #130707;
      --red: #8f1014;
      --red-2: #c91920;
      --red-3: #430607;
      --yellow: #f2bc2f;
      --yellow-2: #ffe08a;
      --cream: #fff4de;
      --cream-2: #fff9ed;
      --text: #fff8ec;
      --muted: #dcc1b2;
      --muted-dark: #67483f;
      --line: rgba(255,255,255,.13);
      --line-dark: rgba(62,25,20,.14);
      --max: 1160px;
      --shadow: 0 28px 80px rgba(0,0,0,.35);
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      font-family: 'Inter', system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background: var(--black);
      color: var(--text);
      line-height: 1.55;
      overflow-x: hidden;
    }
    a { color: inherit; text-decoration: none; }
    svg { display: block; }
    p { color: var(--muted); }
    .container { width: min(var(--max), calc(100% - 44px)); margin: 0 auto; }

    .reveal {
      opacity: 0;
      transform: translateY(26px);
      transition: opacity .72s ease, transform .72s ease;
    }
    .reveal.is-visible { opacity: 1; transform: translateY(0); }
    .delay-1 { transition-delay: .08s; }
    .delay-2 { transition-delay: .16s; }
    .delay-3 { transition-delay: .24s; }

    .topbar {
      position: sticky;
      top: 0;
      z-index: 100;
      background: rgba(9,3,3,.78);
      border-bottom: 1px solid var(--line);
      backdrop-filter: blur(18px);
    }
    .nav {
      height: 76px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 22px;
    }
    .brand {
      display: flex;
      align-items: center;
      gap: 12px;
      min-width: max-content;
    }
    .brand-badge {
      width: 48px;
      height: 48px;
      border-radius: 50%;
      display: grid;
      place-items: center;
      background: linear-gradient(145deg, #ffe08a 0%, var(--yellow) 58%, #d68b12 100%);
      border: 3px solid rgba(255,255,255,.94);
      color: #190606;
      box-shadow: 0 16px 34px rgba(242,188,47,.18);
      font-weight: 900;
      font-size: 13px;
      letter-spacing: -.8px;
      font-style: italic;
    }
    .brand strong { display: block; font-size: 15px; letter-spacing: .1px; }
    .brand span { display: block; color: var(--muted); font-size: 12px; margin-top: -2px; }
    .menu { display: flex; gap: 24px; align-items: center; color: #ead0c0; font-size: 14px; font-weight: 750; }
    .menu a { opacity: .86; transition: .18s ease; }
    .menu a:hover { opacity: 1; color: var(--yellow-2); }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      min-height: 50px;
      padding: 14px 20px;
      border-radius: 999px;
      border: 1px solid rgba(255,255,255,.15);
      font-weight: 850;
      transition: transform .18s ease, box-shadow .18s ease, background .18s ease;
      white-space: nowrap;
    }
    .btn:hover { transform: translateY(-2px); }
    .btn-primary {
      background: linear-gradient(135deg, var(--yellow), #ffb928 42%, var(--red-2));
      color: #210606;
      border-color: transparent;
      box-shadow: 0 18px 46px rgba(201,25,32,.24), 0 8px 24px rgba(242,188,47,.13);
    }
    .btn-secondary { background: rgba(255,255,255,.065); color: var(--cream); }

    .hero {
      position: relative;
      min-height: calc(100vh - 76px);
      display: grid;
      align-items: center;
      padding: 70px 0 86px;
      overflow: hidden;
      background:
        radial-gradient(circle at 17% 8%, rgba(201,25,32,.28), transparent 32%),
        radial-gradient(circle at 82% 22%, rgba(242,188,47,.14), transparent 30%),
        linear-gradient(135deg, #130606 0%, #090303 46%, #160606 100%);
    }
    .hero::before {
      content: '';
      position: absolute;
      inset: 0;
      background-image:
        linear-gradient(rgba(255,255,255,.035) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,.035) 1px, transparent 1px);
      background-size: 50px 50px;
      mask-image: linear-gradient(90deg, black, rgba(0,0,0,.8), transparent 88%);
      pointer-events: none;
    }
    .hero::after {
      content: '';
      position: absolute;
      inset: auto -12% -22% 48%;
      height: 420px;
      background: radial-gradient(circle, rgba(242,188,47,.16), transparent 68%);
      pointer-events: none;
    }
    .page-network {
      position: fixed;
      inset: 0;
      z-index: 0;
      pointer-events: none;
      opacity: .58;
    }
    .page-network svg {
      width: 100%;
      height: 100%;
      display: block;
    }
    .backbone-path {
      stroke-dasharray: 1;
      stroke-dashoffset: 1;
      transition: stroke-dashoffset .28s linear;
      filter: drop-shadow(0 0 10px rgba(242,188,47,.22));
    }
    .network-node {
      opacity: .25;
      transform-origin: center;
      transition: opacity .45s ease, transform .45s ease;
    }
    .network-node.active {
      opacity: 1;
      transform: scale(1.25);
      filter: drop-shadow(0 0 12px rgba(242,188,47,.75));
    }
    .network-dot {
      fill: var(--yellow-2);
      filter: drop-shadow(0 0 10px rgba(242,188,47,.8));
      opacity: .9;
    }
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      z-index: 0;
      pointer-events: none;
      background:
        radial-gradient(circle at var(--mx, 50%) var(--my, 28%), rgba(242,188,47,.075), transparent 20rem),
        radial-gradient(circle at calc(var(--mx, 50%) + 18%) calc(var(--my, 28%) + 12%), rgba(201,25,32,.06), transparent 24rem);
      opacity: .9;
    }
    .hero-grid {
      position: relative;
      z-index: 2;
      display: grid;
      grid-template-columns: 1.02fr .98fr;
      gap: 58px;
      align-items: center;
    }
    .eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 9px;
      color: var(--yellow-2);
      background: rgba(242,188,47,.08);
      border: 1px solid rgba(242,188,47,.24);
      border-radius: 999px;
      padding: 9px 13px;
      font-size: 13px;
      font-weight: 900;
      margin-bottom: 24px;
    }
    .eyebrow svg { width: 17px; height: 17px; }
    h1 {
      font-size: clamp(42px, 6.6vw, 88px);
      line-height: .93;
      letter-spacing: -4px;
      font-weight: 900;
      margin-bottom: 24px;
    }
    .yellow { color: var(--yellow-2); }
    .lead { font-size: 18px; max-width: 670px; margin-bottom: 30px; }
    .hero-actions { display: flex; gap: 14px; flex-wrap: wrap; }

    .signal-stage {
      position: relative;
      min-height: 560px;
      display: grid;
      place-items: center;
      isolation: isolate;
      perspective: 1000px;
    }
    .signal-stage svg.hero-svg {
      width: min(100%, 560px);
      height: auto;
      filter: drop-shadow(0 28px 60px rgba(0,0,0,.24));
      overflow: visible;
    }
    .network-line {
      stroke-dasharray: 7 10;
      animation: dashMove 15s linear infinite;
    }
    .draw-line {
      stroke-dasharray: 900;
      stroke-dashoffset: 900;
      animation: draw 1.8s ease forwards;
    }
    .node-pulse { animation: nodePulse 2.6s ease-in-out infinite; transform-origin: center; }
    .float-node { animation: floatNode 5.4s ease-in-out infinite; }
    .float-node.two { animation-delay: .8s; }
    .float-node.three { animation-delay: 1.4s; }
    .center-mark { animation: breathe 4.4s ease-in-out infinite; transform-origin: center; }
    .orbit { animation: rotateSvg 22s linear infinite; transform-origin: 50% 50%; }
    .orbit.reverse { animation-direction: reverse; animation-duration: 28s; opacity: .62; }
    .hero-chip {
      position: absolute;
      z-index: 5;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 10px 13px;
      border-radius: 999px;
      background: rgba(18,7,7,.76);
      border: 1px solid rgba(242,188,47,.25);
      backdrop-filter: blur(14px);
      color: var(--cream);
      font-size: 13px;
      font-weight: 850;
      box-shadow: 0 16px 36px rgba(0,0,0,.25);
      animation: floatChip 5s ease-in-out infinite;
    }
    .hero-chip svg { width: 16px; height: 16px; color: var(--yellow); }
    .chip-a { left: 4%; top: 20%; }
    .chip-b { right: 2%; top: 34%; animation-delay: .8s; }
    .chip-c { left: 10%; bottom: 22%; animation-delay: 1.5s; }

    @keyframes dashMove { to { stroke-dashoffset: -220; } }
    @keyframes draw { to { stroke-dashoffset: 0; } }
    @keyframes nodePulse { 0%,100% { opacity: .45; transform: scale(.96); } 50% { opacity: 1; transform: scale(1.13); } }
    @keyframes floatNode { 0%,100% { transform: translateY(0); } 50% { transform: translateY(-14px); } }
    @keyframes floatChip { 0%,100% { transform: translateY(0); } 50% { transform: translateY(-12px); } }
    @keyframes breathe { 0%,100% { transform: scale(1); } 50% { transform: scale(1.035); } }
    @keyframes rotateSvg { to { transform: rotate(360deg); } }

    .section-band {
      position: relative;
      z-index: 5;
      margin-top: -44px;
    }
    .band-wrap {
      display: grid;
      grid-template-columns: repeat(4,1fr);
      gap: 14px;
      padding: 16px;
      border-radius: 28px;
      background: rgba(255,244,222,.96);
      box-shadow: 0 22px 60px rgba(0,0,0,.24);
      border: 1px solid rgba(255,255,255,.56);
    }
    .band-item {
      color: #240c09;
      padding: 18px;
      border-radius: 20px;
      background: rgba(255,255,255,.58);
      border: 1px solid rgba(62,25,20,.10);
      position: relative;
      overflow: hidden;
    }
    .band-item::after {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(90deg, transparent, rgba(255,255,255,.7), transparent);
      opacity: .45;
      transform: translateX(-130%);
      animation: shimmer 5.2s ease-in-out infinite;
    }
    @keyframes shimmer { 0%, 45% { transform: translateX(-130%); } 75%, 100% { transform: translateX(130%); } }
    .band-item strong { display: block; font-size: 17px; margin-bottom: 4px; }
    .band-item span { color: var(--muted-dark); font-size: 13px; }

    section { position: relative; z-index: 2; padding: 86px 0; }
    .light { background: var(--cream); color: #210908; }
    .light p { color: var(--muted-dark); }
    .dark {
      background:
        radial-gradient(circle at 18% 18%, rgba(201,25,32,.22), transparent 30%),
        radial-gradient(circle at 88% 26%, rgba(242,188,47,.12), transparent 30%),
        linear-gradient(145deg, #120606, #090303);
    }
    .section-head { max-width: 760px; margin-bottom: 34px; }
    .section-head.center { text-align: center; margin-inline: auto; }
    .tag { color: var(--red-2); font-size: 12px; font-weight: 900; letter-spacing: .13em; text-transform: uppercase; margin-bottom: 10px; }
    .dark .tag { color: var(--yellow-2); }
    h2 { font-size: clamp(30px, 4.4vw, 56px); line-height: 1.04; letter-spacing: -2px; margin-bottom: 14px; }

    .about-grid {
      display: grid;
      grid-template-columns: .95fr 1.05fr;
      gap: 24px;
      align-items: stretch;
    }
    .about-panel {
      min-height: 100%;
      padding: 34px;
      border-radius: 34px;
      color: var(--cream);
      background:
        radial-gradient(circle at 70% 0%, rgba(242,188,47,.18), transparent 34%),
        linear-gradient(145deg, var(--red), var(--red-3));
      box-shadow: 0 22px 70px rgba(63,5,7,.22);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      gap: 32px;
    }
    .about-panel p { color: #f3d6c3; }
    .about-list { display: grid; gap: 12px; }
    .about-row {
      display: grid;
      grid-template-columns: 46px 1fr;
      gap: 14px;
      align-items: start;
      padding: 18px;
      border-radius: 22px;
      background: var(--cream-2);
      border: 1px solid var(--line-dark);
    }
    .num {
      width: 46px;
      height: 46px;
      border-radius: 50%;
      display: grid;
      place-items: center;
      color: #210908;
      background: linear-gradient(145deg, var(--yellow-2), var(--yellow));
      font-weight: 900;
    }
    .about-row strong { display: block; color: #210908; margin-bottom: 3px; }
    .about-row span { color: var(--muted-dark); font-size: 14px; }

    .solutions-grid { display: grid; grid-template-columns: repeat(4,1fr); gap: 16px; }
    .solution-card {
      min-height: 300px;
      padding: 24px;
      border-radius: 26px;
      background: var(--cream-2);
      border: 1px solid var(--line-dark);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      transition: transform .18s ease, box-shadow .18s ease, border-color .18s ease;
      position: relative;
      overflow: hidden;
    }
    .solution-card::before {
      content: '';
      position: absolute;
      inset: auto -20% -40% auto;
      width: 160px;
      height: 160px;
      border-radius: 50%;
      background: radial-gradient(circle, rgba(201,25,32,.12), transparent 70%);
      transition: .18s ease;
    }
    .solution-card::after {
      content: '';
      position: absolute;
      top: 0;
      left: 24px;
      right: 24px;
      height: 3px;
      border-radius: 999px;
      background: linear-gradient(90deg, transparent, var(--yellow), var(--red-2), transparent);
      transform: scaleX(0);
      opacity: .8;
      transition: transform .42s ease;
    }
    .solution-card:hover { transform: translateY(-6px); box-shadow: 0 18px 50px rgba(63,5,7,.12); border-color: rgba(201,25,32,.22); }
    .solution-card:hover::after { transform: scaleX(1); }
    .solution-card:hover::before { transform: scale(1.25); }
    .icon {
      width: 54px;
      height: 54px;
      display: grid;
      place-items: center;
      border-radius: 18px;
      color: var(--red-2);
      background: rgba(201,25,32,.08);
      border: 1px solid rgba(201,25,32,.12);
      margin-bottom: 26px;
    }
    .icon svg { width: 27px; height: 27px; }
    .solution-card:hover .icon svg,
    .contact-card:hover svg { animation: iconNudge .55s ease both; }
    @keyframes iconNudge {
      0%, 100% { transform: translateY(0) scale(1); }
      45% { transform: translateY(-3px) scale(1.06); }
    }
    .solution-card h3 { font-size: 22px; letter-spacing: -.7px; margin-bottom: 10px; color: #210908; }
    .solution-card p { font-size: 15px; }

    .steps {
      position: relative;
      display: grid;
      grid-template-columns: repeat(3,1fr);
      gap: 18px;
    }
    .steps::before {
      content: '';
      position: absolute;
      top: 48px;
      left: 12%;
      right: 12%;
      height: 2px;
      background: linear-gradient(90deg, transparent, rgba(242,188,47,.68), transparent);
      transform: scaleX(0);
      transform-origin: left;
      transition: transform 1s ease;
    }
    .steps.is-visible::before { transform: scaleX(1); }
    .step {
      position: relative;
      min-height: 260px;
      padding: 28px;
      border-radius: 28px;
      background: rgba(255,255,255,.06);
      border: 1px solid rgba(255,255,255,.13);
      overflow: hidden;
    }
    .step::before {
      counter-increment: step;
      content: attr(data-step);
      display: grid;
      place-items: center;
      width: 54px;
      height: 54px;
      border-radius: 50%;
      color: #210606;
      background: linear-gradient(145deg, var(--yellow-2), var(--yellow));
      font-weight: 900;
      margin-bottom: 32px;
      position: relative;
      z-index: 2;
    }
    .step::after {
      content: '';
      position: absolute;
      left: 28px;
      right: 28px;
      bottom: 0;
      height: 3px;
      background: linear-gradient(90deg, var(--yellow), var(--red-2));
      opacity: .75;
    }
    .step h3 { font-size: 22px; margin-bottom: 8px; }

    .cta {
      padding: 90px 0;
      background:
        radial-gradient(circle at 22% 8%, rgba(242,188,47,.14), transparent 30%),
        linear-gradient(145deg, #090303, #160606);
    }
    .cta-box {
      border-radius: 36px;
      padding: 46px;
      display: grid;
      grid-template-columns: 1fr auto;
      align-items: center;
      gap: 22px;
      background:
        radial-gradient(circle at 92% -20%, rgba(242,188,47,.28), transparent 36%),
        linear-gradient(135deg, rgba(143,16,20,.70), rgba(201,25,32,.24));
      border: 1px solid rgba(242,188,47,.22);
      box-shadow: var(--shadow);
    }
    .cta-box p { max-width: 760px; }

    .contact-grid { display: grid; grid-template-columns: repeat(4,1fr); gap: 14px; }
    .contact-card {
      min-height: 160px;
      padding: 22px;
      border-radius: 24px;
      background: var(--cream-2);
      border: 1px solid var(--line-dark);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      color: #210908;
      transition: transform .18s ease, box-shadow .18s ease, border-color .18s ease;
      position: relative;
      overflow: hidden;
    }
    .contact-card:hover { transform: translateY(-5px); box-shadow: 0 18px 50px rgba(63,5,7,.12); border-color: rgba(201,25,32,.22); }
    .contact-card::after {
      content: '';
      position: absolute;
      inset: -1px;
      border-radius: inherit;
      border: 1px solid rgba(242,188,47,0);
      transition: border-color .18s ease;
      pointer-events: none;
    }
    .contact-card:hover::after { border-color: rgba(242,188,47,.32); }
    .contact-card svg { width: 25px; height: 25px; color: var(--red-2); }
    .contact-card span { color: var(--red-2); font-size: 11px; letter-spacing: .12em; font-weight: 900; text-transform: uppercase; display: block; margin-bottom: 6px; }
    .contact-card strong { font-size: 16px; overflow-wrap: anywhere; }
    .contact-card small { color: var(--muted-dark); display: block; margin-top: 5px; }

    footer { position: relative; z-index: 2; background: #070202; border-top: 1px solid var(--line); padding: 40px 0 24px; }
    .footer-grid { display: grid; grid-template-columns: 1.15fr .8fr .8fr; gap: 28px; align-items: start; }
    .footer-brand { display: flex; align-items: center; gap: 12px; margin-bottom: 14px; }
    .footer-col h4 { color: var(--cream); margin-bottom: 12px; }
    .footer-col a { color: var(--muted); display: block; margin-bottom: 8px; font-size: 14px; }
    .footer-col a:hover { color: var(--yellow-2); }
    .legal-data { margin-top: 14px; font-size: 13px; color: #bd9889; max-width: 760px; }
    .bottom {
      margin-top: 28px;
      padding-top: 18px;
      border-top: 1px solid rgba(255,255,255,.09);
      color: #a98577;
      font-size: 13px;
      display: flex;
      justify-content: space-between;
      gap: 16px;
      flex-wrap: wrap;
    }
    .float-contact {
      position: fixed;
      right: 22px;
      bottom: 22px;
      z-index: 120;
      display: inline-flex;
      align-items: center;
      gap: 10px;
      padding: 13px 16px;
      border-radius: 999px;
      background: linear-gradient(135deg, var(--yellow-2), var(--yellow));
      color: #210606;
      font-weight: 900;
      border: 1px solid rgba(255,255,255,.62);
      box-shadow: 0 18px 45px rgba(242,188,47,.22);
    }
    .float-contact svg { width: 18px; height: 18px; }

    @media (max-width: 980px) {
      .menu { display: none; }
      .hero { min-height: auto; }
      .hero-grid, .about-grid, .cta-box { grid-template-columns: 1fr; }
      .signal-stage { min-height: 420px; }
      .band-wrap, .solutions-grid, .contact-grid { grid-template-columns: repeat(2,1fr); }
      .steps { grid-template-columns: 1fr; }
      .steps::before { display: none; }
      .footer-grid { grid-template-columns: 1fr; }
    }
    @media (max-width: 640px) {
      .page-network { opacity: .30; }
      .container { width: min(100% - 32px, var(--max)); }
      .nav { height: 68px; }
      .brand span { display: none; }
      .nav .btn { display: none; }
      h1 { letter-spacing: -2.2px; }
      .hero { padding: 48px 0 72px; }
      .signal-stage { min-height: 310px; margin-top: 8px; }
      .hero-chip { display: none; }
      .section-band { margin-top: -44px; }
      .band-wrap, .solutions-grid, .contact-grid { grid-template-columns: 1fr; }
      section { padding: 62px 0; }
      .cta-box, .about-panel { padding: 28px; }
      .btn { width: 100%; }
      .float-contact { right: 14px; bottom: 14px; padding: 12px 14px; }
      .float-contact span { display: none; }
    }
    @media (prefers-reduced-motion: reduce) {
      .page-network { display: none; }
      *, *::before, *::after {
        animation-duration: .001ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: .001ms !important;
        scroll-behavior: auto !important;
      }
    }
  </style>
</head>
<body>
  <div class="page-network" aria-hidden="true">
    <svg viewBox="0 0 100 300" preserveAspectRatio="none">
      <defs>
        <linearGradient id="backboneGradient" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#ffe08a" stop-opacity="0"/>
          <stop offset="12%" stop-color="#ffe08a" stop-opacity=".42"/>
          <stop offset="52%" stop-color="#c91920" stop-opacity=".32"/>
          <stop offset="100%" stop-color="#ffe08a" stop-opacity="0"/>
        </linearGradient>
      </defs>
      <path class="backbone-path" pathLength="1" d="M73 0 C60 34 82 58 62 89 C43 119 66 145 50 177 C36 206 58 236 43 300" fill="none" stroke="url(#backboneGradient)" stroke-width=".48" stroke-linecap="round"/>
      <circle class="network-node node-hero" cx="73" cy="14" r="1.1" fill="#ffe08a"/>
      <circle class="network-node node-sobre" cx="61" cy="91" r="1.1" fill="#ffe08a"/>
      <circle class="network-node node-portifolio" cx="50" cy="143" r="1.1" fill="#ffe08a"/>
      <circle class="network-node node-como" cx="52" cy="197" r="1.1" fill="#ffe08a"/>
      <circle class="network-node node-contato" cx="44" cy="272" r="1.1" fill="#ffe08a"/>
      <circle class="network-dot" cx="73" cy="14" r=".72"/>
    </svg>
  </div>
  <header class="topbar">
    <div class="container nav">
      <a class="brand" href="#inicio" aria-label="Carrera Telecom">
        <div class="brand-badge">Carrera</div>
        <div>
          <strong>Carrera Telecom</strong>
          <span>Representação comercial em telecom</span>
        </div>
      </a>
      <nav class="menu" aria-label="Menu principal">
        <a href="#sobre">Empresa</a>
        <a href="#portifolio">Portfólio</a>
        <a href="#como-funciona">Como funciona</a>
        <a href="#contato">Contato</a>
      </nav>
      <a class="btn btn-primary" href="https://wa.me/554891541319" target="_blank" rel="noopener">Falar com a Carrera</a>
    </div>
  </header>

  <main id="inicio">
    <section class="hero">
      <div class="container hero-grid">
        <div class="reveal is-visible">
          <div class="eyebrow">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2v20"/><path d="M2 12h20"/><path d="M5 5l14 14"/><path d="M19 5L5 19"/></svg>
            Representação comercial em telecomunicações
          </div>
          <h1>Mais do que representar serviços, representamos <span class="yellow">conexões</span>.</h1>
          <p class="lead">A Carrera Telecom aproxima clientes e soluções do setor de telecom com clareza comercial, atendimento humano e visão consultiva.</p>
          <div class="hero-actions">
            <a class="btn btn-primary" href="https://wa.me/554891541319" target="_blank" rel="noopener">Falar com a Carrera</a>
            <a class="btn btn-secondary" href="#sobre">Conhecer a empresa</a>
          </div>
        </div>

        <div class="signal-stage" aria-label="Animação abstrata de rede e conexão">
          <span class="hero-chip chip-a">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 12h16"/><path d="M12 4v16"/><circle cx="12" cy="12" r="8"/></svg>
            Estratégia
          </span>
          <span class="hero-chip chip-b">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 12h6l3-8 3 16 3-8h3"/></svg>
            Telecom
          </span>
          <span class="hero-chip chip-c">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M7 17l10-10"/><path d="M7 7h10v10"/></svg>
            Relacionamento
          </span>

          <svg class="hero-svg" viewBox="0 0 620 520" role="img" aria-label="Fluxo de conexões Carrera Telecom">
            <defs>
              <radialGradient id="coreGlow" cx="50%" cy="50%" r="50%">
                <stop offset="0%" stop-color="#ffe08a" stop-opacity="0.95"/>
                <stop offset="46%" stop-color="#c91920" stop-opacity="0.38"/>
                <stop offset="100%" stop-color="#090303" stop-opacity="0"/>
              </radialGradient>
              <linearGradient id="lineGrad" x1="0" x2="1" y1="0" y2="1">
                <stop stop-color="#ffe08a"/>
                <stop offset=".45" stop-color="#c91920"/>
                <stop offset="1" stop-color="#fff4de"/>
              </linearGradient>
              <filter id="softGlow">
                <feGaussianBlur stdDeviation="5" result="blur"/>
                <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
              </filter>
            </defs>

            <circle cx="310" cy="260" r="220" fill="url(#coreGlow)" opacity="0.78"/>
            <g class="orbit" opacity=".72">
              <ellipse cx="310" cy="260" rx="220" ry="112" fill="none" stroke="#f2bc2f" stroke-opacity=".25" stroke-width="1.4"/>
              <ellipse cx="310" cy="260" rx="162" ry="256" fill="none" stroke="#fff4de" stroke-opacity=".15" stroke-width="1.2" transform="rotate(32 310 260)"/>
            </g>
            <g class="orbit reverse">
              <ellipse cx="310" cy="260" rx="256" ry="156" fill="none" stroke="#c91920" stroke-opacity=".28" stroke-width="1.2" transform="rotate(-22 310 260)"/>
            </g>

            <path class="draw-line network-line" d="M83 260 C150 112, 242 108, 310 260 S470 418, 545 170" fill="none" stroke="url(#lineGrad)" stroke-width="2" stroke-linecap="round" opacity=".76"/>
            <path class="draw-line network-line" d="M110 382 C230 322, 262 222, 310 260 C362 300, 438 282, 520 368" fill="none" stroke="#ffe08a" stroke-width="1.5" stroke-linecap="round" opacity=".52"/>
            <path class="draw-line network-line" d="M188 112 C254 208, 338 180, 404 100" fill="none" stroke="#fff4de" stroke-width="1.4" stroke-linecap="round" opacity=".35"/>

            <g filter="url(#softGlow)">
              <circle class="node-pulse float-node" cx="83" cy="260" r="7" fill="#ffe08a"/>
              <circle class="node-pulse float-node two" cx="545" cy="170" r="7" fill="#fff4de"/>
              <circle class="node-pulse float-node three" cx="520" cy="368" r="6" fill="#ffe08a"/>
              <circle class="node-pulse" cx="188" cy="112" r="5" fill="#fff4de"/>
              <circle class="node-pulse" cx="404" cy="100" r="5" fill="#f2bc2f"/>
            </g>

            <g class="center-mark" filter="url(#softGlow)">
              <circle cx="310" cy="260" r="88" fill="#f2bc2f"/>
              <circle cx="310" cy="260" r="78" fill="none" stroke="#fff8ec" stroke-width="5" opacity=".92"/>
              <text x="310" y="255" text-anchor="middle" font-size="35" font-weight="900" font-style="italic" fill="#190606" letter-spacing="-2">Carrera</text>
              <text x="310" y="286" text-anchor="middle" font-size="12" font-weight="900" fill="#190606" letter-spacing="5">TELECOM</text>
            </g>
          </svg>
        </div>
      </div>
    </section>

    <div class="section-band">
      <div class="container band-wrap">
        <div class="band-item reveal"><strong>Representação</strong><span>Intermediação comercial em telecom.</span></div>
        <div class="band-item reveal delay-1"><strong>Conectividade</strong><span>Soluções para diferentes perfis.</span></div>
        <div class="band-item reveal delay-2"><strong>Relacionamento</strong><span>Atendimento próximo e consultivo.</span></div>
        <div class="band-item reveal delay-3"><strong>Orientação</strong><span>Direção clara para o cliente decidir.</span></div>
      </div>
    </div>

    <section id="sobre" class="light" data-network="sobre">
      <div class="container about-grid">
        <div class="about-panel reveal">
          <div>
            <div class="tag" style="color: var(--yellow-2);">Sobre a Carrera</div>
            <h2>Uma representante comercial que entende o valor da conexão.</h2>
            <p>A Carrera Telecom aproxima clientes de soluções em telecomunicações, atuando com atendimento consultivo, linguagem clara e direcionamento comercial.</p>
          </div>
          <a class="btn btn-primary" href="https://wa.me/554891541319" target="_blank" rel="noopener">Iniciar atendimento</a>
        </div>
        <div class="about-list">
          <div class="about-row reveal"><div class="num">1</div><div><strong>Atuação comercial</strong><span>Representação e intermediação de soluções de telecomunicações.</span></div></div>
          <div class="about-row reveal delay-1"><div class="num">2</div><div><strong>Visão consultiva</strong><span>Antes de apresentar uma solução, a Carrera entende o cenário do cliente.</span></div></div>
          <div class="about-row reveal delay-2"><div class="num">3</div><div><strong>Portfólio telecom</strong><span>Conectividade, entretenimento, mobilidade, Wi‑Fi e serviços relacionados.</span></div></div>
          <div class="about-row reveal delay-3"><div class="num">4</div><div><strong>Comunicação humana</strong><span>Atendimento direto, simples e orientado para resolver com clareza.</span></div></div>
        </div>
      </div>
    </section>

    <section id="portifolio" class="light" style="padding-top:0;" data-network="portifolio">
      <div class="container">
        <div class="section-head center reveal">
          <div class="tag">Portfólio representado</div>
          <h2>Soluções do setor telecom, apresentadas com clareza.</h2>
          <p>A Carrera Telecom atua na orientação comercial e apresentação de soluções conforme cobertura, perfil de uso e disponibilidade.</p>
        </div>
        <div class="solutions-grid">
          <article class="solution-card reveal">
            <div>
              <div class="icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 12a8 8 0 0 1 16 0"/><path d="M8 12a4 4 0 0 1 8 0"/><path d="M12 12h.01"/></svg></div>
              <h3>Conectividade fixa</h3>
            </div>
            <p>Serviços de internet e conexão para uso residencial, profissional e empresarial.</p>
          </article>
          <article class="solution-card reveal delay-1">
            <div>
              <div class="icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="5" width="18" height="12" rx="2"/><path d="M8 21h8"/><path d="M12 17v4"/></svg></div>
              <h3>Entretenimento</h3>
            </div>
            <p>Serviços de TV, conteúdo e soluções complementares para uma experiência mais completa.</p>
          </article>
          <article class="solution-card reveal delay-2">
            <div>
              <div class="icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="7" y="2" width="10" height="20" rx="2"/><path d="M11 18h2"/></svg></div>
              <h3>Mobilidade</h3>
            </div>
            <p>Soluções móveis para manter pessoas e negócios conectados fora do ambiente fixo.</p>
          </article>
          <article class="solution-card reveal delay-3">
            <div>
              <div class="icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12.55a11 11 0 0 1 14.08 0"/><path d="M8.53 16.11a6 6 0 0 1 6.95 0"/><path d="M12 20h.01"/></svg></div>
              <h3>Experiência Wi‑Fi</h3>
            </div>
            <p>Orientação sobre conectividade interna, cobertura de ambientes e qualidade de uso.</p>
          </article>
        </div>
      </div>
    </section>

    <section id="como-funciona" class="dark" data-network="como">
      <div class="container">
        <div class="section-head center reveal">
          <div class="tag">Como funciona</div>
          <h2>Um atendimento comercial com mais direção.</h2>
          <p>A Carrera entende o perfil do cliente, verifica as possibilidades e orienta o próximo passo com clareza.</p>
        </div>
        <div class="steps reveal">
          <article class="step" data-step="01">
            <h3>Entendemos a necessidade</h3>
            <p>O atendimento começa pelo perfil de uso, endereço, tipo de serviço desejado e objetivo do cliente.</p>
          </article>
          <article class="step" data-step="02">
            <h3>Verificamos as opções</h3>
            <p>As soluções são avaliadas conforme disponibilidade, cobertura, região e condições comerciais vigentes.</p>
          </article>
          <article class="step" data-step="03">
            <h3>Direcionamos a contratação</h3>
            <p>Com as informações alinhadas, o cliente recebe orientação para seguir de forma segura e objetiva.</p>
          </article>
        </div>
      </div>
    </section>

    <section id="diferenciais" class="light">
      <div class="container">
        <div class="section-head center reveal">
          <div class="tag">Diferenciais</div>
          <h2>Representar é traduzir tecnologia em decisão simples.</h2>
          <p>A Carrera une portfólio telecom, atendimento consultivo e comunicação direta para ajudar o cliente a escolher melhor.</p>
        </div>
        <div class="solutions-grid">
          <article class="solution-card reveal">
            <div>
              <div class="icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 20V10"/><path d="M18 20V4"/><path d="M6 20v-4"/></svg></div>
              <h3>Clareza comercial</h3>
            </div>
            <p>Informações objetivas para o cliente entender o que está contratando e por quê.</p>
          </article>
          <article class="solution-card reveal delay-1">
            <div>
              <div class="icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg></div>
              <h3>Agilidade</h3>
            </div>
            <p>Atendimento focado em avançar da dúvida para o próximo passo com organização.</p>
          </article>
          <article class="solution-card reveal delay-2">
            <div>
              <div class="icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg></div>
              <h3>Relacionamento</h3>
            </div>
            <p>Comunicação próxima, humana e voltada para criar confiança durante o atendimento.</p>
          </article>
          <article class="solution-card reveal delay-3">
            <div>
              <div class="icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 12h6l3-8 3 16 3-8h3"/></svg></div>
              <h3>Setor telecom</h3>
            </div>
            <p>Atuação em um mercado essencial para casas, empresas, mobilidade e tecnologia.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="cta dark">
      <div class="container cta-box reveal">
        <div>
          <div class="tag">Contato</div>
          <h2>Vamos encontrar a solução certa para o seu cenário?</h2>
          <p>Fale com a Carrera Telecom para receber orientação comercial sobre serviços de conectividade, disponibilidade e próximos passos.</p>
        </div>
        <a class="btn btn-primary" href="https://wa.me/554891541319" target="_blank" rel="noopener">Falar com a Carrera</a>
      </div>
    </section>

    <section id="contato" class="light" data-network="contato">
      <div class="container">
        <div class="section-head center reveal">
          <div class="tag">Canais oficiais</div>
          <h2>Fale com a Carrera Telecom.</h2>
          <p>Atendimento comercial, informações e orientação sobre soluções de telecomunicações.</p>
        </div>
        <div class="contact-grid">
          <a class="contact-card reveal" href="https://wa.me/554891541319" target="_blank" rel="noopener">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.8 19.8 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6A19.8 19.8 0 0 1 2.11 4.18 2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.12.9.33 1.78.63 2.61a2 2 0 0 1-.45 2.11L8 9.73a16 16 0 0 0 6.27 6.27l1.29-1.29a2 2 0 0 1 2.11-.45c.83.3 1.71.51 2.61.63A2 2 0 0 1 22 16.92z"/></svg>
            <div><span>Telefone</span><strong>(48) 9154-1319</strong><small>Atendimento por mensagem ou ligação</small></div>
          </a>
          <a class="contact-card reveal delay-1" href="mailto:murilozoomtec@outlook.com">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16v16H4z"/><path d="M22 6l-10 7L2 6"/></svg>
            <div><span>E-mail</span><strong>murilozoomtec@outlook.com</strong><small>Contato comercial</small></div>
          </a>
          <a class="contact-card reveal delay-2" href="https://www.instagram.com/carreratelecombr/" target="_blank" rel="noopener">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><path d="M17.5 6.5h.01"/></svg>
            <div><span>Instagram</span><strong>@carreratelecombr</strong><small>Acompanhe a Carrera</small></div>
          </a>
          <a class="contact-card reveal delay-3" href="https://www.google.com/maps/search/?api=1&query=Rua%20Coronel%20Izidoro%201022%20Tijucas%20SC" target="_blank" rel="noopener">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 12-9 12S3 17 3 10a9 9 0 1 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg>
            <div><span>Endereço</span><strong>Tijucas/SC</strong><small>Rua Coronel Izidoro, 1022</small></div>
          </a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container footer-grid">
      <div>
        <div class="footer-brand">
          <div class="brand-badge">Carrera</div>
          <div>
            <strong style="display:block;color:var(--cream);">Carrera Telecom</strong>
            <span style="color:var(--muted);font-size:13px;">Representação comercial em telecomunicações</span>
          </div>
        </div>
        <p>Representação comercial em telecomunicações, com apresentação de soluções em conectividade, TV, telefonia móvel, Wi‑Fi e serviços relacionados, mediante consulta de disponibilidade.</p>
        <p class="legal-data">Carrera Telecom • CNPJ: 21.135.589/0001-05 • Rua Coronel Izidoro, 1022, Galpão, Bairro Universitário, Tijucas/SC, CEP 88.200-000</p>
      </div>
      <div class="footer-col">
        <h4>Navegação</h4>
        <a href="#sobre">Empresa</a>
        <a href="#portifolio">Portfólio</a>
        <a href="#como-funciona">Como funciona</a>
        <a href="#diferenciais">Diferenciais</a>
        <a href="#contato">Contato</a>
      </div>
      <div class="footer-col">
        <h4>Legal</h4>
        <a href="politica-de-privacidade.html">Política de Privacidade</a>
        <a href="termos-de-uso.html">Termos de Uso e Direitos do Usuário</a>
        <a href="mailto:murilozoomtec@outlook.com">murilozoomtec@outlook.com</a>
        <a href="https://www.instagram.com/carreratelecombr/" target="_blank" rel="noopener">Instagram @carreratelecombr</a>
      </div>
    </div>
    <div class="container bottom">
      <span>© 2026 Carrera Telecom. Todos os direitos reservados.</span>
      <span>Telefone: (48) 9154-1319</span>
    </div>
  </footer>

  <a class="float-contact" href="https://wa.me/554891541319" target="_blank" rel="noopener" aria-label="Abrir atendimento Carrera Telecom">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.8 19.8 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6A19.8 19.8 0 0 1 2.11 4.18 2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.12.9.33 1.78.63 2.61a2 2 0 0 1-.45 2.11L8 9.73a16 16 0 0 0 6.27 6.27l1.29-1.29a2 2 0 0 1 2.11-.45c.83.3 1.71.51 2.61.63A2 2 0 0 1 22 16.92z"/></svg>
    <span>Atendimento</span>
  </a>

  <script>
    const revealItems = document.querySelectorAll('.reveal, .steps');
    const observer = new IntersectionObserver((entries) => {
      entries.forEach((entry) => {
        if (entry.isIntersecting) {
          entry.target.classList.add('is-visible');
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.16 });

    revealItems.forEach((item) => observer.observe(item));

    const backbone = document.querySelector('.backbone-path');
    const networkDot = document.querySelector('.network-dot');
    const sections = Array.from(document.querySelectorAll('[data-network]'));

    function updateNetwork() {
      if (!backbone) return;
      const scrollable = document.documentElement.scrollHeight - window.innerHeight;
      const progress = scrollable > 0 ? Math.min(1, Math.max(0, window.scrollY / scrollable)) : 0;
      backbone.style.strokeDashoffset = String(1 - progress);

      if (networkDot && backbone.getTotalLength) {
        const total = backbone.getTotalLength();
        const point = backbone.getPointAtLength(total * progress);
        networkDot.setAttribute('cx', point.x.toFixed(2));
        networkDot.setAttribute('cy', point.y.toFixed(2));
      }

      sections.forEach((section) => {
        const rect = section.getBoundingClientRect();
        const active = rect.top < window.innerHeight * 0.62 && rect.bottom > window.innerHeight * 0.28;
        const node = document.querySelector(`.node-${section.dataset.network}`);
        if (node) node.classList.toggle('active', active);
      });

      const heroNode = document.querySelector('.node-hero');
      if (heroNode) heroNode.classList.toggle('active', window.scrollY < window.innerHeight * 0.55);
    }

    let ticking = false;
    window.addEventListener('scroll', () => {
      if (!ticking) {
        requestAnimationFrame(() => {
          updateNetwork();
          ticking = false;
        });
        ticking = true;
      }
    }, { passive: true });
    window.addEventListener('resize', updateNetwork);
    updateNetwork();

    const stage = document.querySelector('.signal-stage');
    const svg = document.querySelector('.hero-svg');
    if (stage && svg && !window.matchMedia('(prefers-reduced-motion: reduce)').matches) {
      stage.addEventListener('pointermove', (event) => {
        const rect = stage.getBoundingClientRect();
        const x = ((event.clientX - rect.left) / rect.width - 0.5) * 10;
        const y = ((event.clientY - rect.top) / rect.height - 0.5) * 10;
        svg.style.transform = `rotateX(${-y}deg) rotateY(${x}deg)`;
        document.body.style.setProperty('--mx', `${event.clientX}px`);
        document.body.style.setProperty('--my', `${event.clientY}px`);
      });
      stage.addEventListener('pointerleave', () => {
        svg.style.transform = 'rotateX(0deg) rotateY(0deg)';
      });
      window.addEventListener('pointermove', (event) => {
        document.body.style.setProperty('--mx', `${event.clientX}px`);
        document.body.style.setProperty('--my', `${event.clientY}px`);
      }, { passive: true });
    }
  </script>
</body>
</html>
