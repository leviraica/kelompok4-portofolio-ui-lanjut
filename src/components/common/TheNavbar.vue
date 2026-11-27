<template>
    <header class="navbar">
      <div class="container bar">
        <RouterLink to="/" class="logo">LE<span>SA</span></RouterLink>
        <nav>
          <a href="#tim">Tim</a>
          <a href="#layanan">Layanan</a>
          <a href="#proyek">Proyek</a>
          <a href="#kontak">Kontak</a>
        </nav>
      </div>
    </header>
  </template>
  
  <style scoped>
  .navbar {
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 10;
    background: rgba(11, 16, 32, 0.85);
    backdrop-filter: blur(8px);
    border-bottom: 1px solid var(--line);
  }
  .bar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 70px;
  }
  .logo {
    font-family: var(--font-heading);
    font-size: 1.6rem;
    font-weight: 700;
    letter-spacing: 0.2em;
  }
  .logo span {
    color: var(--gold);
  }
  nav a {
    margin-left: 2rem;
    font-size: 0.8rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--muted);
    transition: color 0.3s;
  }
  nav a:hover {
    color: var(--gold);
  }
  
  @media (max-width: 600px) {
    nav a {
      margin-left: 1rem;
      font-size: 0.7rem;
    }
  }
  </style>