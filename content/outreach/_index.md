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
        My path into science was shaped by museums and mentorship. I believe science should not be restricted to traditional academic settings, so you can often find me working with students in the classroom, sharing fossils with museum visitors, or conducting fieldwork.

        Here, I provide a brief overview of the experiences that have shaped my commitment to making scientific knowledge accessible to the public. For a complete list of my activities, please see my CV.

        <h2 class="engagement-section-heading">Teaching and Mentorship</h2>

        <div class="outreach-split">
          <div class="outreach-text">
            <h3>Classroom Teaching</h3>

            <p>I have taught biology and geology courses at both the George Washington University and the University of Michigan, Ann Arbor, in roles ranging from undergraduate teaching assistant to instructor of record.</p>

            <p>My courses often include project-based assignments that use publicly available resources, such as ArcGIS, NCBI, iNaturalist, the IUCN Red List, and the Paleobiology Database, to help students engage directly with the natural world. These experiences have allowed me to work with students from diverse backgrounds and help them explore how geology and biology have shaped their lives and experiences.</p>
          </div>

          <div class="outreach-carousel-wrap">
            {{< carousel pattern="classroom-*" alt="Classroom teaching photo" >}}
          </div>
        </div>

        <div class="outreach-split">
          <div class="outreach-carousel-wrap">
            {{< carousel pattern="mentoring-*" alt="Student mentorship photo" >}}
          </div>

          <div class="outreach-text">
            <h3>Mentorship</h3>

            <p>Mentorship is another important part of my teaching. At the University of Michigan, I have worked with several students through the Undergraduate Research Opportunity Program (UROP).</p>

            <p>These projects have ranged from training machine-learning models to extract information from historical texts and documenting the depositional environments of fossil localities across the Mediterranean Basin to redescribing Miocene fossil fishes from Indonesia.</p>
          </div>
        </div>

        <div class="outreach-split">
          <div class="outreach-text">
            <h3>Field-Based Teaching</h3>

            <p>Although my research is largely museum-based and analytical, I recognize that without the contributions of field scientists, there would be no specimens to study.</p>

            <p>Field-based courses are an important way for students to engage directly with the natural sciences, and much of my recent teaching has incorporated fieldwork in both geology and biology.</p>
          </div>

          <div class="outreach-carousel-wrap">
            {{< carousel pattern="field-*" alt="Field-based teaching photo" >}}
          </div>
        </div>

        <h2 class="engagement-section-heading">Public Engagement and Museum Exhibits</h2>

        <div class="outreach-split">
          <div class="outreach-carousel-wrap">
            {{< carousel pattern="outreach-*" alt="Museum and public outreach photo" >}}
          </div>

          <div class="outreach-text">
            <h3>Public Outreach</h3>

            <p>Since my undergraduate years, I have participated in a wide range of museum and public outreach activities. These experiences have included serving as an Evolution Ambassador at the Smithsonian and completing fellowships in science communication and museum studies.</p>

            <p>At the University of Michigan, Ann Arbor, I have also developed several new museum activities centered on fossils, biodiversity, and evolution.</p>
          </div>
        </div>

        <div class="outreach-split">
          <div class="outreach-text">
            <h3>Museum Exhibit Development</h3>

            <p>I have also contributed to the development of museum exhibits at the University of Michigan, the University of Florida, and the American Museum of Natural History.</p>

            <p>These projects have ranged from creating digital media and research-focused displays to developing exhibitions that celebrate the histories, accomplishments, and people of these institutions.</p>
          </div>

          <div class="outreach-carousel-wrap">
            {{< carousel pattern="exhibits-*" alt="Museum exhibit development photo" >}}
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
