---
title: "Engagement"
summary: "Fieldwork, teaching, outreach, and public engagement"
date: 2026-06-28
type: landing

sections:
  - block: markdown
    content:
      title: "Engagement"
      text: |
        I love teaching in both informal and formal settings. Whether I am working with students in a classroom, sharing fossils with museum visitors, doing fieldwork, or helping make paleontology more accessible to broader audiences, I am interested in creating spaces where people can ask questions, make observations, and connect with natural history.

        <div class="outreach-split">
          <div class="outreach-text">
            <h2>Teaching and mentoring</h2>
            <p>I enjoy helping students build confidence with scientific concepts, data, and observation-based thinking. My teaching interests include paleontology, evolution, biodiversity, museum collections, and quantitative approaches to understanding the history of life.</p>
            <p>I am especially interested in making scientific methods feel approachable, whether that means guiding students through fossil identification, helping them understand figures and datasets, or encouraging them to ask their own research questions.</p>
          </div>

          <div class="outreach-carousel-wrap">
            {{< carousel pattern="teaching-*" alt="Teaching and mentoring photo" >}}
          </div>
        </div>

        <div class="outreach-split">
          <div class="outreach-carousel-wrap">
            {{< carousel pattern="fieldwork-*" alt="Fieldwork and collections photo" >}}
          </div>

          <div class="outreach-text">
            <h2>Fieldwork and collections</h2>
            <p>Fieldwork and museum collections are central to how I think about paleontology. Collecting, documenting, and revisiting specimens connects local field observations to larger questions about biodiversity, evolution, and environmental change through deep time.</p>
            <p>I am interested in how field-based research and museum collections can work together to expand what we know about fossil fishes and the ecosystems they lived in.</p>
          </div>
        </div>

        <div class="outreach-split">
          <div class="outreach-text">
            <h2>Museum and public outreach</h2>
            <p>I care deeply about museum-based outreach because collections provide a direct way for people to connect with deep time, evolution, and the history of life. Fossils can make abstract scientific ideas feel tangible and exciting.</p>
            <p>My outreach work focuses on communicating paleontology in ways that are welcoming, visually engaging, and accessible to people with different backgrounds and levels of scientific experience.</p>
          </div>

          <div class="outreach-carousel-wrap">
            {{< carousel pattern="outreach-*" alt="Museum and public outreach photo" >}}
          </div>
        </div>

        <script>
          document.addEventListener("DOMContentLoaded", function () {
            const carousels = document.querySelectorAll(".outreach-carousel");

            carousels.forEach(function (carousel) {
              const slides = carousel.querySelectorAll(".carousel-slide");
              let index = 0;

              if (slides.length <= 2) return;

              carousel.scrollTo({
                left: 0,
                behavior: "auto"
              });

              setInterval(function () {
                index = index + 1;

                carousel.scrollTo({
                  left: carousel.clientWidth * index,
                  behavior: "smooth"
                });

                if (index === slides.length - 1) {
                  setTimeout(function () {
                    carousel.scrollTo({
                      left: 0,
                      behavior: "auto"
                    });
                    index = 0;
                  }, 700);
                }
              }, 3000);
            });
          });
        </script>
---
