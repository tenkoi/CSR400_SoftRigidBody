<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSR400 · Soft &amp; Rigid Body — Learning Guide</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Shrikhand&family=Space+Grotesk:wght@400;500;700&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --paper:   #F4E7CE;
    --ink:     #2C1B10;
    --orange:  #E4572E;
    --mustard: #E9A63A;
    --teal:    #1E6E64;
    --rose:    #C4485B;
    --radius:  14px;
  }

  *{ margin:0; padding:0; box-sizing:border-box; }

  html{ scroll-behavior:smooth; }
  @media (prefers-reduced-motion: reduce){
    html{ scroll-behavior:auto; }
    *,*::before,*::after{ animation:none !important; transition:none !important; }
  }

  body{
    background:var(--paper);
    color:var(--ink);
    font-family:'Space Grotesk', sans-serif;
    line-height:1.6;
    /* subtle paper grain */
    background-image:
      radial-gradient(rgba(44,27,16,0.06) 1px, transparent 1px);
    background-size:5px 5px;
  }

  h1,h2,h3{ font-family:'Shrikhand', cursive; font-weight:400; line-height:1.1; }
  .mono{ font-family:'DM Mono', monospace; }

  a{ color:var(--teal); }
  a:focus-visible, button:focus-visible{
    outline:3px solid var(--orange);
    outline-offset:3px;
  }

  /* ============ NAV ============ */
  nav{
    position:sticky; top:0; z-index:50;
    background:var(--ink);
    border-bottom:4px solid var(--orange);
  }
  .nav-inner{
    max-width:1100px; margin:0 auto;
    display:flex; align-items:center; gap:1.2rem;
    padding:.65rem 1.2rem;
    flex-wrap:wrap;
  }
  .nav-badge{
    font-family:'Shrikhand', cursive;
    color:var(--mustard);
    font-size:1.15rem;
    letter-spacing:.5px;
  }
  .nav-links{ display:flex; gap:.35rem; flex-wrap:wrap; margin-left:auto; }
  .nav-links a{
    font-family:'DM Mono', monospace;
    font-size:.78rem;
    color:var(--paper);
    text-decoration:none;
    padding:.3rem .65rem;
    border:1.5px solid transparent;
    border-radius:999px;
    transition:all .15s ease;
  }
  .nav-links a:hover{ border-color:var(--mustard); color:var(--mustard); }

  /* ============ HERO ============ */
  header.hero{
    position:relative;
    overflow:hidden;
    border-bottom:6px solid var(--ink);
    background:
      repeating-linear-gradient(
        0deg,
        var(--teal) 0 90px,
        var(--mustard) 90px 170px,
        var(--orange) 170px 240px,
        var(--rose) 240px 300px,
        var(--paper) 300px 100%
      );
  }
  /* groovy sunset arcs */
  .hero-arcs{
    position:absolute; inset:0;
    background:
      radial-gradient(circle at 50% 118%, var(--paper) 0 34%, transparent 34.5%),
      radial-gradient(circle at 50% 118%, var(--mustard) 0 44%, transparent 44.5%),
      radial-gradient(circle at 50% 118%, var(--orange) 0 55%, transparent 55.5%),
      radial-gradient(circle at 50% 118%, var(--rose) 0 67%, transparent 67.5%),
      radial-gradient(circle at 50% 118%, var(--teal) 0 82%, transparent 82.5%),
      var(--ink);
  }
  .hero-content{
    position:relative;
    max-width:1100px; margin:0 auto;
    padding:5.5rem 1.2rem 4.5rem;
    text-align:center;
  }
  .hero-eyebrow{
    display:inline-block;
    font-family:'DM Mono', monospace;
    font-size:.85rem;
    letter-spacing:.35em;
    text-transform:uppercase;
    color:var(--paper);
    background:var(--ink);
    border:2px solid var(--paper);
    border-radius:999px;
    padding:.4rem 1.3rem;
    margin-bottom:1.4rem;
  }
  .hero h1{
    font-size:clamp(2.6rem, 8vw, 5.4rem);
    color:var(--paper);
    text-shadow:
      3px 3px 0 var(--ink),
      6px 6px 0 var(--orange);
    margin-bottom:1rem;
  }
  .hero .sub{
    color:var(--paper);
    font-size:clamp(1rem, 2.4vw, 1.25rem);
    max-width:640px;
    margin:0 auto 2rem;
    font-weight:500;
  }
  .hero-tags{
    display:flex; gap:.6rem; justify-content:center; flex-wrap:wrap;
  }
  .tag{
    font-family:'DM Mono', monospace;
    font-size:.8rem;
    background:var(--paper);
    color:var(--ink);
    border:2px solid var(--ink);
    box-shadow:3px 3px 0 var(--ink);
    border-radius:8px;
    padding:.35rem .8rem;
  }

  /* marquee strip */
  .marquee{
    background:var(--orange);
    border-top:3px solid var(--ink);
    border-bottom:3px solid var(--ink);
    overflow:hidden;
    white-space:nowrap;
  }
  .marquee-track{
    display:inline-block;
    font-family:'Shrikhand', cursive;
    color:var(--paper);
    font-size:1rem;
    padding:.5rem 0;
    animation:scroll 28s linear infinite;
  }
  @keyframes scroll{
    from{ transform:translateX(0); }
    to{ transform:translateX(-50%); }
  }

  /* ============ SECTIONS ============ */
  main{ max-width:1100px; margin:0 auto; padding:0 1.2rem; }

  section{ padding:4rem 0 1rem; }

  .section-head{
    display:flex; align-items:center; gap:1rem;
    margin-bottom:2rem;
  }
  .section-head::after{
    content:""; flex:1; height:4px;
    background:repeating-linear-gradient(90deg, var(--ink) 0 14px, transparent 14px 24px);
    border-radius:2px;
  }
  .section-head h2{
    font-size:clamp(1.7rem, 4.5vw, 2.5rem);
    color:var(--ink);
  }
  .section-head .dot{
    width:20px; height:20px; border-radius:50%;
    background:var(--orange);
    border:3px solid var(--ink);
    flex:none;
  }

  /* course info card grid */
  .info-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(230px, 1fr));
    gap:1.2rem;
  }
  .info-card{
    background:#fff9ec;
    border:3px solid var(--ink);
    border-radius:var(--radius);
    box-shadow:6px 6px 0 var(--ink);
    padding:1.4rem;
  }
  .info-card h3{
    font-size:1.05rem;
    color:var(--orange);
    margin-bottom:.5rem;
  }
  .info-card p, .info-card li{ font-size:.94rem; }
  .info-card ol{ padding-left:1.2rem; }
  .info-card ol li{ margin-bottom:.4rem; }

  .synopsis-band{
    margin-top:2rem;
    background:var(--teal);
    color:var(--paper);
    border:3px solid var(--ink);
    border-radius:var(--radius);
    box-shadow:6px 6px 0 var(--ink);
    padding:1.8rem 2rem;
    font-size:1.05rem;
  }
  .synopsis-band strong{ color:var(--mustard); }

  /* ============ LECTURER ============ */
  .lecturer{
    display:flex; gap:1.6rem; align-items:center;
    background:var(--mustard);
    border:3px solid var(--ink);
    border-radius:var(--radius);
    box-shadow:6px 6px 0 var(--ink);
    padding:1.6rem 2rem;
    flex-wrap:wrap;
  }
  .lecturer .avatar{
    width:92px; height:92px; flex:none;
    border-radius:50%;
    background:
      radial-gradient(circle at 50% 40%, var(--paper) 0 32%, transparent 33%),
      radial-gradient(circle at 50% 95%, var(--paper) 0 42%, transparent 43%),
      var(--orange);
    border:3px solid var(--ink);
  }
  .lecturer h3{ font-size:1.35rem; margin-bottom:.2rem; }
  .lecturer p{ font-size:.95rem; }

  /* ============ WEEK CARDS ============ */
  .week{
    margin-bottom:3.2rem;
    border:3px solid var(--ink);
    border-radius:var(--radius);
    overflow:hidden;
    box-shadow:8px 8px 0 var(--ink);
    background:#fff9ec;
  }
  .week-head{
    display:flex; align-items:center; gap:1.2rem;
    padding:1.2rem 1.6rem;
    border-bottom:3px dashed var(--ink); /* ticket-stub perforation */
    flex-wrap:wrap;
  }
  .week:nth-of-type(6n+1) .week-head{ background:var(--orange); }
  .week:nth-of-type(6n+2) .week-head{ background:var(--teal); }
  .week:nth-of-type(6n+3) .week-head{ background:var(--rose); }
  .week:nth-of-type(6n+4) .week-head{ background:var(--mustard); }
  .week:nth-of-type(6n+5) .week-head{ background:var(--ink); }
  .week:nth-of-type(6n+6) .week-head{ background:var(--orange); }

  .week-num{
    font-family:'Shrikhand', cursive;
    font-size:2rem;
    color:var(--ink);
    background:var(--paper);
    border:3px solid var(--ink);
    border-radius:12px;
    padding:.1rem .9rem;
    box-shadow:3px 3px 0 var(--ink);
    flex:none;
  }
  .week-head h3{
    color:var(--paper);
    font-size:clamp(1.15rem, 3vw, 1.6rem);
    text-shadow:2px 2px 0 var(--ink);
  }
  .week-head .wk-label{
    font-family:'DM Mono', monospace;
    font-size:.72rem;
    letter-spacing:.25em;
    text-transform:uppercase;
    color:var(--paper);
    display:block;
  }

  .week-body{ padding:1.6rem; }
  .week-topics{
    display:flex; gap:.5rem; flex-wrap:wrap;
    margin-bottom:1.4rem;
  }
  .topic-chip{
    font-family:'DM Mono', monospace;
    font-size:.78rem;
    background:var(--paper);
    border:2px solid var(--ink);
    border-radius:999px;
    padding:.28rem .75rem;
  }

  .video-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(280px, 1fr));
    gap:1.2rem;
  }
  .video-card{
    border:3px solid var(--ink);
    border-radius:12px;
    overflow:hidden;
    background:var(--ink);
    transition:transform .15s ease;
  }
  .video-card:hover{ transform:translate(-2px,-2px); box-shadow:5px 5px 0 var(--orange); }
  .video-frame{
    position:relative;
    padding-top:56.25%;
    background:var(--ink);
  }
  .video-frame iframe{
    position:absolute; inset:0;
    width:100%; height:100%;
    border:0;
  }
  .video-meta{
    padding:.8rem 1rem 1rem;
    background:var(--paper);
    border-top:3px solid var(--ink);
  }
  .video-meta .vt{
    font-weight:700;
    font-size:.92rem;
    display:block;
    margin-bottom:.15rem;
  }
  .video-meta .vc{
    font-family:'DM Mono', monospace;
    font-size:.74rem;
    color:var(--teal);
  }


  .yt-btn{
    display:inline-block;
    margin-top:.55rem;
    font-family:'DM Mono', monospace;
    font-size:.74rem;
    font-weight:500;
    text-decoration:none;
    color:var(--paper);
    background:var(--ink);
    border:2px solid var(--ink);
    border-radius:999px;
    padding:.3rem .85rem;
    transition:all .15s ease;
  }
  .yt-btn:hover{ background:var(--orange); border-color:var(--ink); color:var(--paper); }


  .yt-facade{
    position:absolute; inset:0;
    width:100%; height:100%;
    border:0; padding:0; cursor:pointer;
    background:var(--ink);
    display:block;
  }
  .yt-facade img{
    width:100%; height:100%;
    object-fit:cover; display:block;
    filter:saturate(.92);
  }
  .play-badge{
    position:absolute; top:50%; left:50%;
    transform:translate(-50%,-50%);
    width:64px; height:64px;
    display:flex; align-items:center; justify-content:center;
    font-size:1.5rem; color:var(--paper);
    background:var(--orange);
    border:3px solid var(--paper);
    border-radius:50%;
    box-shadow:0 0 0 4px var(--ink), 4px 6px 0 4px rgba(44,27,16,.55);
    transition:transform .15s ease, background .15s ease;
    padding-left:5px;
  }
  .yt-facade:hover .play-badge{ transform:translate(-50%,-50%) scale(1.1); background:var(--rose); }

  .week-note{
    margin-top:1.3rem;
    font-family:'DM Mono', monospace;
    font-size:.8rem;
    background:var(--paper);
    border:2px dashed var(--ink);
    border-radius:10px;
    padding:.7rem 1rem;
  }
  .week-note b{ color:var(--rose); }

  /* ============ REFERENCES ============ */
  .ref-list{ list-style:none; display:grid; gap:1rem; }
  .ref-list li{
    background:#fff9ec;
    border:3px solid var(--ink);
    border-left:14px solid var(--orange);
    border-radius:10px;
    box-shadow:5px 5px 0 var(--ink);
    padding:1rem 1.3rem;
    font-size:.95rem;
  }
  .ref-list li.alt{ border-left-color:var(--teal); }
  .ref-list .rlabel{
    font-family:'DM Mono', monospace;
    font-size:.7rem;
    letter-spacing:.2em;
    text-transform:uppercase;
    color:var(--rose);
    display:block;
    margin-bottom:.15rem;
  }

  /* ============ FOOTER ============ */
  footer{
    margin-top:4.5rem;
    background:var(--ink);
    color:var(--paper);
    border-top:6px solid var(--orange);
    text-align:center;
    padding:2.6rem 1.2rem 2rem;
  }
  footer .foot-title{
    font-family:'Shrikhand', cursive;
    color:var(--mustard);
    font-size:1.4rem;
    margin-bottom:.4rem;
  }
  footer p{ font-size:.85rem; opacity:.85; }
  footer .mono{ font-size:.75rem; margin-top:.8rem; opacity:.6; }

  @media (max-width:600px){
    .hero-content{ padding:3.5rem 1rem 3rem; }
    .week-body{ padding:1.1rem; }
    .lecturer{ padding:1.2rem; }
  }
