<script setup>
const projects = [
  { title: 'Proyek Pertama', tag: 'Vue.js' },
  { title: 'Proyek Kedua', tag: 'UI Design' },
  { title: 'Proyek Ketiga', tag: 'Web App' },
]
</script>

<template>
  <section id="proyek" class="section">
    <div class="container">
      <p class="section-label">Proyek</p>
      <h2>Karya Pilihan</h2>
      <div class="grid">
        <article v-for="p in projects" :key="p.title" class="project">
          <div class="thumb"></div>
          <span class="tag">{{ p.tag }}</span>
          <h3>{{ p.title }}</h3>
        </article>
      </div>
    </div>
  </section>
</template>

<style scoped>
.section {
  padding: 7rem 0;
  background: var(--bg-soft);
}
h2 {
  font-size: 2.5rem;
  margin: 0.5rem 0 3rem;
}
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
}
.thumb {
  aspect-ratio: 4 / 3;
  background: linear-gradient(135deg, #1b2347, #0b1020);
  border: 1px solid var(--line);
  margin-bottom: 1rem;
  transition: border-color 0.3s;
}
.project:hover .thumb {
  border-color: var(--gold);
}
.tag {
  color: var(--gold);
  font-size: 0.75rem;
  letter-spacing: 0.2em;
  text-transform: uppercase;
}
h3 {
  font-size: 1.4rem;
  margin-top: 0.3rem;
}
</style>