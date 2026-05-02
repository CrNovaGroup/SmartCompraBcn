<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SmartCompraBcn – Las Mejores Ofertas de Amazon España</title>
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Outfit:wght@300;400;500;600;700&display=swap" rel="stylesheet" />
  <script src="https://unpkg.com/lucide@latest/dist/umd/lucide.min.js"></script>
  <style>
    .icon { display:inline-flex; align-items:center; justify-content:center; }
    .icon svg { width:20px; height:20px; stroke-width:1.75; }
    .icon-lg svg { width:32px; height:32px; stroke-width:1.5; }
    .icon-xl svg { width:44px; height:44px; stroke-width:1.3; }
    .icon-sm svg { width:16px; height:16px; stroke-width:2; }
  </style>
  <style>
    :root {
      --rojo: #a50044;
      --naranja: #c9004a;
      --amarillo: #EDBB00;
      --negro: #07091a;
      --blanco: #f0f4ff;
      --gris: #0d1130;
      --gris2: #141835;
      --texto: #d0d8f0;
      --azul: #004d98;
      --azul-claro: #1a6ec7;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; }

    body {
      background-color: var(--negro);
      color: var(--texto);
      font-family: 'Outfit', sans-serif;
      overflow-x: hidden;
    }

    /* ── NOISE OVERLAY ── */
    body::before {
      content: '';
      position: fixed; inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
      pointer-events: none; z-index: 9999; opacity: .4;
    }

    /* ── NAV ── */
    nav {
      position: fixed; top: 0; left: 0; right: 0; z-index: 100;
      display: flex; align-items: center; justify-content: space-between;
      padding: 1rem 2.5rem;
      background: rgba(7,9,26,.9);
      backdrop-filter: blur(14px);
      border-bottom: 1px solid rgba(255,255,255,.06);
    }

    .nav-logo {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 1.8rem;
      letter-spacing: 2px;
      color: var(--azul-claro);
    }
    .nav-logo span { color: var(--amarillo); }

    .nav-links { display: flex; gap: 2rem; list-style: none; }
    .nav-links a {
      color: var(--texto); text-decoration: none;
      font-weight: 500; font-size: .9rem; letter-spacing: .5px;
      transition: color .2s;
    }
    .nav-links a:hover { color: var(--azul-claro); }

    .nav-cta {
      background: var(--rojo); color: #fff;
      border: none; padding: .55rem 1.4rem;
      border-radius: 4px; font-family: 'Outfit', sans-serif;
      font-weight: 600; font-size: .9rem; cursor: pointer;
      transition: background .2s, transform .15s;
    }
    .nav-cta:hover { background: var(--naranja); transform: scale(1.04); }

    /* ── HERO ── */
    .hero {
      min-height: 100vh;
      display: flex; flex-direction: column;
      justify-content: center; align-items: flex-start;
      padding: 8rem 2.5rem 4rem;
      position: relative; overflow: hidden;
    }

    .hero-bg {
      position: absolute; inset: 0; z-index: 0;
      background:
        radial-gradient(ellipse 60% 60% at 80% 50%, rgba(165,0,68,.25) 0%, transparent 70%),
        radial-gradient(ellipse 40% 40% at 20% 70%, rgba(0,77,152,.22) 0%, transparent 60%),
        linear-gradient(160deg, #07091a 0%, #0d1130 100%);
    }
    .hero-stripes {
      position: absolute; inset: 0; z-index: 0; overflow: hidden; opacity: .04;
      background: repeating-linear-gradient(
        90deg,
        #004d98 0px, #004d98 40px,
        #a50044 40px, #a50044 80px
      );
    }

    .hero-tag {
      position: relative; z-index: 1;
      background: rgba(0,77,152,.2); border: 1px solid rgba(0,77,152,.5);
      color: var(--azul-claro); padding: .35rem 1rem;
      border-radius: 999px; font-size: .78rem;
      font-weight: 600; letter-spacing: 1.5px; text-transform: uppercase;
      margin-bottom: 1.5rem;
      animation: fadeUp .6s ease both;
      display: flex; align-items: center; gap: 6px; width: fit-content;
    }

    .hero-title {
      position: relative; z-index: 1;
      font-family: 'Bebas Neue', sans-serif;
      font-size: clamp(3.5rem, 9vw, 8rem);
      line-height: .95;
      color: var(--blanco);
      animation: fadeUp .7s .1s ease both;
    }
    .hero-title em { font-style: normal; color: var(--rojo); }
    .hero-title .amarillo { color: var(--amarillo); }

    .hero-sub {
      position: relative; z-index: 1;
      font-size: 1.15rem; font-weight: 300; color: #b0a090;
      max-width: 520px; margin-top: 1.5rem; line-height: 1.6;
      animation: fadeUp .7s .2s ease both;
    }

    .hero-btns {
      position: relative; z-index: 1;
      display: flex; gap: 1rem; margin-top: 2.5rem;
      animation: fadeUp .7s .3s ease both;
    }

    .btn-prime {
      background: var(--rojo); color: #fff;
      padding: .85rem 2rem; border-radius: 6px;
      font-weight: 700; font-size: 1rem; text-decoration: none;
      border: none; cursor: pointer;
      transition: background .2s, transform .15s;
    }
    .btn-prime:hover { background: var(--naranja); transform: translateY(-2px); }

    .btn-sec {
      background: transparent; color: var(--texto);
      padding: .85rem 2rem; border-radius: 6px;
      font-weight: 600; font-size: 1rem; text-decoration: none;
      border: 1px solid rgba(255,255,255,.2); cursor: pointer;
      transition: border-color .2s, color .2s;
    }
    .btn-sec:hover { border-color: var(--azul-claro); color: var(--azul-claro); }

    /* FLOATING CARDS */
    .hero-cards {
      position: absolute; right: 4vw; top: 50%; transform: translateY(-50%);
      z-index: 1; display: flex; flex-direction: column; gap: 1rem;
      animation: fadeLeft .8s .4s ease both;
    }

    .mini-card {
      background: rgba(255,255,255,.05);
      border: 1px solid rgba(255,255,255,.1);
      backdrop-filter: blur(10px);
      border-radius: 12px; padding: 1rem 1.2rem;
      display: flex; align-items: center; gap: .8rem;
      width: 220px; transition: transform .2s, border-color .2s;
    }
    .mini-card:hover { transform: translateX(-6px); border-color: rgba(0,77,152,.6); }

    .mini-card-icon { width:36px; height:36px; display:flex; align-items:center; justify-content:center; background:rgba(0,77,152,.2); border-radius:8px; color:var(--azul-claro); flex-shrink:0; }
    .mini-card-icon svg { width:20px; height:20px; stroke-width:1.75; }

    .mini-card-info { flex: 1; }
    .mini-card-name { font-size: .82rem; font-weight: 600; color: var(--blanco); }
    .mini-card-price { font-size: .75rem; color: var(--amarillo); font-weight: 700; margin-top: .1rem; }
    .mini-card-badge {
      background: var(--rojo); color: #fff;
      font-size: .65rem; font-weight: 700; padding: .15rem .4rem;
      border-radius: 3px; white-space: nowrap;
    }

    /* ── STATS BAR ── */
    .stats {
      background: var(--gris); border-top: 1px solid rgba(255,255,255,.06);
      border-bottom: 1px solid rgba(255,255,255,.06);
      display: flex; justify-content: center;
      gap: 0; padding: 0;
    }
    .stat {
      flex: 1; max-width: 260px;
      padding: 1.8rem 1rem; text-align: center;
      border-right: 1px solid rgba(255,255,255,.06);
    }
    .stat:last-child { border-right: none; }
    .stat-num { font-family: 'Bebas Neue', sans-serif; font-size: 2.5rem; color: var(--amarillo); }
    .stat-lbl { font-size: .8rem; color: #888; margin-top: .2rem; letter-spacing: .5px; }

    /* ── SECTION ── */
    section { padding: 5rem 2.5rem; }

    .section-label {
      font-size: .75rem; font-weight: 700; letter-spacing: 3px;
      text-transform: uppercase; color: var(--azul-claro); margin-bottom: .8rem;
    }
    .section-title {
      font-family: 'Bebas Neue', sans-serif;
      font-size: clamp(2rem, 5vw, 3.5rem); line-height: 1;
      color: var(--blanco); margin-bottom: .6rem;
    }
    .section-sub { color: #888; font-size: 1rem; max-width: 500px; }

    /* ── CATEGORIES ── */
    #categorias { background: var(--negro); }

    .cats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
      gap: 1rem; margin-top: 3rem;
    }

    .cat-card {
      background: var(--gris2);
      border: 1px solid rgba(255,255,255,.07);
      border-radius: 14px; padding: 2rem 1rem;
      text-align: center; cursor: pointer; text-decoration: none;
      transition: transform .2s, border-color .25s, background .2s;
      display: block;
    }
    .cat-card:hover {
      transform: translateY(-6px);
      border-color: var(--azul-claro);
      background: rgba(0,77,152,.08);
    }
    .cat-icon { width:56px; height:56px; display:flex; align-items:center; justify-content:center; margin: 0 auto .8rem; background:rgba(255,255,255,.06); border-radius:14px; color:var(--azul-claro); transition: background .2s, color .2s; }
    .cat-icon svg { width:28px; height:28px; stroke-width:1.5; }
    .cat-card:hover .cat-icon { background:rgba(0,77,152,.2); color:var(--amarillo); }
    .cat-name { color: var(--blanco); font-weight: 600; font-size: .95rem; }
    .cat-count { color: #666; font-size: .78rem; margin-top: .3rem; }

    /* ── PRODUCTS ── */
    #ofertas { background: var(--gris); }

    .products-header {
      display: flex; justify-content: space-between; align-items: flex-end;
      margin-bottom: 2.5rem; flex-wrap: wrap; gap: 1rem;
    }

    .filter-tabs { display: flex; gap: .5rem; flex-wrap: wrap; }
    .tab {
      background: transparent; border: 1px solid rgba(255,255,255,.12);
      color: #888; padding: .45rem 1.1rem; border-radius: 999px;
      font-family: 'Outfit', sans-serif; font-size: .82rem;
      font-weight: 500; cursor: pointer; transition: all .2s;
    }
    .tab.active, .tab:hover {
      background: var(--azul); border-color: var(--azul); color: #fff;
    }

    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
      gap: 1.4rem;
    }

    .product-card {
      background: var(--negro);
      border: 1px solid rgba(255,255,255,.07);
      border-radius: 16px; overflow: hidden;
      transition: transform .25s, border-color .25s, box-shadow .25s;
      display: flex; flex-direction: column;
    }
    .product-card:hover {
      transform: translateY(-8px);
      border-color: rgba(0,77,152,.6);
      box-shadow: 0 20px 50px rgba(0,0,0,.5);
    }

    .product-img {
      height: 180px; width: 100%;
      display: flex; align-items: center; justify-content: center;
      background: #1a1a1a;
    }
    .prod-icon-svg { display:flex; align-items:center; justify-content:center; }
    .prod-icon-svg svg { width:72px; height:72px; stroke-width:1.1; opacity:.85; }

    .product-body { padding: 1.2rem; flex: 1; display: flex; flex-direction: column; }

    .product-cat {
      font-size: .7rem; font-weight: 700; letter-spacing: 1.5px;
      text-transform: uppercase; color: var(--naranja); margin-bottom: .4rem;
    }

    .product-name {
      font-weight: 600; font-size: .97rem; color: var(--blanco);
      line-height: 1.4; margin-bottom: auto;
    }

    .product-stars { display:flex; align-items:center; gap:2px; margin-top:.8rem; }
    .star-filled { color:var(--amarillo); font-size:13px; }
    .star-empty { color:#444; font-size:13px; }
    .product-stars .reviews { color:#666; font-size:.78rem; margin-left:.3rem; }

    .product-pricing {
      display: flex; align-items: center; gap: .7rem; margin-top: .8rem;
    }
    .product-price { font-family: 'Bebas Neue', sans-serif; font-size: 1.6rem; color: var(--blanco); }
    .product-old { text-decoration: line-through; color: #555; font-size: .85rem; }
    .product-discount {
      background: var(--rojo); color: #fff;
      font-size: .72rem; font-weight: 700;
      padding: .18rem .5rem; border-radius: 4px; margin-left: auto;
    }

    .product-btn {
      display: block; text-align: center; margin-top: 1rem;
      background: var(--naranja); color: #fff;
      padding: .7rem; border-radius: 8px;
      font-weight: 700; font-size: .9rem; text-decoration: none;
      transition: background .2s, transform .15s;
    }
    .product-btn:hover { background: var(--rojo); transform: scale(1.02); }

    /* ── BANNER PRIME ── */
    .prime-banner {
      background: linear-gradient(135deg, #07091a 0%, #0d1130 60%, #180520 100%);
      border: 1px solid rgba(255,208,0,.2);
      border-radius: 20px; margin: 0 2.5rem;
      padding: 4rem 3rem; display: flex;
      align-items: center; justify-content: space-between;
      gap: 2rem; flex-wrap: wrap;
      position: relative; overflow: hidden;
    }
    .prime-banner::before {
      content: 'PRIME';
      position: absolute; right: -30px; top: 50%; transform: translateY(-50%);
      font-family: 'Bebas Neue', sans-serif; font-size: 12rem;
      color: rgba(255,208,0,.04); pointer-events: none;
      white-space: nowrap;
    }

    .prime-content { position: relative; z-index: 1; }
    .prime-logo {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 1rem; letter-spacing: 4px; color: var(--amarillo);
      margin-bottom: .5rem;
    }
    .prime-title {
      font-family: 'Bebas Neue', sans-serif;
      font-size: clamp(2rem, 4vw, 3rem); color: var(--blanco);
      line-height: 1;
    }
    .prime-perks {
      margin-top: 1.5rem; display: flex; gap: 1.5rem; flex-wrap: wrap;
    }
    .prime-perk { display: flex; align-items: center; gap: .5rem; font-size: .9rem; color: #b0a090; }
    .prime-perk-icon { color:var(--azul-claro); display:inline-flex; align-items:center; }
    .prime-perk-icon svg { width:16px; height:16px; stroke-width:2; }

    .prime-cta {
      background: var(--amarillo); color: var(--negro);
      padding: 1rem 2.5rem; border-radius: 8px;
      font-weight: 800; font-size: 1rem; text-decoration: none;
      position: relative; z-index: 1;
      transition: transform .2s, box-shadow .2s;
      white-space: nowrap;
    }
    .prime-cta:hover { transform: scale(1.04); box-shadow: 0 0 40px rgba(255,208,0,.3); }

    /* ── NEWSLETTER ── */
    #alertas { background: var(--negro); }

    .newsletter-box {
      background: var(--gris2);
      border: 1px solid rgba(255,255,255,.08);
      border-radius: 20px; padding: 3.5rem;
      max-width: 680px; margin: 0 auto;
      text-align: center;
    }
    .newsletter-emoji { display:flex; align-items:center; justify-content:center; width:64px; height:64px; margin:0 auto 1rem; background:rgba(0,77,152,.2); border-radius:18px; color:var(--azul-claro); }
    .newsletter-emoji svg { width:32px; height:32px; stroke-width:1.5; }
    .newsletter-title {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 2.5rem; color: var(--blanco);
    }
    .newsletter-sub { color: #888; margin-top: .5rem; margin-bottom: 2rem; }

    .newsletter-form { display: flex; gap: .8rem; flex-wrap: wrap; justify-content: center; }
    .newsletter-input {
      background: rgba(255,255,255,.07); border: 1px solid rgba(255,255,255,.12);
      color: var(--blanco); padding: .85rem 1.2rem; border-radius: 8px;
      font-family: 'Outfit', sans-serif; font-size: .95rem;
      flex: 1; min-width: 220px; outline: none;
      transition: border-color .2s;
    }
    .newsletter-input::placeholder { color: #555; }
    .newsletter-input:focus { border-color: var(--amarillo); }
    .newsletter-btn {
      background: var(--azul); color: #fff;
      border: none; padding: .85rem 1.8rem; border-radius: 8px;
      font-family: 'Outfit', sans-serif; font-weight: 700; font-size: .95rem;
      cursor: pointer; transition: background .2s;
    }
    .newsletter-btn:hover { background: var(--azul-claro); }
    .newsletter-fine { color: #555; font-size: .75rem; margin-top: 1rem; }

    /* ── FOOTER ── */
    footer {
      background: var(--gris); border-top: 1px solid rgba(255,255,255,.06);
      padding: 3rem 2.5rem 2rem;
      display: grid; grid-template-columns: 2fr 1fr 1fr 1fr;
      gap: 2rem;
    }

    .footer-brand .nav-logo { margin-bottom: .8rem; font-size: 1.6rem; }
    .footer-brand p { color: #666; font-size: .85rem; line-height: 1.6; max-width: 260px; }

    .footer-col h4 { color: var(--blanco); font-size: .85rem; font-weight: 700; margin-bottom: 1rem; letter-spacing: .5px; }
    .footer-col ul { list-style: none; }
    .footer-col li + li { margin-top: .6rem; }
    .footer-col a { color: #666; font-size: .82rem; text-decoration: none; transition: color .2s; }
    .footer-col a:hover { color: var(--azul-claro); }

    .footer-bottom {
      grid-column: 1/-1; padding-top: 2rem;
      border-top: 1px solid rgba(255,255,255,.06);
      display: flex; justify-content: space-between; align-items: center;
      color: #555; font-size: .78rem; flex-wrap: wrap; gap: 1rem;
    }

    .disclaimer {
      background: rgba(255,255,255,.04); border: 1px solid rgba(255,255,255,.08);
      border-radius: 8px; padding: 1rem 1.5rem;
      color: #555; font-size: .75rem; line-height: 1.5;
      grid-column: 1/-1; margin-top: .5rem;
    }

    /* ── ANIMATIONS ── */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(30px); }
      to   { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeLeft {
      from { opacity: 0; transform: translateX(40px); }
      to   { opacity: 1; transform: translateX(0); }
    }

    /* ── RESPONSIVE ── */
    @media (max-width: 900px) {
      .hero-cards { display: none; }
      footer { grid-template-columns: 1fr 1fr; }
    }
    @media (max-width: 600px) {
      nav { padding: 1rem 1.5rem; }
      .nav-links { display: none; }
      .hero { padding: 7rem 1.5rem 3rem; }
      section { padding: 3.5rem 1.5rem; }
      .prime-banner { margin: 0 1.5rem; padding: 2.5rem 1.5rem; }
      footer { grid-template-columns: 1fr; padding: 2.5rem 1.5rem 1.5rem; }
      .stats { flex-direction: column; }
      .stat { border-right: none; border-bottom: 1px solid rgba(255,255,255,.06); }
    }
  </style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-logo">SmartCompra<span>Bcn</span></div>
  <ul class="nav-links">
    <li><a href="#categorias">Categorías</a></li>
    <li><a href="#ofertas">Ofertas</a></li>
    <li><a href="#alertas">Alertas</a></li>
  </ul>
  <button class="nav-cta" onclick="document.getElementById('ofertas').scrollIntoView({behavior:'smooth'})">Ver Chollos</button>
</nav>

<!-- HERO -->
<header class="hero">
  <div class="hero-bg"></div>
  <div class="hero-stripes"></div>
  <div class="hero-tag"><span class="icon icon-sm" data-lucide="map-pin" style="color:var(--amarillo);margin-right:6px;"></span>Amazon España · Barcelona</div>
  <h1 class="hero-title">
    Los mejores<br>
    <em>chollos</em><br>
    de <span class="amarillo">Amazon</span>
  </h1>
  <p class="hero-sub">
    Descuentos exclusivos seleccionados a mano para Barcelona y toda España.
    Tecnología, moda, hogar y mucho más — actualizados cada día.
  </p>
  <div class="hero-btns">
    <a href="#ofertas" class="btn-prime">Ver Ofertas 🔥</a>
    <a href="#alertas" class="btn-sec">Activar Alertas</a>
  </div>

  <div class="hero-cards">
    <div class="mini-card">
      <div class="mini-card-icon icon icon-lg" data-lucide="smartphone"></div>
      <div class="mini-card-info">
        <div class="mini-card-name">Samsung S25</div>
        <div class="mini-card-price">desde 749 €</div>
      </div>
      <div class="mini-card-badge">-22%</div>
    </div>
    <div class="mini-card">
      <div class="mini-card-icon icon icon-lg" data-lucide="headphones"></div>
      <div class="mini-card-info">
        <div class="mini-card-name">AirPods Pro</div>
        <div class="mini-card-price">desde 179 €</div>
      </div>
      <div class="mini-card-badge">-30%</div>
    </div>
    <div class="mini-card">
      <div class="mini-card-icon icon icon-lg" data-lucide="bot"></div>
      <div class="mini-card-info">
        <div class="mini-card-name">Roomba i5+</div>
        <div class="mini-card-price">desde 299 €</div>
      </div>
      <div class="mini-card-badge">-40%</div>
    </div>
    <div class="mini-card">
      <div class="mini-card-icon icon icon-lg" data-lucide="laptop"></div>
      <div class="mini-card-info">
        <div class="mini-card-name">MacBook Air M3</div>
        <div class="mini-card-price">desde 1.099 €</div>
      </div>
      <div class="mini-card-badge">-15%</div>
    </div>
  </div>
</header>

<!-- STATS -->
<div class="stats">
  <div class="stat"><div class="stat-num">+4.800</div><div class="stat-lbl">Ofertas activas hoy</div></div>
  <div class="stat"><div class="stat-num">97%</div><div class="stat-lbl">Envíos en 24h Barcelona</div></div>
  <div class="stat"><div class="stat-num">€ 23M</div><div class="stat-lbl">Ahorros de nuestra comunidad</div></div>
  <div class="stat"><div class="stat-num">128k</div><div class="stat-lbl">Suscriptores de alertas</div></div>
</div>

<!-- CATEGORIES -->
<section id="categorias">
  <div class="section-label">Explorar</div>
  <h2 class="section-title">Categorías Populares</h2>
  <p class="section-sub">Encuentra lo que necesitas entre las mejores ofertas de Amazon España.</p>
  <div class="cats-grid">
    <a class="cat-card" href="https://www.amazon.es/s?k=tecnologia" target="_blank" rel="nofollow noopener">
      <span class="cat-icon icon icon-xl" data-lucide="smartphone"></span>
      <div class="cat-name">Tecnología</div>
      <div class="cat-count">+2.300 productos</div>
    </a>
    <a class="cat-card" href="https://www.amazon.es/s?k=hogar" target="_blank" rel="nofollow noopener">
      <span class="cat-icon icon icon-xl" data-lucide="home"></span>
      <div class="cat-name">Hogar</div>
      <div class="cat-count">+1.800 productos</div>
    </a>
    <a class="cat-card" href="https://www.amazon.es/s?k=moda" target="_blank" rel="nofollow noopener">
      <span class="cat-icon icon icon-xl" data-lucide="shirt"></span>
      <div class="cat-name">Moda</div>
      <div class="cat-count">+3.100 productos</div>
    </a>
    <a class="cat-card" href="https://www.amazon.es/s?k=deporte+outdoor" target="_blank" rel="nofollow noopener">
      <span class="cat-icon icon icon-xl" data-lucide="dumbbell"></span>
      <div class="cat-name">Deporte</div>
      <div class="cat-count">+900 productos</div>
    </a>
    <a class="cat-card" href="https://www.amazon.es/s?k=belleza" target="_blank" rel="nofollow noopener">
      <span class="cat-icon icon icon-xl" data-lucide="sparkles"></span>
      <div class="cat-name">Belleza</div>
      <div class="cat-count">+1.400 productos</div>
    </a>
    <a class="cat-card" href="https://www.amazon.es/s?k=libros" target="_blank" rel="nofollow noopener">
      <span class="cat-icon icon icon-xl" data-lucide="book-open"></span>
      <div class="cat-name">Libros</div>
      <div class="cat-count">+600 productos</div>
    </a>
    <a class="cat-card" href="https://www.amazon.es/s?k=gaming" target="_blank" rel="nofollow noopener">
      <span class="cat-icon icon icon-xl" data-lucide="gamepad-2"></span>
      <div class="cat-name">Gaming</div>
      <div class="cat-count">+750 productos</div>
    </a>
    <a class="cat-card" href="https://www.amazon.es/s?k=cocina" target="_blank" rel="nofollow noopener">
      <span class="cat-icon icon icon-xl" data-lucide="utensils"></span>
      <div class="cat-name">Cocina</div>
      <div class="cat-count">+1.100 productos</div>
    </a>
  </div>
</section>

<!-- PRODUCTS -->
<section id="ofertas">
  <div class="products-header">
    <div>
      <div class="section-label">Destacados</div>
      <h2 class="section-title">Chollos del Día 🔥</h2>
    </div>
    <div class="filter-tabs">
      <button class="tab active" onclick="filterTab(this,'todos')">Todos</button>
      <button class="tab" onclick="filterTab(this,'tech')">Tecnología</button>
      <button class="tab" onclick="filterTab(this,'hogar')">Hogar</button>
      <button class="tab" onclick="filterTab(this,'deporte')">Deporte</button>
    </div>
  </div>

  <div class="products-grid" id="products-grid">

    <div class="product-card" data-cat="tech">
      <div class="product-img" style="background:linear-gradient(135deg,#ff6b0022,#ff6b0008);"><span data-lucide="smartphone" class="prod-icon-svg" style="color:#ff6b00;"></span></div>
      <div class="product-body">
        <div class="product-cat">Tecnología</div>
        <div class="product-name">Samsung Galaxy S25 128GB – Negro Phantom</div>
        <div class="product-stars"><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><span class="reviews">(4.8 · 3.241 reseñas)</span></div>
        <div class="product-pricing">
          <div class="product-price">749 €</div>
          <div class="product-old">959 €</div>
          <div class="product-discount">-22%</div>
        </div>
        <a class="product-btn" href="https://www.amazon.es/dp/B0DX1KJFMF" target="_blank" rel="nofollow noopener">Ver en Amazon →</a>
      </div>
    </div>

    <div class="product-card" data-cat="tech">
      <div class="product-img" style="background:linear-gradient(135deg,#ffd00022,#ffd00008);"><span data-lucide="headphones" class="prod-icon-svg" style="color:#ffd000;"></span></div>
      <div class="product-body">
        <div class="product-cat">Audio</div>
        <div class="product-name">Sony WH-1000XM5 – Auriculares Inalámbricos ANC</div>
        <div class="product-stars"><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><span class="reviews">(4.9 · 7.812 reseñas)</span></div>
        <div class="product-pricing">
          <div class="product-price">279 €</div>
          <div class="product-old">399 €</div>
          <div class="product-discount">-30%</div>
        </div>
        <a class="product-btn" href="https://www.amazon.es/s?k=sony+wh1000xm5" target="_blank" rel="nofollow noopener">Ver en Amazon →</a>
      </div>
    </div>

    <div class="product-card" data-cat="hogar">
      <div class="product-img" style="background:linear-gradient(135deg,#e8272b22,#e8272b08);"><span data-lucide="bot" class="prod-icon-svg" style="color:#e8272b;"></span></div>
      <div class="product-body">
        <div class="product-cat">Hogar Inteligente</div>
        <div class="product-name">iRobot Roomba i5+ – Robot Aspirador con Vaciado Automático</div>
        <div class="product-stars"><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:#444"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><span class="reviews">(4.6 · 2.100 reseñas)</span></div>
        <div class="product-pricing">
          <div class="product-price">299 €</div>
          <div class="product-old">499 €</div>
          <div class="product-discount">-40%</div>
        </div>
        <a class="product-btn" href="https://www.amazon.es/s?k=roomba+i5" target="_blank" rel="nofollow noopener">Ver en Amazon →</a>
      </div>
    </div>

    <div class="product-card" data-cat="tech">
      <div class="product-img" style="background:linear-gradient(135deg,#004d9822,#004d9808);"><span data-lucide="laptop" class="prod-icon-svg" style="color:#818cf8;"></span></div>
      <div class="product-body">
        <div class="product-cat">Ordenadores</div>
        <div class="product-name">Apple MacBook Air 13" M3 8GB/256GB – Medianoche</div>
        <div class="product-stars"><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><span class="reviews">(4.9 · 5.634 reseñas)</span></div>
        <div class="product-pricing">
          <div class="product-price">1.099 €</div>
          <div class="product-old">1.299 €</div>
          <div class="product-discount">-15%</div>
        </div>
        <a class="product-btn" href="https://www.amazon.es/s?k=macbook+air+m3" target="_blank" rel="nofollow noopener">Ver en Amazon →</a>
      </div>
    </div>

    <div class="product-card" data-cat="deporte">
      <div class="product-img" style="background:linear-gradient(135deg,#34d39922,#34d39908);"><span data-lucide="timer" class="prod-icon-svg" style="color:#34d399;"></span></div>
      <div class="product-body">
        <div class="product-cat">Deporte & Fitness</div>
        <div class="product-name">Garmin Forerunner 265 – Reloj Multideporte GPS</div>
        <div class="product-stars"><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><span class="reviews">(4.7 · 1.987 reseñas)</span></div>
        <div class="product-pricing">
          <div class="product-price">349 €</div>
          <div class="product-old">449 €</div>
          <div class="product-discount">-22%</div>
        </div>
        <a class="product-btn" href="https://www.amazon.es/s?k=garmin+forerunner+265" target="_blank" rel="nofollow noopener">Ver en Amazon →</a>
      </div>
    </div>

    <div class="product-card" data-cat="hogar">
      <div class="product-img" style="background:linear-gradient(135deg,#f59e0b22,#f59e0b08);"><span data-lucide="coffee" class="prod-icon-svg" style="color:#f59e0b;"></span></div>
      <div class="product-body">
        <div class="product-cat">Cocina</div>
        <div class="product-name">De'Longhi Dedica Arte – Cafetera Expreso Compacta</div>
        <div class="product-stars"><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:#444"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><span class="reviews">(4.5 · 3.320 reseñas)</span></div>
        <div class="product-pricing">
          <div class="product-price">119 €</div>
          <div class="product-old">179 €</div>
          <div class="product-discount">-34%</div>
        </div>
        <a class="product-btn" href="https://www.amazon.es/s?k=delonghi+dedica+arte" target="_blank" rel="nofollow noopener">Ver en Amazon →</a>
      </div>
    </div>

    <div class="product-card" data-cat="tech">
      <div class="product-img" style="background:linear-gradient(135deg,#ec489922,#ec489908);"><span data-lucide="camera" class="prod-icon-svg" style="color:#ec4899;"></span></div>
      <div class="product-body">
        <div class="product-cat">Fotografía</div>
        <div class="product-name">DJI Osmo Pocket 3 – Cámara Estabilizadora 4K</div>
        <div class="product-stars"><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><span class="reviews">(4.8 · 892 reseñas)</span></div>
        <div class="product-pricing">
          <div class="product-price">329 €</div>
          <div class="product-old">409 €</div>
          <div class="product-discount">-20%</div>
        </div>
        <a class="product-btn" href="https://www.amazon.es/s?k=dji+osmo+pocket+3" target="_blank" rel="nofollow noopener">Ver en Amazon →</a>
      </div>
    </div>

    <div class="product-card" data-cat="deporte">
      <div class="product-img" style="background:linear-gradient(135deg,#22d3ee22,#22d3ee08);"><span data-lucide="watch" class="prod-icon-svg" style="color:#22d3ee;"></span></div>
      <div class="product-body">
        <div class="product-cat">Fitness</div>
        <div class="product-name">Amazfit Balance Smartwatch – Salud & Bienestar</div>
        <div class="product-stars"><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:var(--amarillo)"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 24 24" fill="currentColor" stroke="none" style="color:#444"><polygon points="12,2 15.09,8.26 22,9.27 17,14.14 18.18,21.02 12,17.77 5.82,21.02 7,14.14 2,9.27 8.91,8.26"/></svg><span class="reviews">(4.4 · 1.203 reseñas)</span></div>
        <div class="product-pricing">
          <div class="product-price">149 €</div>
          <div class="product-old">229 €</div>
          <div class="product-discount">-35%</div>
        </div>
        <a class="product-btn" href="https://www.amazon.es/s?k=amazfit+balance" target="_blank" rel="nofollow noopener">Ver en Amazon →</a>
      </div>
    </div>

  </div>
</section>

<!-- PRIME BANNER -->
<div class="prime-banner">
  <div class="prime-content">
    <div class="prime-logo">AMAZON <span class="icon icon-sm" style="display:inline-flex;vertical-align:middle;color:var(--amarillo);" data-lucide="star"></span> PRIME</div>
    <h2 class="prime-title">Envío GRATIS<br>en 24 horas a Barcelona</h2>
    <div class="prime-perks">
      <div class="prime-perk"><span class="prime-perk-icon icon icon-sm" data-lucide="package"></span> Envío rápido gratis</div>
      <div class="prime-perk"><span class="prime-perk-icon icon icon-sm" data-lucide="play-circle"></span> Prime Video incluido</div>
      <div class="prime-perk"><span class="prime-perk-icon icon icon-sm" data-lucide="music"></span> Prime Music</div>
      <div class="prime-perk"><span class="prime-perk-icon icon icon-sm" data-lucide="zap"></span> Acceso anticipado a ofertas</div>
    </div>
  </div>
  <a class="prime-cta" href="https://www.amazon.es/prime" target="_blank" rel="nofollow noopener">Prueba Prime GRATIS 30 días</a>
</div>

<!-- NEWSLETTER -->
<section id="alertas">
  <div class="newsletter-box">
    <div class="newsletter-emoji" data-lucide="bell"></div>
    <h2 class="newsletter-title">Alertas de Chollos</h2>
    <p class="newsletter-sub">Sé el primero en enterarte de las mejores ofertas para Barcelona.<br>Sin spam, solo los mejores descuentos.</p>
    <div class="newsletter-form">
      <input class="newsletter-input" type="email" placeholder="tu@email.com" />
      <button class="newsletter-btn" onclick="subscribe()">¡Quiero Alertas!</button>
    </div>
    <p class="newsletter-fine">Respetamos tu privacidad · Baja cuando quieras</p>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-brand">
    <div class="nav-logo">SmartCompra<span>Bcn</span></div>
    <p>Tu web de referencia para encontrar las mejores ofertas de Amazon España, desde Barcelona al mundo.</p>
  </div>
  <div class="footer-col">
    <h4>Categorías</h4>
    <ul>
      <li><a href="#">Tecnología</a></li>
      <li><a href="#">Hogar</a></li>
      <li><a href="#">Moda</a></li>
      <li><a href="#">Deporte</a></li>
      <li><a href="#">Gaming</a></li>
    </ul>
  </div>
  <div class="footer-col">
    <h4>Información</h4>
    <ul>
      <li><a href="#">Sobre nosotros</a></li>
      <li><a href="#">Cómo funciona</a></li>
      <li><a href="#">Política de privacidad</a></li>
      <li><a href="#">Cookies</a></li>
      <li><a href="#">Contacto</a></li>
    </ul>
  </div>
  <div class="footer-col">
    <h4>Síguenos</h4>
    <ul>
      <li><a href="#">Telegram</a></li>
      <li><a href="#">Instagram</a></li>
      <li><a href="#">TikTok</a></li>
      <li><a href="#">Twitter / X</a></li>
    </ul>
  </div>
  <div class="disclaimer">
    <strong>Aviso legal:</strong> BarcelonaDeals es participante en el Programa de Afiliados de Amazon ES, un programa de publicidad para afiliados diseñado para proporcionar a sitios web un medio para obtener comisiones por hacer publicidad y enlazar a amazon.es. Los precios indicados pueden variar y están sujetos a disponibilidad en el momento de la visita. Esta web no garantiza la exactitud de los precios mostrados.
  </div>
  <div class="footer-bottom">
    <span>© 2026 SmartCompraBcn · Hecho con <span class="icon icon-sm" style="display:inline-flex;vertical-align:middle;color:var(--rojo);" data-lucide="heart"></span> en Barcelona</span>
    <span>Afiliado Amazon España · amazon.es</span>
  </div>
</footer>

<script>
  // Filter tabs
  function filterTab(btn, cat) {
    document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
    btn.classList.add('active');
    document.querySelectorAll('.product-card').forEach(card => {
      if (cat === 'todos' || card.dataset.cat === cat) {
        card.style.display = '';
      } else {
        card.style.display = 'none';
      }
    });
  }

  // Subscribe
  function subscribe() {
    const input = document.querySelector('.newsletter-input');
    if (!input.value.includes('@')) { input.focus(); return; }
    const btn = document.querySelector('.newsletter-btn');
    btn.textContent = '¡Suscrito! 🎉';
    btn.style.background = '#EDBB00'; btn.style.color='#07091a';
    input.value = '';
    setTimeout(() => { btn.textContent = '¡Quiero Alertas!'; btn.style.background = ''; }, 3000);
  }

  // Scroll animations
  const observer = new IntersectionObserver(entries => {
    entries.forEach(e => {
      if (e.isIntersecting) {
        e.target.style.opacity = 1;
        e.target.style.transform = 'translateY(0)';
      }
    });
  }, { threshold: 0.1 });

  document.querySelectorAll('.product-card, .cat-card, .mini-card').forEach(el => {
    el.style.opacity = 0;
    el.style.transform = 'translateY(24px)';
    el.style.transition = 'opacity .5s ease, transform .5s ease';
    observer.observe(el);
  });

  // Init Lucide icons
  lucide.createIcons();
</script>

</body>
</html>
