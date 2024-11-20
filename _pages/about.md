---
permalink: /
title: "Greetings! this is Fahim"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

### Academic Background
I am a recent graduate from East West University, where I earned my degree in Computer Science and Engineering with a major in Data Science. Throughout my academic journey, I developed a strong foundation in data analytics, deep learning, and Big Data technologies. My studies fueled my passion for solving real-world problems with data-driven solutions, and I took every opportunity to expand my knowledge in these areas, preparing me for the evolving demands of the tech industry.

### Projects
During my time at university, I worked on a variety of projects that allowed me to apply my skills in data science, software engineering, and web development. One of my notable projects involved developing a web-based platform for agricultural data analytics, using machine learning to improve crop yield predictions. Additionally, I have explored autonomous systems, leveraging AI and deep learning techniques to create models that can drive innovation in automation. These hands-on experiences helped me hone my ability to design, build, and implement complex solutions across different sectors.

### Interests
I have a deep interest in applying technology to industries such as agriculture and autonomous systems. I am particularly passionate about leveraging AI and data science to address challenges in these fields, whether it's optimizing farming practices or advancing automation technologies. Outside of tech, I have a keen entrepreneurial spirit, running several business ventures that allow me to merge my technical expertise with practical, real-world applications. This blend of innovation and entrepreneurship drives my ongoing commitment to exploring new ways technology can improve lives.

### Current Tasks
Currently, I am focusing on a variety of initiatives, including the development of an alumni portal for my university in collaboration with fellow alumni. Alongside that, I continue to work on several business ventures in my country, applying my knowledge of data science and web development to build practical solutions that make an impact. These projects keep me engaged with both the academic and entrepreneurial worlds, allowing me to constantly learn and grow as I tackle new challenges.

### Future Goals
Looking ahead, my goal is to deepen my expertise in AI and autonomous systems, particularly focusing on how these technologies can be applied to solve real-world problems in agriculture, transportation, and other industries. I am also eager to expand my entrepreneurial ventures, using the insights and skills I’ve gained to create solutions that drive change. In the long term, I aspire to lead collaborative projects that push the boundaries of technology, innovate new applications, and contribute to the greater good through technology-driven solutions.


### Photo Gallery

<div class="slider">
  <div class="slides">
    <div class="slide">
      <img src="https://github.com/fahimrayhan/fahimrayhan.github.io/blob/master/gallery/robi2.jpeg?raw=true" alt="Robi Datathon 3.0">
      <div class="caption">Tensor Titans Team Photo in Robi Datathon 3.0 ~ 2024</div>
    </div>
    <div class="slide">
      <img src="https://github.com/fahimrayhan/fahimrayhan.github.io/blob/master/gallery/robi1.jpeg?raw=true" alt="Image 3">
      <div class="caption">Robi Datathon 3.0 ~ 2024</div>
    </div>
    <div class="slide">
      <img src="https://github.com/fahimrayhan/fahimrayhan.github.io/blob/master/gallery/robi4.jpeg?raw=true" alt="Image 2">
      <div class="caption">Tensor Titans Team Photo in Robi Datathon 3.0 ~ 2024</div>
    </div>
    <div class="slide">
      <img src="https://github.com/fahimrayhan/fahimrayhan.github.io/blob/master/gallery/robi3.jpeg?raw=true" alt="Image 3">
      <div class="caption">Robi Datathon 3.0 ~ 2024</div>
    </div>
    <div class="slide">
      <img src="https://github.com/fahimrayhan/fahimrayhan.github.io/blob/master/gallery/robi3.jpeg?raw=true" alt="Image 4">
      <div class="caption">Team Tensor Titan ~ Robi Datathon 3.0</div>
    </div>
    <div class="slide">
      <img src="https://github.com/fahimrayhan/fahimrayhan.github.io/blob/master/gallery/event4.jpg?raw=true" alt="Image 5">
      <div class="caption">Inter College Programming Contest (Web) ~ ACC IT Carnival</div>
    </div>
    <div class="slide">
      <img src="https://github.com/fahimrayhan/fahimrayhan.github.io/blob/master/gallery/event5.jpg?raw=true" alt="Image 6">
      <div class="caption">Inter College Programming Contest (Web) ~ ACC IT Carnival</div>
    </div>
  </div>
  <a class="prev" onclick="changeSlide(-1)">&#10094;</a>
  <a class="next" onclick="changeSlide(1)">&#10095;</a>
</div>

<style>
  .slider {
    position: relative;
    max-width: 90%;
    margin: auto;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  }

  .slides {
    display: flex;
    transition: transform 0.5s ease-in-out;
    width: 100%; /* Ensure slides container takes full width */
  }

  .slide {
    min-width: 100%;
    box-sizing: border-box;
  }

  .slide img {
    width: 100%;
    height: auto;
    border-radius: 10px 10px 0 0;
  }

  .caption {
    text-align: center;
    background: rgba(0, 0, 0, 0.7);
    color: #fff;
    padding: 15px;
    font-size: 1em;
  }

  .prev, .next {
    cursor: pointer;
    position: absolute;
    top: 50%;
    padding: 16px;
    margin-top: -22px;
    color: white;
    font-weight: bold;
    font-size: 18px;
    transition: 0.6s ease;
    user-select: none;
    background-color: rgba(0, 0, 0, 0.5);
  }

  .next {
    right: 0;
    border-radius: 3px 0 0 3px;
  }

  .prev {
    left: 0;
    border-radius: 0 3px 3px 0;
  }

  .prev:hover, .next:hover {
    background-color: rgba(0, 0, 0, 0.8);
  }
</style>

<script>
  let currentIndex = 0;
  const slides = document.querySelectorAll('.slide');

  function showSlide(index) {
    if (index >= slides.length) {
      currentIndex = 0;
    } else if (index < 0) {
      currentIndex = slides.length - 1;
    } else {
      currentIndex = index;
    }
    const offset = -currentIndex * 100;
    document.querySelector('.slides').style.transform = `translateX(${offset}%)`;
  }

  function changeSlide(step) {
    clearInterval(autoSlideInterval);
    showSlide(currentIndex + step);
    autoSlideInterval = setInterval(() => changeSlide(1), 2000);
  }

  let autoSlideInterval = setInterval(() => changeSlide(1), 2000);

  document.querySelector('.next').addEventListener('click', () => changeSlide(1));
  document.querySelector('.prev').addEventListener('click', () => changeSlide(-1));
</script>