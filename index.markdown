---
layout: default
title: Evolution of Chromosome Segregation
---

<!-- Bulma & AOS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.4/css/bulma.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
<link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css">
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>document.addEventListener('DOMContentLoaded',()=>AOS.init({once:true}));</script>

<style>
  :root { --sky-blue:#87CEEB; --magenta:#FF00FF; }

  /* make the page a flex column so footer can stick */
  html, body { height:100%; margin:0; display:flex; flex-direction:column; }

  /* background image must exist under assets/images */
  body {
    background: url('{{ '/assets/images/Dudka-lab-website-cover.png' | relative_url }}') no-repeat center/cover fixed;
  }

  /* the content wrapper grows to push footer down */
  .main-content { flex:1 0 auto; }

  /* footer always at bottom */
  .footer { margin-top:auto; }

  /* your existing overlay + cards + buttons */
  .overlay-section { background:rgba(255,255,255,0.85); padding:4rem 2rem; margin:2rem auto; border-radius:6px; max-width:960px; }
  .fancy-card { transition:transform .3s,box-shadow .3s; border-top:4px solid var(--magenta); }
  .fancy-card:hover { transform:translateY(-10px) rotate(-1deg); box-shadow:0 12px 24px rgba(0,0,0,.15); }
  .button.is-link.is-inverted { background:var(--magenta); border-color:var(--sky-blue); color:#fff; }
  .button.is-link.is-inverted:hover { background:var(--sky-blue); border-color:var(--magenta); }
</style>

<div class="main-content">
  <!-- Hero overlay -->
  <section class="section overlay-section">
    <div class="container has-text-centered">
      <h1 class="title has-text-dark animate__animated animate__fadeInDown">
        Evolution of Chromosome Segregation
      </h1>
      <h2 class="subtitle has-text-dark animate__animated animate__fadeInUp animate__delay-1s">
        Dudka Lab @ UPenn
      </h2>
      <a href="#main-sections"
         class="button is-large is-link is-inverted animate__animated animate__bounce animate__delay-2s mt-5">
        Explore ↓
      </a>
    </div>
  </section>

  <!-- Cards -->
  <section id="main-sections" class="section">
    <div class="container">
      <div class="columns is-multiline">
        <!-- Research -->
        <div class="column is-one-third" data-aos="fade-up" data-aos-delay="100">
          <a href="{{ site.baseurl }}/research/">
            <div class="card fancy-card">
              <div class="card-content has-text-centered">
                <span class="icon is-large"><i class="fas fa-flask fa-2x"></i></span>
                <p class="title is-4">Research</p>
                <p>Evolutionary mechanisms of chromosome segregation.</p>
              </div>
            </div>
          </a>
        </div>
        <!-- Publications -->
        <div class="column is-one-third" data-aos="fade-up" data-aos-delay="200">
          <a href="{{ site.baseurl }}/publications/">
            <div class="card fancy-card">
              <div class="card-content has-text-centered">
                <span class="icon is-large"><i class="fas fa-book fa-2x"></i></span>
                <p class="title is-4">Publications</p>
                <p>Browse our latest papers and preprints.</p>
              </div>
            </div>
          </a>
        </div>
        <!-- CV -->
        <div class="column is-one-third" data-aos="fade-up" data-aos-delay="300">
          <a href="{{ site.baseurl }}/cv/">
            <div class="card fancy-card">
              <div class="card-content has-text-centered">
                <span class="icon is-large"><i class="fas fa-id-card fa-2x"></i></span>
                <p class="title is-4">CV</p>
                <p>Download Damian Dudka’s curriculum vitae.</p>
              </div>
            </div>
          </a>
        </div>
      </div>
    </div>
  </section>
</div>

<footer class="footer">
  <div class="content has-text-centered">
    <p>&copy; 2025 Dudka Lab. All rights reserved.</p>
  </div>
</footer>
