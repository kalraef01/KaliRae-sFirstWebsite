project:
  type: website
  output-dir: docs

website:
  title: "Kali Rae's BIOL 806 Website"
  navbar:
    left:
      - href: index.qmd
        text: Home
      - projects.qmd
    tools:
      - icon: github
        href: https://github.com/kalraef01/KaliRae-sFirstWebsite
  page-footer:
    right: "Built with [Quarto](https://quarto.org/)"
    left: "&copy; Copyright 2026, Kali Rae"

format:
  html:
    theme: cerulean
    toc: true

editor: source


