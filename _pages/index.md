---
layout: default
pagination:
  enabled: true
permalink: /
---
<section id="#" class="cont" style="background-color: #fff;">
<div class="grid">
  <div>
    <span class="cta__text">I am Nan Wang. Designer, Engineer and Entrepreneur.</span>
  </div>
</div>
</section>

<section id="stories" style="background-color: #f4f4f4;">
<div class="posts">
  <div class="grid-xlarge">
    <h2 class="cta__text">
      <span>Our Stories</span>
    </h2>

    <div class="posts__container" data-columns>

      {% for post in site.posts %}

        <!-- The tag below includes the markup for each post - partials/post-card.html -->
        {% include post-card.html %}

      {% endfor %}
    </div>
  </div>

</div>
</section>


<section id="kiss" class="cta bg-black">
  <a class="cta__link" href="{{ '/kisses/' | prepend: site.baseurl }}">
    <span class="cta__text">Let’s Waving</span>
  </a>
</section>