</style>
</head>
<body>

<!-- ===================== NAV ===================== -->
<nav aria-label="Main navigation">
  <div class="nav-inner">
    <span class="nav-badge">CSR400</span>
    <div class="nav-links">
      <a href="#about">About</a>
      <a href="#lecturer">Lecturer</a>
      <a href="#week1">Wk 1</a>
      <a href="#week2">Wk 2</a>
      <a href="#week3">Wk 3</a>
      <a href="#week4">Wk 4</a>
      <a href="#week5">Wk 5</a>
      <a href="#week6">Wk 6</a>
      <a href="#references">References</a>
    </div>
  </div>
</nav>

<!-- ===================== HERO ===================== -->
<header class="hero">
  <div class="hero-arcs" aria-hidden="true"></div>
  <div class="hero-content">
    <span class="hero-eyebrow">AEU · Asia e University · Malaysia</span>
    <h1>Soft &amp; Rigid Body</h1>
    <p class="sub">A 6-week guided journey into physics, dynamics &amp; simulation —
    taught the modern way with <strong>Blender 4.0+</strong>. Drop it, smash it, squish it, bake it.</p>
    <div class="hero-tags">
      <span class="tag">Course Code · CSR400</span>
      <span class="tag">Credit Value · 3</span>
      <span class="tag">Prerequisite · CBD346 Basic 3D Animation</span>
      <span class="tag">Tool · Blender 4.0 &amp; above</span>
    </div>
  </div>
