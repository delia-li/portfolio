---
layout: default
permalink: /
---

<div class="row justify-content-center align-items-center p-4">
  <div class="col-md-6 text-center mt-4" style="width: 100%">

    <!-- Fine Circle Responsive Image -->
    <div id="container" class="mx-auto" style="width: 175px;">
      <div id="dummy"></div>
      <div id="element">
        <img src="{{ site.author.image }}" alt="{{ site.title }}" class="circle-image wow animated zoomIn" data-wow-delay=".1s">
      </div>
    </div>

    <p class="text-muted wow animated slideInUp" data-wow-delay=".15s">{{ site.description }}</p>

  </div>
</div>

## Featured Project

  <div class="wow animated fadeIn" data-wow-delay=".15s">
    <a href="projects/1-rate-my-transit" class="project card text-themed" {%- if external and site.open_new_tab -%} target="_blank" {%- endif -%} >
    <div class="card">
      <img class="card-img-top" src="rmt_assets/cover.png" alt="Rate My Transit cover image"/>
      <div class="card-body">
        <h5 class="card-title">Rate My Transit</h5>
        <p class="card-text">A mobile app that provides real time updates on travel conditions from the local transit community. Using Rate My Transit, transit users share information with each other to improve the experience for all riders.</p>
        <p class="card-text"><small class="text-muted">January 1, 2024 - February 1, 2024</small></p>
      </div>
    </div>
