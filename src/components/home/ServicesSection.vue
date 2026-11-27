<script setup>
const services = [
  { no: '01', title: 'Web Development', desc: 'Website responsif dan cepat dengan Vue.js.' },
  { no: '02', title: 'UI/UX Design', desc: 'Tampilan bersih dan nyaman dipakai.' },
  { no: '03', title: 'Kolaborasi Tim', desc: 'Alur kerja rapi dengan Git dan GitHub.' },
]
</script>

<template>
  <section id="layanan" class="section">
    <div class="container">
      <p class="section-label">Layanan</p>
      <h2>Yang Kami Kerjakan</h2>
      <div class="grid">
        <article v-for="s in services" :key="s.no" class="card">
          <span class="no">{{ s.no }}</span>
          <h3>{{ s.title }}</h3>
          <p>{{ s.desc }}</p>
        </article>
      </div>
    </div>
  </section>
</template>

<style scoped>
.section {
  padding: 7rem 0;
}
h2 {
  font-size: 2.5rem;
  margin: 0.5rem 0 3rem;
}
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.5rem;
}
.card {
  padding: 2.5rem 2rem;
  border: 1px solid var(--line);
  background: var(--bg-soft);
  transition:
    transform 0.3s,
    border-color 0.3s;
}
.card:hover {
  transform: translateY(-6px);
  border-color: var(--gold);
}
.no {
  color: var(--gold);
  font-family: var(--font-heading);
  font-size: 1.2rem;
}
h3 {
  font-size: 1.4rem;
  margin: 1rem 0 0.5rem;
}
p {
  color: var(--muted);
}
</style>