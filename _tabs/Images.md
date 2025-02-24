---
title: Image Gallery
icon: fas fa-images
order: 4
---

<div class="gallery">
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi.jpg' | relative_url }}" alt="Image 1">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/ApeInfo.jpeg' | relative_url }}" alt="Image 2">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/DoTheApe.jpg' | relative_url }}" alt="Image 3">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi2.jpg' | relative_url }}" alt="Image 4">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/2025hifi.png' | relative_url }}" alt="Image 5">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_and_joe.jpg' | relative_url }}" alt="Image 6">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_alien.jpg' | relative_url }}" alt="Image 7">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_flyer.jpg' | relative_url }}" alt="Image 8">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_frank.jpg' | relative_url }}" alt="Image 9">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_hellbilly.png' | relative_url }}" alt="Image 10">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_go_nuts.jpg' | relative_url }}" alt="Image 11">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_holiday_is_over.jpg' | relative_url }}" alt="Image 12">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_islands.jpg' | relative_url }}" alt="Image 14">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_mummies.jpeg' | relative_url }}" alt="Image 15">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_psycho.jpg' | relative_url }}" alt="Image 16">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_romance.jpg' | relative_url }}" alt="Image 17">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_romance2.jpg' | relative_url }}" alt="Image 18">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_stripper.jpeg' | relative_url }}" alt="Image 19">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_torvi.jpg' | relative_url }}" alt="Image 20">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_wayne.jpg' | relative_url }}" alt="Image 21">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hifi_zombie.jpg' | relative_url }}" alt="Image 22">
  </div>
  <div class="gallery-item">
    <img src="{{ './assets/img/hotrockin.jpg' | relative_url }}" alt="Image 23">
  </div>
</div>

<style>
.gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.gallery-item {
  flex: 1 1 calc(33.333% - 10px);
  box-sizing: border-box;
}

.gallery-item img {
  width: 100%;
  height: auto;
  display: block;
}
</style>