</header>

<div class="marquee" aria-hidden="true">
  <div class="marquee-track">
    ★ RIGID BODIES ★ CONSTRAINTS ★ ACTIVE &amp; PASSIVE ★ SOLVERS ★ BAKING ★ SOFT BODIES ★ GOALS &amp; WEIGHTS ★ SHATTER FX ★
    ★ RIGID BODIES ★ CONSTRAINTS ★ ACTIVE &amp; PASSIVE ★ SOLVERS ★ BAKING ★ SOFT BODIES ★ GOALS &amp; WEIGHTS ★ SHATTER FX ★
  </div>
</div>

<main>

<!-- ===================== ABOUT ===================== -->
<section id="about" aria-labelledby="about-h">
  <div class="section-head">
    <span class="dot"></span>
    <h2 id="about-h">About This Course</h2>
  </div>

  <div class="info-grid">
    <div class="info-card">
      <h3>Objectives</h3>
      <ol>
        <li>Introduce dynamic theory and how it works in 3D applications.</li>
        <li>Explain the different types of dynamics in the real world and apply them in 3D.</li>
        <li>Demonstrate the workflow of creating dynamics in a 3D application.</li>
        <li>Explain methods of managing, selecting, evaluating and manipulating information from different sources.</li>
      </ol>
    </div>
    <div class="info-card">
      <h3>Learning Outcomes</h3>
      <ol>
        <li>Analyse real-world dynamics and apply them to 3D applications.</li>
        <li>Simulate real-world dynamics in the digital 3D environment.</li>
        <li>Apply real-world dynamic theory to dynamics in the digital world.</li>
        <li>Identify methods of managing, selecting, evaluating and manipulating information from different sources.</li>
      </ol>
    </div>
    <div class="info-card">
      <h3>How To Use This Guide</h3>
      <p>Work through one week at a time. Watch all three tutorials, follow along in
      <strong>Blender 4.0 or newer</strong>, then complete the weekly practice challenge
      before moving on. Assignments are briefed in Weeks 3 and 6.</p>
    </div>
  </div>

  <div class="synopsis-band">
    <strong>Synopsis —</strong> This course explores the function of <strong>Rigid Bodies</strong>,
    how to use rigid bodies and constraints, and how to use <strong>Soft Bodies</strong> —
    including applying soft-body dynamics to a rigged character for use in animation.
    While the original syllabus references Maya, this learning guide delivers the same
    concepts using the free and open-source <strong>Blender (4.0+)</strong>.
  </div>
