---
layout: projects
title: Projects
---
<div class="project-cover">
  {% for post in site.posts %}
  <a class="project-link" href="{{ post.url }}" title="{{ post.title }}">
    <div class="cover-content-container">
      <div class="cover-image-container">
        <div class="cover-image">
          <img src="/images/{{ post.name }}/{{ post.name }}.jpg">
          <div class="overlay">
            <div class="overlay-text">
              <h4>{{ post.title }}</h4>
              <p> {{ post.year}} </p>
            </div>
          </div>
        </div>
      </div>
      <!-- <div class="cover-text-container">
          <div class="cover-text">
            <h3>{{ post.title }}</h3>
          </div>
      </div> -->
    </div>
  </a>
  {% endfor %}
</div>
