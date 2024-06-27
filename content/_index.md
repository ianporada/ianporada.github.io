---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: Ian Porada
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
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
  - block: collection
    content:
      title: Selected Publications
      text: ""
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['4rem', '20px', '2rem', '20px']
  - block: markdown
    content:
      title: Contact
      text: "ian.porada (at) mail.mcgill.ca <br> 6666 St-Urbain, #200 Montreal, QC, H2S 3H1"
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['4rem', '20px', '2rem', '20px']
---
