# web
 #http://localhost:3158/index.html
# project:
  type: website output-dir: ../docs

website:
  title: "VDH-Project"
  navbar:
    left:
      - href: index.qmd
        text: Home
      - about.qmd

format:
  html:
    theme: cosmo
    css: styles.css
    toc: true

editor: visual
