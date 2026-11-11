---
layout: default
title: Home
---


<style>
/* Main palette 
  11/11/26 - made the original pallet darker/richer */
:root {
  --brown: #795348; /*now rich chestnut brown*/
  --green: #16866A; /*now jade brown*/
  --yellow: #D4B85D; /*now antique gold*/
  --ink: #30231F;
  --deep-green: #075B46;
}

/* Center the content and leave space on both sides */
.container,
.container-fluid {
  width: 90% !important;
  max-width: 1200px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  padding-left: 0 !important;
  padding-right: 0 !important;
}

main,
article,
.page-content {
  width: 100%;
  max-width: 1200px;
  margin-left: auto !important;
  margin-right: auto !important;
  padding-left: 5% !important;
  padding-right: 5% !important;
  box-sizing: border-box;
}
  
/* Overall page */
body {
  background-color: #795348;

  background-image: 
    linear-gradient(
        rgba(121, 83, 72, 0.70), /*Only 30% of backgrnd IMAGE shows up*/
        rgba(121, 83, 72, 0.70)
    ),
    url("{{'/assets/images/backgrounds/background.jpg' | relative_url}}");

  background-repeat: repeat;
  background-size: auto, 500px auto;
  background-attachment: fixed;

  color: #F5EBDD; /*warm ivory*/
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
  background-color: var(--yellow);
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
  color: #F5EBDD;
  font-family: Arial, Helvetica, sans-serif;
}

/* Links */
a {
  color: var(--yellow);
}

a:hover {
  color: #F5EBDD; /*light cream color*/
}

/* Content cards */
.card {
  background-color: var(--green);
  border: 1px solid rgba(57, 48, 45, 0.15);
  border-radius: 4px;
}

/* Buttons */
.btn {
  background-color: var(--deep-green);
  color: #F5F0E7;
  border: 1px solid var(--yellow);
  border-radius: 2px;
}

.btn:hover {
  background-color: var(--yellow);
  color: var(--ink);
}

/* Gallery rows */
.gallery-item {
  display: flex;
  align-items: center;
  gap: 22px;
  padding: 18px;
  margin: 18px 0;
  background-color: var(--green);
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

.gallery-item h3,
.gallery-item p {
  color: #FFFFFF;
}
  
/* Decorative accents */
hr {
  border-color: var(--yellow);
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

.last-updated {
  margin-top: 50px;
  padding-bottom: 15px;
  text-align: center;
  font-size: 11px;
  color: rgba(245, 235, 221, 0.65);
}  

  
</style>

# Welcome to my stationery library!
I use these in my journaling ecosystem, and wanted to share. 

Feel free to download, print, and use.

## Indexes

<!-- sheep sheep -->
<div class="gallery-item">
  <a href="{{ '/assets/images/indexes/sheep sheep.png' | relative_url }}"
    target="_blank"
    rel="noopener noreferrer">
    <img src="{{ '/assets/images/indexes/sheep sheep.png' | relative_url }}"
       alt="2027 Sheep Sheep index">
  </a>
  <div class="gallery-description">
    
    <h3>2027 Sheep Sheep</h3>
    <p>Index pages for the 2027 Sheep Sheep planner.</p>

  </div>
</div>

<!-- one piece -->
<div class="gallery-item">
  <a href="{{ '/assets/images/indexes/one piece.png' | relative_url }}"
    target="_blank"
    rel="noopener noreferrer">
    <img src="{{ '/assets/images/indexes/one piece.png' | relative_url }}"
       alt="One Piece index">
  </a>
  <div class="gallery-description">
    
    <h3>2027 One Piece</h3>
    <p>Index pages for the One Piece collab planners.</p>

  </div>
</div>

## Doodles

<!-- 11/11/2026: Disappointed kitty first batch. Greyscales. -->
<div class="gallery-item">
  <a href="{{'/assets/images/doodles/dissapointed cat.png' | relative_url}}"
    target="_blank"
    rel="noopener noreferrer">
    <img src="{{'/assets/images/doodles/dissapointed cat.png' | relative_url}}"
    alt="This cat is judging you">
  </a>
  <div class="gallery-description">

    <h3>A cat who judges</h3>
    <p>Enjoy some doodles of my kitty, who always looks so disappointed in me :')</p>
  </div>
</div>

## Other

<!-- nameplate for the first page of my SheepSheeps -->
<div class="gallery-item">
  <a href="{{'/assets/images/other/title sheep sheep.png' | relative_url}}" 
    target="_blank"
    rel="noopener noreferrer">
    <img src="{{'/assets/images/other/title sheep sheep.png' | relative_url}}"
    alt="Fat Sheep">
  </a>
  <div class="gallery-description">

    <h3>Large bellied 2027 sheep</h3>
    <p>Started using these as a nameplate for the first page of my SheepSheeps.</p>
  </div>
</div>

<!-- LAST UPDATE FOOTER -->
<div class="last-updated">
  Last updated: {{ site.time | date: "%B %d, %Y at %I:%M %p" }}
</div>

