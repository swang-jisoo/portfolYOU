---
layout: page
permalink: /
---

<section class="section site-header text-center">
  <!-- {% include landing.html %} -->
  <div class="section-content">
    <h1> 
      Hi, I am {{ site.author.name }}.
      <br>
      {{ site.author.description }} 
    </h1>
  </div>
</section>

<section class="section">
  {% include about/timeline_light.html title="Recent News" source=site.data.news %}
</section>

