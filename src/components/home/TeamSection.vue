<script setup>
const members = [
  { initial: 'S', name: 'Saskia', role: 'Anggota Tim', part: 'SA' },
  { initial: 'L', name: 'Levi', role: 'Anggota Tim', part: 'LE' },
]
</script>

<template>
  <section id="tim" class="section">
    <div class="container">
      <p class="section-label">Tim Kami</p>
      <h2>Di Balik <em>LESA</em></h2>
      <p class="intro">
        <strong>LE</strong> dari Levi dan <strong>SA</strong> dari Saskia. Dua nama, satu tim,
        satu tujuan.
      </p>

      <div class="grid">
        <article v-for="m in members" :key="m.name" class="member">
          <div class="monogram">{{ m.initial }}</div>
          <h3>{{ m.name }}</h3>
          <span class="gold-line"></span>
          <p class="role">{{ m.role }}</p>
        </article>
      </div>
    </div>
  </section>
</template>

<style scoped>
.section {
  padding: 7rem 0;
  text-align: center;
}
h2 {
  font-size: 2.5rem;
  margin: 0.5rem 0 1rem;
}
h2 em {
  color: var(--gold);
  font-style: italic;
  letter-spacing: 0.1em;
}
.intro {
  color: var(--muted);
  max-width: 460px;
  margin: 0 auto 4rem;
}
.intro strong {
  color: var(--gold);
  font-weight: 500;
}
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 300px));
  justify-content: center;
  gap: 2rem;
}
.member {
  padding: 3rem 2rem;
  border: 1px solid var(--line);
  background: var(--bg-soft);
  transition:
    transform 0.3s,
    border-color 0.3s;
}
.member:hover {
  transform: translateY(-6px);
  border-color: var(--gold);
}
.monogram {
  width: 110px;
  height: 110px;
  margin: 0 auto 1.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 1px solid var(--gold);
  border-radius: 50%;
  font-family: var(--font-heading);
  font-style: italic;
  font-size: 3rem;
  color: var(--gold);
  background: radial-gradient(circle, rgba(201, 169, 97, 0.12), transparent 70%);
}
h3 {
  font-size: 1.8rem;
  letter-spacing: 0.08em;
}
.gold-line {
  display: block;
  width: 40px;
  height: 1px;
  background: var(--gold);
  margin: 1rem auto;
}
.role {
  color: var(--muted);
  font-size: 0.8rem;
  letter-spacing: 0.2em;
  text-transform: uppercase;
}
</style>