</section>

<!-- ===================== LECTURER ===================== -->
<section id="lecturer" aria-labelledby="lect-h">
  <div class="section-head">
    <span class="dot" style="background:var(--teal)"></span>
    <h2 id="lect-h">Your Lecturer</h2>
  </div>
  <div class="lecturer">
    <div class="avatar" aria-hidden="true"></div>
    <div>
      <h3>Mohd Faiz bin Alias</h3>
      <p>Lecturer — Multimedia &amp; 3D Animation<br>
      <strong>AEU · Asia e University, Malaysia</strong></p>
    </div>
  </div>
</section>

<!-- ===================== WEEK 1 ===================== -->
<section id="week1" aria-labelledby="w1-h">
  <div class="section-head">
    <span class="dot"></span>
    <h2>The 6-Week Programme</h2>
  </div>

  <article class="week">
    <div class="week-head">
      <span class="week-num">01</span>
      <div>
        <span class="wk-label">Week One</span>
        <h3 id="w1-h">Introduction to Rigid Bodies</h3>
      </div>
    </div>
    <div class="week-body">
      <div class="week-topics">
        <span class="topic-chip">What is a rigid body?</span>
        <span class="topic-chip">Initial velocity &amp; impulse</span>
        <span class="topic-chip">Mass · Friction · Damping</span>
        <span class="topic-chip">Collision shapes &amp; layers</span>
      </div>
      <div class="video-grid">
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="02u8Ag49Gec" data-title="Rigid Body Physics For Beginners — Blender 4.3" aria-label="Play video: Rigid Body Physics For Beginners — Blender 4.3">
              <img src="https://i.ytimg.com/vi/02u8Ag49Gec/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Rigid Body Physics for Beginners</span>
            <span class="vc">PIXXO 3D · Blender 4.3</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=02u8Ag49Gec" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="B58P5hnbdNU" data-title="Rigid Body Physics for Beginners — Domino Simulation" aria-label="Play video: Rigid Body Physics for Beginners — Domino Simulation">
              <img src="https://i.ytimg.com/vi/B58P5hnbdNU/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Rigid Body Physics — Domino Beginner Walkthrough</span>
            <span class="vc">Nik Kottmann</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=B58P5hnbdNU" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="q88mMWW2yNs" data-title="Rigid Body Physics Quick Start" aria-label="Play video: Rigid Body Physics Quick Start">
              <img src="https://i.ytimg.com/vi/q88mMWW2yNs/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Rigid Body Quick Start — Mass, Friction &amp; Bounce</span>
            <span class="vc">Physics Quick Start Tutorial</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=q88mMWW2yNs" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
      </div>
      <p class="week-note"><b>Practice:</b> Drop a stack of 10 cubes onto a plane. Experiment with mass, friction and bounciness values, and observe how each setting changes the result.</p>
    </div>
  </article>

