<template>
    <footer class="footer">
      <div class="container">
        <p class="brand">LE<span>SA</span></p>
        <p class="names">Saskia &amp; Levi</p>
        <p class="copy">© 2026 LESA. Dibuat dengan Vue.js</p>
      </div>
    </footer>
  </template>
  
  <style scoped>
  .footer {
    padding: 3rem 0 2rem;
    text-align: center;
    color: var(--muted);
    font-size: 0.85rem;
    border-top: 1px solid var(--line);
  }
  .brand {
    font-family: var(--font-heading);
    font-size: 1.5rem;
    font-weight: 700;
    letter-spacing: 0.2em;
    color: var(--text);
  }
  .brand span {
    color: var(--gold);
  }
  .names {
    font-family: var(--font-heading);
    font-style: italic;
    margin: 0.3rem 0 1.5rem;
  }
  .copy {
    font-size: 0.75rem;
    letter-spacing: 0.05em;
  }
  </style>