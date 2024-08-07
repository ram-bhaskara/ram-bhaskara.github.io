---
layout: publications
title: "Publications"
permalink: /publications/
---

<h2>Publications</h2>
<ul class="publication-list">
  {% for publication in site.data.publications %}
    <li class="publication-item">
      <div class="publication-image">
        <img src="{{ publication.image | relative_url }}" alt="Publication Image">
      </div>
      <div class="publication-details">
        <strong class="publication-title">
          {% if publication.paper_url %}
            <a href="{{ publication.paper_url }}" target="_blank">{{ publication.title }}</a>
          {% else %}
            {{ publication.title }}
          {% endif %}
        </strong><br>
        <div class="publication-authors">
          {% assign authors = publication.authors | split: ", " %}
          {% for author in authors %}
            {% if author == "Ramchander Rao Bhaskara" %}
              <strong>{{ author }}</strong>{% if forloop.last == false %},{% endif %}
            {% else %}
              {{ author }}{% if forloop.last == false %},{% endif %}
            {% endif %}
          {% endfor %}
        </div>
        <div class="publication-journal">
          <em>{{ publication.journal }}</em>, {{ publication.year }}
        </div>
        <div class="publication-links">
          {% if publication.paper_url %}
            [<a href="{{ publication.paper_url }}" target="_blank">Paper</a>]
          {% endif %}
          {% if publication.code_url %}
            [<a href="{{ publication.code_url }}" target="_blank">Code</a>]
          {% endif %}
          {% if publication.award %}
            <span class="publication-award"><strong>{{ publication.award }}</strong></span>
          {% endif %}
        </div>
      </div>
    </li>
  {% endfor %}
</ul>

