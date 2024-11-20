---
layout: archive
title: "Hobbies"
permalink: /hobbies/
author_profile: true
# redirect_from:
#   - /resume
---


<section id="hobbies">
  <h2>Hobbies</h2>
  <div class="hobby-cards">
    <div class="hobby-card">
      <div class="card-icon">
        <img src="gallery/travelling.jpg" alt="Traveling">
      </div>
      <div class="card-content">
        <h3>Traveling</h3>
        <!-- <p>Explore new cultures and landscapes.</p> -->
      </div>
    </div>
    <div class="hobby-card">
      <div class="card-icon">
        <img src="path/to/your/cycling-image.jpg" alt="Cycling">
      </div>
      <div class="card-content">
        <h3>Cycling</h3>
        <!-- <p>Enjoy the freedom and health benefits.</p> -->
      </div>
    </div>
    <div class="hobby-card">
      <div class="card-icon">
        <img src="path/to/your/gardening-image.jpg" alt="Gardening">
      </div>
      <div class="card-content">
        <h3>Gardening</h3>
        <!-- <p>Nurture plants and create a serene space.</p> -->
      </div>
    </div>
    <div class="hobby-card">
      <div class="card-icon">
        <img src="path/to/your/photography-image.jpg" alt="Photography">
      </div>
      <div class="card-content">
        <h3>Photography</h3>
        <!-- <p>Capture moments and preserve memories.</p> -->
      </div>
    </div>
  </div>
</section>

<style>
#hobbies {
  margin: 20px 0;
}

.hobby-cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.hobby-card {
  background-color: #f2f2f2;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  margin: 10px;
  padding: 20px;
  width: calc(25% - 20px); /* Adjust width as needed */
}

.card-icon {
  text-align: center;
  margin-bottom: 10px;
}

.card-icon i {
  font-size: 36px;
  color: #333;
}

.card-content h3 {
  margin: 0;
  font-size: 18px;
  font-weight: bold;
}

.card-content p {
  margin: 5px 0;
  line-height: 1.5;
}
</style>