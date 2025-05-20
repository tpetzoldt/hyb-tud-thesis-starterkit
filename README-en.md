[ 🇩🇪 Deutsch (German)](/README.md)

# hyb-tud-thesis-starterkit


**Welcome to the hyb-tud-thesis-starterkit!**

## For the impatient Microsoft Word user

* Download the file [template-praktikumsbericht-einfach.docx](https://github.com/tpetzoldt/hyb-tud-thesis-starterkit/raw/refs/heads/main/word/template-praktikumsbericht-einfach.docx) and start writing.


## Why this repository?

* **Quick start:** Save time and concentrate on the content of your work instead of struggling with formatting.
* **Consistency:** Ensure a uniform design of your work.
* **Flexibility:** The templates can be adapted to your individual needs.
* **Open Source:** Share your improvements with the community and benefit from the contributions of others.

This repository offers a collection of templates for bachelor, master and internship theses, by example of standards of hydrobiology at the TU Dresden. The templates can of course also be used for other degree programs. Ask your supervisor about the applicable rules.

The templates are based on the corporate design of TU Dresden (in Word format) and the LaTeX package 'TUD-Script' by Falk Hanisch (https://www.ctan.org/pkg/tudscr), in order to maintain a consistent style.

## Which word processing tool should I use?


There are various word processing programs to choose from for your student research projects. Here are some recommendations to help you decide:

### Microsoft Word

If you are familiar with Microsoft Word, you can simply download the corresponding Word file and edit it. Word is widely used and offers an intuitive user interface.

### LaTeX and Quarto for professional layout

For a more professional layout and additional functionality, LaTeX and Quarto are excellent options. 
Both systems allow precise control over the appearance of your document.

**Quarto is the most modern system**

* Easy to learn: Compared to LaTeX, Quarto is easier and faster to learn.
* Reproducible and portable: Your documents can be reproduced and shared on different systems.
* Integration of R and Python graphics and tables: you can embed R and Python code directly into your document to create graphics and tables dynamically. This is especially useful when writing data-intensive work.

**Important tip**

Be sure to discuss your choice of text program with your supervisor. They can make specific recommendations and support you with your chosen tool.


## Which format to use?

* **Word template:** 
    * A pragmatic outline, based on the Word template of the TU Dresden CD (Corporate Design).
* **LaTeX templates:** 
    * Configured LaTeX templates, for seminar papers and theses 
    * `template-article-basic.tex` contains a cover page that is intentionally kept simple.
    * `template-tud-script.tex` is based on the tud-script package and contains all the essential elements of a scientific paper.
* **Quarto templates:**
    * The template `template-quarto-basic` is particularly easy to use and only requires R and Rstudio. It is a good place to start writing. A cover page can be added later.
    * The template `template-quarto-koma-script.qmd` is based on the article template `scrartcl` from the KOMA-Script package.
    * The template `template-quarto-tud-script.qmd` is based on the tud-script LaTeX template, but is easier to use and allows the embedding of R, Python and Julia code. It contains all the important elements of a scientific paper (cover page, table of contents, list of figures, bibliography).
    

## Installation of the LaTeX and Quarto templates

### Step 1: Download the files.

* Download the entire repository or part of it as a ZIP file using the **Code** button.
* Experts can clone the repository with `git`.

### Step 2: Install the TUD script package

* Not required for the Word version and the Quarto Basic version.
* Required for the Latex versions and the Markdown versions except Quarto-Basic:
    * First install a Tex environment, e.g. Texlive, Miktex or tinytex
    * Use the package manager of TexLive or Miktex and install the package **tudscr**
    * The documentation can be found at: https://github.com/tud-cd/tudscr
    
**Important:** 

Please download always the complete folder, not only the `template-*` file.

* `tudcolors.sty`: Color schemes of the TU Dresden
* `apa.csl`: Bibliography style according to the American Psychological Association (APA)
* `references.bib` is an example of a literature database in BibTex format. 
It can be created by hand or exported from a literature program, e.g. [Zotero](https://www.zotero.org/).
* The files `pdf-plot.pdf` and `mountains.jpg` are example graphics. 
Your own graphics can also be organized in subdirectories.

Translated with DeepL.com (free version)    
    
### Step 4: Open the template file

* Make a copy of the template file (recognizable by “template-” in the name)
* Open the file in Word, TexStudio or RStudio
* Read the notes in the template
* Start writing

## Contribute!

* Share your experience and send comments and suggestions for improvement to the package maintainer
* Create a fork of the repository, modify it according to your needs and report suggestions for improvement, e.g. as a pull request


Good luck!

