
> [!NOTE] Explanation
> This file contains some snippets from dataview plugin that you can use in various parts of the system. It is here for reference. 


# 1. Creating Citations from your ontologies

Template for pulling all citations from the "1️⃣ Primary Sources" folder that I reference in this note. For example if I like [[Connell 1964]] it will show up in the table below. 

```dataview
TABLE DOI FROM outgoing([[]]) AND "1️⃣ Primary Sources"
```
If you only want the DOI, use this snippet:

```dataview
TABLE WITHOUT ID DOI FROM outgoing([[]]) AND "1️⃣ Primary Sources"
```
This allows you to copy paste a list of referenced DOIs. 

Paste your DOI list to [Bibtex](https://www.bibtex.com/c/doi-to-bibtex-converter/)  to generate a list of citations in the correct format. 


