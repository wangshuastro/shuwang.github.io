---
# Leave the homepage title empty to use the site title
title: "Shu Wang's Homepage"
date: 2024-06-24
type: landing

design:
  # Default section spacing
  spacing: "2rem"
  background:
    # Choose a color such as from https://html-color-codes.info
    color: 'navy'
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true


sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Check out my CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  

---
