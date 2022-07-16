---
layout: page
permalink: /
---

<section class="section site-header text-center">
  <!-- {% include landing.html %} -->
  <div class="section-content">
    <h1 class="site-header-text"> 
      Hi, I am {{ site.author.name }}.
      <br>
      {{ site.author.description }} 
    </h1>
  </div>
</section>

<section class="section section-news">
  <div class="section-content">
    {% include about/timeline_light.html title="Recent News" source=site.data.news %}
  </div>
</section>

