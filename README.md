# How to create a reproducible word document (.docx) in R markdown with APA formatting.

An example of how to prepare an APA style word document (.docx) using R markdown.


``` YAML

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

The bibliography is a bib file, created using [Zotero](https://www.zotero.org/) and (Better BibTeX for Zotero)[https://github.com/retorquere/zotero-better-bibtex.git]. This hold all of the information we need to create in-text citations and the references section at the end of the document.

CSL is a (Citation Styles Language)[github.com/citation-style-language/styles] file that organises in the bibliographic information into APA formatting. Many other styles are available if needed.

The reference document is the template used to produce the APA formatting. This is a word document that was made in R markdown and then edited to create the desired appearance. 
