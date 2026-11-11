---
layout: default
title: Home
---


<style>
/* Main palette */
:root {
  --light-brown-drab: #B59392;
  --glaucous-green: #B4CDC2;
  --pyrite-yellow: #CAB356;
  --ink: #39302D;
  --deep-green: #526D61;
}

/* Overall page */
body {
  background-color: #F2EEE5;

  background-image: url("{{'/assets/images/backgrounds/background.jpg' | relative_url}}");

  background-repeat: repeat;
  background-size: 500px auto;
  background-attachment: fixed;

  color: var(--ink);
}

/* Header branding */
.navbar {
  background-color: var(--deep-green) !important;
  padding-top: 14px;
  padding-bottom: 14px;
}

.navbar .navbar-brand {
  color: #F5F0E7 !important;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 25px;
  letter-spacing: 1px;
}

/* Yellow navigation tabs */
.navbar .nav-item {
  margin: 0 5px;
}

.navbar .nav-link {
  background-color: var(--pyrite-yellow);
  color: var(--ink) !important;
  padding: 8px 15px !important;
  border-radius: 2px;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 14px;
  letter-spacing: 0.5px;
}

.navbar .nav-link:hover {
  background-color: #E0CC82;
  color: var(--ink) !important;
}

/* Headings */
h1, h2, h3, h4 {
  color: var(--ink);
  font-family: Arial, Helvetica, sans-serif;
}

/* Links */
a {
  color: var(--deep-green);
}

a:hover {
  color: var(--pyrite-yellow);
}

/* Content cards */
.card {
  background-color: var(--glaucous-green);
  border: 1px solid rgba(57, 48, 45, 0.15);
  border-radius: 4px;
}

/* Buttons */
.btn {
  background-color: var(--deep-green);
  color: #F5F0E7;
  border: 1px solid var(--pyrite-yellow);
  border-radius: 2px;
}

.btn:hover {
  background-color: var(--pyrite-yellow);
  color: var(--ink);
}

/* Gallery rows */
.gallery-item {
  display: flex;
  align-items: center;
  gap: 22px;
  padding: 18px;
  margin: 18px 0;
  background-color: var(--glaucous-green);
  border: 1px solid rgba(57, 48, 45, 0.18);
  border-radius: 4px;
}

/* Square thumbnails */
.gallery-item img {
  width: 150px;
  height: 150px;
  flex-shrink: 0;
  object-fit: cover;
  object-position: center;
  border-radius: 3px;
}

/* Descriptions */
.gallery-description {
  flex: 1;
  min-width: 0;
}

.gallery-description h3 {
  margin-top: 0;
  margin-bottom: 8px;
}

.gallery-description p {
  margin-bottom: 8px;
}

/* Decorative accents */
hr {
  border-color: var(--pyrite-yellow);
}

/* Mobile layout */
@media (max-width: 600px) {
  .gallery-item {
    gap: 12px;
    padding: 10px;
  }

  .gallery-item img {
    width: 105px;
    height: 105px;
  }
}
</style>

# Welcome to my stationery library!
I use these in my journaling ecosystem, and wanted to share. 

Feel free to download, print, and use.

## Indexes
<!-- sheep sheep -->
<div class="gallery-item">
  <img src="{{ '/assets/images/indexes/sheep sheep.png' | relative_url }}"
       alt="2027 Sheep Sheep index">
  <div class="gallery-description">
    
    <h3>2027 Sheep Sheep</h3>
    <p>Index pages for the 2027 Sheep Sheep planner.</p>

  </div>
</div>

<!-- one piece -->
<div class="gallery-item">
  <img src="{{ '/assets/images/indexes/one piece.png' | relative_url }}"
       alt="One Piece index">
  <div class="gallery-description">
    
    <h3>2027 One Piece</h3>
    <p>Index pages for the One Piece collab planners.</p>

  </div>
</div>

## Doodles
<!-- 11/11/2027: Disappointed kitty first batch. Greyscales. -->
<div class="gallery-item">
  <img src="{{'/assets/images/doodles/dissapointed cat.png' | relative_url}}"
    alt="This cat is judging you">
  <div class="gallery-description">

    <h3>A cat who judges</h3>
    <p>Enjoy some doodles of my kitty, who always looks so disappointed in me :')</p>
  </div>
</div>

## Other
<!-- nameplate for the first page of my SheepSheeps -->
<div class="gallery-item">
  <img src="{{'/assets/images/other/title sheep sheep.png' | relative_url}}"
    alt="Fat Sheep">
  <div class="gallery-description">

    <h3>Large bellied 2027 sheep</h3>
    <p>Started using these as a nameplate for the first page of my SheepSheeps.</p>
  </div>
</div>
