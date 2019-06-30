# apa-word-docx-in-rmarkdown

An example of how to prepare an APA style word document (.docx) using R markdown.

```

bibliography: example.bib
csl: apa.csl
editor_options:
  chunk_output_type: console
output:
  word_document:
    fig_caption: yes
    highlight: tango
    reference_docx: apa_style.docx

```
