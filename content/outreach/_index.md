---
title: "Outreach"
summary: "Teaching, outreach, and public engagement"
date: 2026-06-28
type: landing

sections:
  - block: markdown
    content:
      title: "Outreach"
      text: |
        I love teaching in both informal and formal settings. Whether I am working with students in a classroom, sharing fossils with museum visitors, or helping make paleontology more accessible to broader audiences, I am interested in creating spaces where people can ask questions, make observations, and connect with natural history.

        <div class="outreach-split">
          <div class="outreach-text">
            <h2>Teaching and mentoring</h2>
            <p>I enjoy helping students build confidence with scientific concepts, data, and observation-based thinking. My teaching interests include paleontology, evolution, biodiversity, museum collections, and quantitative approaches to understanding the history of life.</p>
            <p>I am especially interested in making scientific methods feel approachable, whether that means guiding students through fossil identification, helping them understand figures and datasets, or encouraging them to ask their own research questions.</p>
          </div>

          <div class="outreach-carousel" aria-label="Teaching and mentoring photos">
            <img src="teaching-1.jpg" alt="Teaching and mentoring photo 1">
            <img src="teaching-2.jpg" alt="Teaching and mentoring photo 2">
            <img src="teaching-3.jpg" alt="Teaching and mentoring photo 3">
          </div>
        </div>

        <div class="outreach-split">
          <div class="outreach-carousel" aria-label="Museum and public outreach photos">
            <img src="outreach-1.jpg" alt="Museum and public outreach photo 1">
            <img src="outreach-2.jpg" alt="Museum and public outreach photo 2">
            <img src="outreach-3.jpg" alt="Museum and public outreach photo 3">
          </div>

          <div class="outreach-text">
            <h2>Museum and public outreach</h2>
            <p>I care deeply about museum-based outreach because collections provide a direct way for people to connect with deep time, evolution, and the history of life. Fossils can make abstract scientific ideas feel tangible and exciting.</p>
            <p>My outreach work focuses on communicating paleontology in ways that are welcoming, visually engaging, and accessible to people with different backgrounds and levels of scientific experience.</p>
          </div>
        </div>

        <script>
          document.addEventListener("DOMContentLoaded", function () {
            const carousels = document.querySelectorAll(".outreach-carousel");

            carousels.forEach(function (carousel) {
              const slides = carousel.querySelectorAll("img");
              let index = 0;

              if (slides.length <= 1) return;

              setInterval(function () {
                index = (index + 1) % slides.length;
                carousel.scrollTo({
                  left: slides[index].offsetLeft,
                  behavior: "smooth"
                });
              }, 2000);
            });
          });
        </script>
---
