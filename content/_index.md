---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "0rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: Ian Porada
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Porada_CV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-lines.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0rem', '20px', '2rem', '20px']
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
        padding: ['4rem', '20px', '4rem', '20px']
  - block: markdown
    content:
      title: Contact
      text: "ian.porada (at) mail.mcgill.ca <br> Mountain View, California"
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: [0, '20px', 0, '20px']
---
