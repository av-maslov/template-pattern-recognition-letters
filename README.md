## Trying to find the right template for "Pattern Recognition Letters" journal submission

## Open access published article example 

- https://www.sciencedirect.com/science/article/pii/S016786552300020X 

[File](ExampleOfPublishedArticle)

### Summary of findings 

- [V1](./V1/): - just `\documentclass{elsarticle} \usepackage{prletters}` 
- [V2](./V2): [elsarticle-template.zip](https://www.elsevier.com/__data/assets/file/0007/56842/elsarticle-template.zip)
- [V3](./V3): [els-cas-template.zip](https://mirrors.ctan.org/macros/latex/contrib/els-cas-templates.zip)



- **V2 and V3 do not contain any reference to `prletters.sty`. V2 and V3 contain several options each for tex file.**
- **Where to find right LaTeX template (with right imports and settings)?**

### Steps

**1)** Journal web page [Pattern Recognition Letters](https://www.sciencedirect.com/journal/pattern-recognition-letters) refers to **2)** [Guide for authors](https://www.elsevier.com/journals/pattern-recognition-letters/0167-8655/guide-for-authors) which refers to ["The latex template can be found"](https://www.elsevier.com/__data/promis_misc/PRLetters-28012014.sty.zip) which refers to the file `PRLetters-28012014.sty.zip` containing `prletters.sty` file.

Further instructions:

> **The latex template can be found:** https://www.elsevier.com/__data/promis_misc/PRLetters-28012014.sty.zip 
>
> Please note that papers can have 7 pages (plus one page after revision).
> These limits include all materials e.g. narrative, figures, tables,
> references, etc.

> LaTeX: **The article should be written using Elsevier's document class 'elsarticle' and prletters.sty files provided.** Please do not edit them.

- [V1/main.tex](V1/main.tex) file corresponds to these instructions. Corresponding [PDF](./V1/main.pdf) file.

Further instructions:

> **Detailed instructions for LaTeX preparation can be obtained from the Quickguide:**
> https://www.elsevier.com/author-schemas/preparing-documents-with-latex or
> from the Comprehensive TeX Archive Network (CTAN): see below, in the
> directory /tex-archive/macros/latex/contrib/elsarticle. It consists of the
> files: elsarticle.cls, complete user documentation for the class file,
> bibliographic style files in various styles, and template files for a quick
> start.guidelines for users of elsart, a template file for quick start.
> 
> CTAN is an archive with up-to-date copies of all the public-domain versions
> of TeX, LaTeX, Metafont and ancillary programs, which is made available via a
> mirrored network of FTP servers. You can enter the CTAN archive via a web
> interface in the UK (http://www.tex.ac.uk), in the USA (http://www.ctan.org),
> or in Germany (http://www.dante.de/software/ctan) (page in German). You can
> search for a package on CTAN via http://www.ucc.ie/cgi-bin/ctan/. You can
> also enter the archive via FTP at ftp://ftp.tex.ac.uk, at ftp://ftp.dante.de,
> at ftp://ctan.tug.org, or at one of the many mirror servers; see for a list
> the UK or USA CTAN web pages. When a CTAN server does not respond, please try
> another one. Note that CTAN is not related to Elsevier, and that Elsevier's
> Customer support cannot accept complaints or answer questions about the
> availability of any CTAN server. 


Now the reference is to **3)** [www.elsevier.com: LaTeX instructions](https://www.elsevier.com/author-schemas/preparing-documents-with-latex) which contains the link to [elsarticle-template.zip](https://www.elsevier.com/__data/assets/file/0007/56842/elsarticle-template.zip) 
> You can download a set of files containing a template LaTeX manuscript, using
> the elsarticle class, plus associated BibTeX style files
> [here](https://www.elsevier.com/__data/assets/file/0007/56842/elsarticle-template.zip).
> Although elsarticle.cls supports most journal styles, it is not possible to
> match the
> journal's layout exactly 

- Template is uploaded into [V2/](./V2/elsarticle) folder.

**Also, source 3) says**

> For more complex articles two additional class files and templates are available, single-column (cas-sc.cls) and double-column (cas-dc.cls). 
> These can be downloaded from [CTAN](https://www.ctan.org/pkg/els-cas-templates/) ([els-cas-template.zip](https://mirrors.ctan.org/macros/latex/contrib/els-cas-templates.zip)). These class files are documented [here](https://support.stmdocs.in/wiki/index.php?title=Elsarticle.cls).
- This version is uploaded into [V3](./V3/) folder

Source 3) contains two options for template and source 1 & 2) refer to the simplest option.