<!-- ===================== WEEK 2 ===================== -->
  <article class="week" id="week2">
    <div class="week-head">
      <span class="week-num">02</span>
      <div>
        <span class="wk-label">Week Two</span>
        <h3>Introduction to Constraints</h3>
      </div>
    </div>
    <div class="week-body">
      <div class="week-topics">
        <span class="topic-chip">Function of constraints</span>
        <span class="topic-chip">Fixed (nail) &amp; Point (pin)</span>
        <span class="topic-chip">Hinge · Slider · Piston</span>
        <span class="topic-chip">Spring · Motor · Generic</span>
      </div>
      <div class="video-grid">
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="6BALmm_uN-c" data-title="Every Rigid Body Constraint in 10 Minutes" aria-label="Play video: Every Rigid Body Constraint in 10 Minutes">
              <img src="https://i.ytimg.com/vi/6BALmm_uN-c/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Every Rigid Body Constraint in 10 Minutes</span>
            <span class="vc">Blender Made Easy</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=6BALmm_uN-c" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="V8WSuS1GLk0" data-title="Rigid Body Hinge Constraint" aria-label="Play video: Rigid Body Hinge Constraint">
              <img src="https://i.ytimg.com/vi/V8WSuS1GLk0/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">The Hinge Constraint — Doors &amp; Swings</span>
            <span class="vc">Hinge Constraint Tutorial</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=V8WSuS1GLk0" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="-5aOtIlax3A" data-title="Wrecking Ball and Chain with Rigid Body Physics" aria-label="Play video: Wrecking Ball and Chain with Rigid Body Physics">
              <img src="https://i.ytimg.com/vi/-5aOtIlax3A/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Wrecking Ball &amp; Chain — Constraints in Action</span>
            <span class="vc">Rigid Body Chain Project</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=-5aOtIlax3A" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
      </div>
      <p class="week-note"><b>Practice:</b> Build a swinging pendulum with a hinge constraint, then upgrade it to a wrecking ball that knocks down a wall of bricks.</p>
    </div>
  </article>

