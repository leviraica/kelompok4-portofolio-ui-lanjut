<template>
    <section class="hero">
      <div class="container">
        <p class="section-label">Portofolio Tim LESA</p>
        <h1>Merancang Karya Digital<br />yang <em>Elegan</em> &amp; Bermakna</h1>
  
        <div class="byline">
          <span class="line"></span>
          <p class="names">Saskia <i>&amp;</i> Levi</p>
        </div>
  
        <p class="tagline">
          Kami sekelompok mahasiswa yang membangun website dengan Vue.js, dengan perhatian pada
          detail dan kerja sama tim.
        </p>
        <a href="#tim" class="btn">Kenali Kami</a>
      </div>
    </section>
  </template>
  
  <style scoped>
  .hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    background: radial-gradient(circle at 70% 30%, var(--bg-soft), var(--bg) 60%);
  }
  h1 {
    font-size: clamp(2.5rem, 6vw, 4.5rem);
    line-height: 1.15;
    margin: 1rem 0 2rem;
  }
  h1 em {
    color: var(--gold);
    font-style: italic;
  }
  .byline {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin-bottom: 1.5rem;
  }
  .line {
    width: 60px;
    height: 1px;
    background: var(--gold);
  }
  .names {
    font-family: var(--font-heading);
    font-style: italic;
    font-size: 1.5rem;
    letter-spacing: 0.05em;
  }
  .names i {
    color: var(--gold);
    margin: 0 0.3rem;
  }
  .tagline {
    max-width: 520px;
    color: var(--muted);
    margin-bottom: 2.5rem;
  }
  </style>