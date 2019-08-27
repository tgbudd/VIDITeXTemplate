# LaTeX template for the NWO VIDI application form 2019

This is a quick and dirty LuaTeX remake of the original Microsoft Word VIDI application form that is available from the [NWO website](https://www.nwo.nl/en/funding/our-funding-instruments/nwo/innovational-research-incentives-scheme/vidi/index.html).
Of course, I provide **no guarantees** that the document fulfils the criteria of NWO, but it looks similar enough. 

It provides automatic word count on the relevant sections.

Note that the final section **Statements by the applicant** is still missing (see the official application form).

To compile the document run:
```
lualatex --enable-write18 VIDI_template.tex
```