<!-- ===================== WEEK 3 ===================== -->
  <article class="week" id="week3">
    <div class="week-head">
      <span class="week-num">03</span>
      <div>
        <span class="wk-label">Week Three</span>
        <h3>Active &amp; Passive Bodies · Solvers · Baking</h3>
      </div>
    </div>
    <div class="week-body">
      <div class="week-topics">
        <span class="topic-chip">Active vs Passive</span>
        <span class="topic-chip">Keying the Animated attribute</span>
        <span class="topic-chip">Rigid body world &amp; solver steps</span>
        <span class="topic-chip">Baking the simulation</span>
        <span class="topic-chip">★ Assignment 1 briefing</span>
      </div>
      <div class="video-grid">
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="kqp4QzLroNQ" data-title="Rigid Body, Collision, Physics for Complete Beginners" aria-label="Play video: Rigid Body, Collision, Physics for Complete Beginners">
              <img src="https://i.ytimg.com/vi/kqp4QzLroNQ/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Rigid Body &amp; Collision — Active/Passive Setup</span>
            <span class="vc">Complete Beginners Tutorial</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=kqp4QzLroNQ" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="1oUSgiyQ8-o" data-title="Physics Accuracy, Cache and Bake settings in Blender" aria-label="Play video: Physics Accuracy, Cache and Bake settings in Blender">
              <img src="https://i.ytimg.com/vi/1oUSgiyQ8-o/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Solver Accuracy, Cache &amp; Bake Settings</span>
            <span class="vc">Physics Settings Overview</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=1oUSgiyQ8-o" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="4WQSeevO_oU" data-title="How to Make Domino Effects in Blender 4.3" aria-label="Play video: How to Make Domino Effects in Blender 4.3">
              <img src="https://i.ytimg.com/vi/4WQSeevO_oU/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Domino Effect Project — Blender 4.3</span>
            <span class="vc">Rigid Body + Geometry Nodes</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=4WQSeevO_oU" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
      </div>
      <p class="week-note"><b>Assignment 1 (briefed this week):</b> Create a 10-second Rube-Goldberg / domino-run animation using rigid bodies and at least two constraint types. Bake your simulation before rendering.</p>
    </div>
  </article>

