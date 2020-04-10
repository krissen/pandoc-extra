# pandoc-extra
Uploads of some extra [pandoc](https://pandoc.org/) material which might be of interest to others.

## Microsoft Word template for numbered sections
[numbered-sections.docx](https://github.com/krissen/pandoc-extra/blob/master/templates/numbered-sections.docx), a docx-template for numbered sections. Created by 1) making a docx-file through pandoc and 2) numbering sections manually. Can now be used as a reference docx as follows:
```
pandoc INPUT --reference-doc=numbered-sections.docx -o OUTPUT.docx
```
Headings for levels 1-3 are numbered. E.g. section, subsection, and subsubsection. Headings on level 4 and lower are not numbered.
