---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-06-27
type: landing

sections:
  - block: resume-biography-3
    content:
      # This pulls your name, photo, role, organization, and bio from content/authors/me/_index.md
      username: me
      text: ''
      # Remove the CV button for now
      button:
        text: ''
        url: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the original gradient mesh background
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing
      name:
        size: md # Options: xs, sm, md, lg, xl

      # Avatar customization
      avatar:
        size: large # Options: small, medium, large, xl, xxl
        shape: square # Options: circle, square, rounded
---