<!-- ===================== WEEK 4 ===================== -->
  <article class="week" id="week4">
    <div class="week-head">
      <span class="week-num">04</span>
      <div>
        <span class="wk-label">Week Four</span>
        <h3>Introduction to Soft Bodies</h3>
      </div>
    </div>
    <div class="week-body">
      <div class="week-topics">
        <span class="topic-chip">Soft body basics</span>
        <span class="topic-chip">Goal &amp; goal strength</span>
        <span class="topic-chip">Vertex weights (paint tools)</span>
        <span class="topic-chip">Edges, stiffness &amp; self-collision</span>
        <span class="topic-chip">★ Assignment 1 submission</span>
      </div>
      <div class="video-grid">
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="6Dtwhd1N0bY" data-title="Soft Body Physics for Beginners" aria-label="Play video: Soft Body Physics for Beginners">
              <img src="https://i.ytimg.com/vi/6Dtwhd1N0bY/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Soft Body Physics for Beginners</span>
            <span class="vc">Ryan King Art</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=6Dtwhd1N0bY" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="yhYrHxxbZUc" data-title="Introduction to SOFTBODY physics in Blender" aria-label="Play video: Introduction to SOFTBODY physics in Blender">
              <img src="https://i.ytimg.com/vi/yhYrHxxbZUc/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Introduction to Soft Body Physics</span>
            <span class="vc">Fast-Paced Overview</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=yhYrHxxbZUc" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="nWKH_t9IT70" data-title="Softbody Physics in Blender For Beginners" aria-label="Play video: Softbody Physics in Blender For Beginners">
              <img src="https://i.ytimg.com/vi/nWKH_t9IT70/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Soft Body Physics — Goals &amp; Weight Painting</span>
            <span class="vc">Beginner Soft Body Guide</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=nWKH_t9IT70" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
      </div>
      <p class="week-note"><b>Practice:</b> Drop a soft-body sphere down a staircase. Then use vertex-group goal weights so only half the object jiggles. <b>Submit Assignment 1 this week.</b></p>
    </div>
  </article>

<!-- ===================== WEEK 5 ===================== -->
  <article class="week" id="week5">
    <div class="week-head">
      <span class="week-num">05</span>
      <div>
        <span class="wk-label">Week Five</span>
        <h3>Soft Bodies on Rigged Characters</h3>
      </div>
    </div>
    <div class="week-body">
      <div class="week-topics">
        <span class="topic-chip">Soft body + armature</span>
        <span class="topic-chip">Jiggle &amp; secondary motion</span>
        <span class="topic-chip">Weight painting for dynamics</span>
        <span class="topic-chip">Caching soft-body results</span>
      </div>
      <div class="video-grid">
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="EdIGfANAF7M" data-title="EASY Soft Body Character Physics in Blender" aria-label="Play video: EASY Soft Body Character Physics in Blender">
              <img src="https://i.ytimg.com/vi/EdIGfANAF7M/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Easy Soft Body Character Physics</span>
            <span class="vc">SouthernShotty</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=EdIGfANAF7M" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="_QY12thfOPc" data-title="EASY Floppy and Jiggle Physics Rig in Blender 3D" aria-label="Play video: EASY Floppy and Jiggle Physics Rig in Blender 3D">
              <img src="https://i.ytimg.com/vi/_QY12thfOPc/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Floppy &amp; Jiggle Physics on a Character Rig</span>
            <span class="vc">SouthernShotty</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=_QY12thfOPc" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="eggOO9CIyp4" data-title="Soft Body Simulation — Jiggles and Wiggles" aria-label="Play video: Soft Body Simulation — Jiggles and Wiggles">
              <img src="https://i.ytimg.com/vi/eggOO9CIyp4/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Advanced Soft Body — Jiggles &amp; Wiggles</span>
            <span class="vc">Character Jiggle Tutorial</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=eggOO9CIyp4" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
      </div>
      <p class="week-note"><b>Practice:</b> Add believable jiggle to a rigged character's belly or ears using soft-body goals, then bake the cache so the result is locked for rendering.</p>
    </div>
  </article>

