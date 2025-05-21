---
layout: default
title: Evolution of chromosome segregation
---

<!-- Link to compiled SCSS -->
<link rel="stylesheet" href="{{ '/assets/css/main.css' | relative_url }}">

<!-- Hero with DNA/chromosome background -->
<section
  class="hero is-medium is-dark"
  style="background-image: url('/assets/images/chromosome-bg.jpg');
         background-size: cover;
         background-position: center;"
>
  <div class="hero-body has-text-centered">
    <h1 class="title has-text-white">Evolution of Chromosome Segregation</h1>
    <h2 class="subtitle has-text-white">Dudka Lab</h2>
  </div>
</section>

<!-- Card grid for main sections -->
<section class="section">
  <div class="container">
    <div class="columns is-multiline is-variable is-4">
      <!-- Research Card -->
      <div class="column is-4">
        <a href="{{ site.baseurl }}/research/">
          <div class="card has-text-centered">
            <div class="card-content">
              <span class="icon is-large">
                <i class="fas fa-flask fa-2x"></i>
              </span>
              <p class="title is-4">Research</p>
              <p>Evolutionary mechanisms of chromosome segregation.</p>
            </div>
          </div>
        </a>
      </div>

      <!-- Publications Card -->
      <div class="column is-4">
        <a href="{{ site.baseurl }}/publications/">
          <div class="card has-text-centered">
            <div class="card-content">
              <span class="icon is-large">
                <i class="fas fa-book fa-2x"></i>
              </span>
              <p class="title is-4">Publications</p>
              <p>Browse our latest papers and preprints.</p>
            </div>
          </div>
        </a>
      </div>

      <!-- CV Card -->
      <div class="column is-4">
        <a href="{{ site.baseurl }}/cv/">
          <div class="card has-text-centered">
            <div class="card-content">
              <span class="icon is-large">
                <i class="fas fa-id-card fa-2x"></i>
              </span>
              <p class="title is-4">CV</p>
              <p>Download Damian Dudka’s curriculum vitae.</p>
            </div>
          </div>
        </a>
      </div>
    </div>
  </div>
</section>
