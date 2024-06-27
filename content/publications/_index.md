---
title: Publications
cms_exclude: true
id: publications

text: "Some text here."

sections:
  - block: markdown
    content:
      title: Contact
      text: "ian.porada (at) mail.mcgill.ca <br> 6666 St-Urbain, #200 Montreal, QC, H2S 3H1"
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['4rem', '20px', '2rem', '20px']
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

# View.
view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
  

sections:
  - block: resume-biography-3
    content:
      
---