<!-- ===================== WEEK 6 ===================== -->
  <article class="week" id="week6">
    <div class="week-head">
      <span class="week-num">06</span>
      <div>
        <span class="wk-label">Week Six</span>
        <h3>Shatter Effects &amp; Final Project</h3>
      </div>
    </div>
    <div class="week-body">
      <div class="week-topics">
        <span class="topic-chip">Cell Fracture add-on</span>
        <span class="topic-chip">Shatter effects overview</span>
        <span class="topic-chip">Using dynamics to shatter glass</span>
        <span class="topic-chip">Caching particles &amp; shards</span>
        <span class="topic-chip">★ Final assignment briefing</span>
      </div>
      <div class="video-grid">
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="2huuzkax4l4" data-title="Breaking glass using cell fracture — Blender tutorial" aria-label="Play video: Breaking glass using cell fracture — Blender tutorial">
              <img src="https://i.ytimg.com/vi/2huuzkax4l4/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Breaking Glass with Cell Fracture</span>
            <span class="vc">Cell Fracture + Rigid Body</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=2huuzkax4l4" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="P8VHGjWBQ4w" data-title="Glass Window Breaking Simulation in Blender" aria-label="Play video: Glass Window Breaking Simulation in Blender">
              <img src="https://i.ytimg.com/vi/P8VHGjWBQ4w/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">Glass Window Breaking Simulation</span>
            <span class="vc">Window Smash Project</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=P8VHGjWBQ4w" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
        <div class="video-card">
          <div class="video-frame">
            <button class="yt-facade" data-id="cCMNgkDQGGE" data-title="How to CELL FRACTURE Glass — Blender Tutorial" aria-label="Play video: How to CELL FRACTURE Glass — Blender Tutorial">
              <img src="https://i.ytimg.com/vi/cCMNgkDQGGE/hqdefault.jpg" alt="" loading="lazy">
              <span class="play-badge" aria-hidden="true">&#9654;</span>
            </button>
          </div>
          <div class="video-meta">
            <span class="vt">How to Cell-Fracture Glass — Made Easy</span>
            <span class="vc">Take 3 Studio</span>
            <a class="yt-btn" href="https://www.youtube.com/watch?v=cCMNgkDQGGE" target="_blank" rel="noopener">&#9654; Watch on YouTube</a>
          </div>
        </div>
      </div>
      <p class="week-note"><b>Final Assignment (briefed this week):</b> Produce a 15–20 second animation combining rigid bodies, at least one constraint, a soft-body element on a character or prop, and a shatter effect. All simulations must be baked. Submission in Week 8.</p>
    </div>
  </article>
</section>

<!-- ===================== REFERENCES ===================== -->
<section id="references" aria-labelledby="ref-h">
  <div class="section-head">
    <span class="dot" style="background:var(--rose)"></span>
    <h2 id="ref-h">References</h2>
  </div>
  <ul class="ref-list">
    <li>
      <span class="rlabel">Main reference</span>
      Todd Palamar (2009), <em>Maya Studio Projects: Dynamics</em>, Sybex.
    </li>
    <li class="alt">
      <span class="rlabel">Additional reference</span>
      Autodesk Maya Press (2007), <em>The Art of Maya: An Introduction to 3D Computer Graphics</em>, Sybex.
    </li>
    <li class="alt">
      <span class="rlabel">Additional reference</span>
      Eric Keller (2007), <em>Maya Visual Effects: The Innovator's Guide</em>, Sybex.
    </li>
    <li>
      <span class="rlabel">Online reference · Blender</span>
      Blender Foundation, <em>Blender Manual — Physics: Rigid Body &amp; Soft Body</em>,
      <a href="https://docs.blender.org/manual/en/latest/physics/rigid_body/index.html">docs.blender.org</a>.
    </li>
  </ul>
</section>

</main>

<!-- ===================== FOOTER ===================== -->
<footer>
  <div class="foot-title">CSR400 · Soft &amp; Rigid Body</div>
  <p>Lecturer: Mohd Faiz bin Alias — AEU, Asia e University, Malaysia</p>
  <p>Prerequisite: CBD346 — Basic 3D Animation · Credit Value: 3</p>
  <p class="mono">Learning guide adapted for Blender 4.0+ · Embedded videos remain the property of their respective creators on YouTube.</p>
</footer>


<script>
document.addEventListener('click', function(e){
  var btn = e.target.closest('.yt-facade');
  if(!btn) return;
  var id = btn.dataset.id;
  var title = btn.dataset.title || 'YouTube video';
  var iframe = document.createElement('iframe');
  iframe.src = 'https://www.youtube-nocookie.com/embed/' + id + '?autoplay=1&rel=0';
  iframe.title = title;
  iframe.setAttribute('allow','accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture');
  iframe.setAttribute('allowfullscreen','');
  iframe.setAttribute('referrerpolicy','strict-origin-when-cross-origin');
  iframe.style.cssText = 'position:absolute;inset:0;width:100%;height:100%;border:0;';
  btn.replaceWith(iframe);
});
</script>
</body>
</html>
