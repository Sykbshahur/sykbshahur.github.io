---
layout: page
title: Photo Gallery
permalink: /gallery/
---

<style>
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    grid-gap: 20px;
    padding: 20px 0;
}

.gallery-item {
    position: relative;
    overflow: hidden;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.gallery-item img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    transition: transform 0.3s ease;
}

.gallery-item:hover img {
    transform: scale(1.05);
}

.gallery-caption {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: rgba(0,0,0,0.7);
    color: white;
    padding: 10px;
    font-size: 0.9em;
}
</style>

## Daily Photos

<div class="gallery">
    <div class="gallery-item">
        <img src="path_to_photo1.jpg" alt="Photo description">
        <div class="gallery-caption">Photo Caption 1 - Date</div>
    </div>
    
    <div class="gallery-item">
        <img src="path_to_photo2.jpg" alt="Photo description">
        <div class="gallery-caption">Photo Caption 2 - Date</div>
    </div>
    
    <!-- Add more gallery items as needed -->
</div>