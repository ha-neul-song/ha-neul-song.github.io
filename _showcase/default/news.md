---
title: News
show: true
width: 8
date: 2026-01-14
---
<div class="m-4">
  {% assign count_news = site.news | size %}
  {% if count_news > 0 %}
    {% include widgets/news_card.html limit=5 %}
  {% else %}
    <p class="text-muted mb-0">No news yet.</p>
  {% endif %}
</div>
