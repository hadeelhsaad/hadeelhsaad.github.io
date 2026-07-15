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
        My entrance into science was shaped by museums and mentorship. I love teaching in both informal and formal settings, whether I am working with students in the classroom, sharing fossils with museum visitors, or doing fieldwork.

        Here, I provide a brief overview of the experiences that have shaped my values around sharing knowledge with the public. Please take a look at my CV for a complete list of my activities.

        <div class="outreach-split">
          <div class="outreach-text">
            <h2>Teaching and mentoring</h2>

            <p>Early in my undergraduate career, I took several courses in K–12 education. I have since used that training to develop lessons and teach in K–12 settings, and those experiences continue to shape how I work with college students today.</p>

            <p>I have taught courses in organismal biology, cell and molecular biology, and introductory geography at multiple institutions and at both the undergraduate and graduate levels. I have also served as an instructor for field-based courses focused on high school and college preparation. In addition, I have worked as a guest lecturer and invited speaker, leading lectures and coding workshops for participants with a wide range of backgrounds and experience levels.</p>

            <p>Mentoring is another important part of my teaching. At the University of Michigan, I have worked with several students through the Undergraduate Research Opportunity Program (UROP). UROP is also how I first became involved in research, so it is especially meaningful to support undergraduate students in the same way that others once supported me.</p>
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

            <p>If it were not for the museums I visited as a child and during my early undergraduate years, I would not be fortunate enough to be a researcher today. Museum outreach, particularly specimen-based outreach, offers a direct and tangible way for people to connect with biodiversity, evolution, and the history of life.</p>

            <p>Since my undergraduate years, I have participated in a wide range of museum and public outreach activities. These experiences have included serving as an Evolution Ambassador at the Smithsonian, completing science communication fellowships, developing new museum activities, participating in a museum studies fellowship, contributing to digital media at the University of Michigan Museum of Natural History, and helping create museum exhibits.</p>
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

              if (slides.length === 0) return;

              slides[0].classList.add("active");

              if (slides.length === 1) return;

              setInterval(function () {
                slides[index].classList.remove("active");
                index = (index + 1) % slides.length;
                slides[index].classList.add("active");
              }, 4000);
            });
          });
        </script>
---
