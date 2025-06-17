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

    <p class="text-muted wow animated slideInUp" data-wow-delay=".15s" style="margin-top: 40px">{{ site.description }}</p>

  </div>
</div>

## Featured Project

<div class="wow animated fadeIn" data-wow-delay=".15s">
  <a href="projects/1-rate-my-transit" class="project card text-themed" target="blank">
    <div class="row g-0">
      <div class="col-md-4">
        <img src="rmt_assets/cover.png" class="img-fluid rounded-start" alt="Rate My Transit cover image">
      </div>
      <div class="col-md-8">
        <div class="card-body">
          <h5 class="card-title">Rate My Transit</h5>
          <p class="card-text"><small class="text-body-secondary">January 1, 2024 - February 1, 2024</small></p>
          <p class="card-text">A mobile app that provides real time updates on travel conditions from the local transit community. Using Rate My Transit, transit users share information with each other to improve the experience for all riders.</p>
          <p id="tools" class="card-text">
            <span class="badge badge-pill badge-primary ml-1">App Design</span>
            <span class="badge badge-pill badge-primary ml-1">Public Transit</span>
            <span class="badge badge-pill badge-primary ml-1">Social Media</span>
          </p>
        </div>
      </div>
    </div>
  </a>
</div>
