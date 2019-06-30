# How to create a reproducible word document (.docx) in R markdown with APA formatting

An example of how to prepare an APA style word document (.docx) using R markdown


``` YAML

bibliography: example.bib
csl: apa.csl
output:
  word_document:
    fig_caption: yes
    reference_docx: apa_style.docx

```

The bibliography is a bib file, created using <a href="https://www.zotero.org/">Zotero</a> and <a href="https://github.com/retorquere/zotero-better-bibtex">Better BibTeX for Zotero</a>. This hold all of the information we need to create in-text citations and the references section at the end of the document.

CSL is a  <a href="https://github.com/citation-style-language/styles">Citation Styles Language</a> file that organises in the bibliographic information into APA formatting. Many other styles are available if needed.

The reference document is the template used to produce the APA formatting. This is a word document that was made in R markdown and then edited to create the desired appearance.
