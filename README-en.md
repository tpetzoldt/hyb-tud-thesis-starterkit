<div style="text-align: right;">
[ 🇩🇪 Deutsch (German)](/README.md)
</div>

# hyb-tud-thesis-starterkit


**Welcome to the hyb-tud-thesis-starterkit!

This repository offers a collection of templates for bachelor, master and internship theses, by example of standards of hydrobiology at the TU Dresden. The templates can of course also be used for other degree programs. Ask your supervisor about the applicable rules.

The templates are based on the LaTeX package "TUD-Script"”" by Falk Hanisch (https://github.com/tud-cd/tudscr) to support a consistent style according to the university's corporate design.


## Why this repository?

* **Quick start:** Save time and concentrate on the content of your work instead of struggling with formatting.
** **Consistency:** Ensure a uniform design of your work.
** **Flexibility:** The templates can be adapted to your individual needs.
** **Open Source:** Share your improvements with the community and benefit from the contributions of others.

## Contents

* **Word template:** 
    * A pragmatic style sheet, based on the Word template of the TU Dresden CD (Corporate Design).
* **LaTeX templates:** 
    * Configured LaTeX templates, for seminar papers and theses 
    * `template-article-basic.tex` contains a cover page that is intentionally kept simple.
    * `template-tud-script.tex` is based on the tud-script package and contains all the essential elements of a scientific paper.
**Quarto templates:** 
    * The template `template-quarto-basic` is particularly easy to use and only requires R and Rstudio. It is a good place to start writing. A cover page can be added later.
    * The template `template-quarto-koma-script.qmd` is based on the article template `scrartcl` from the KOMA-Script package.
    * The template `template-quarto-tud-script.qmd` is based on the tud-script LaTeX template, but is easier to use and allows the embedding of R, Python and Julia code. It contains all the important elements of a scientific paper (cover page, table of contents, list of figures, bibliography).

## Installation

### Step 1: Download the files.

* Download the entire repository or part of it as a ZIP file using the **Code** button.
* Expert: clone the repository with `git`.

### Step 2: Install the TUD script package

* Not required for the Word version and the Quarto Basic version.
* Required for the Latex versions and the Markdown versions except Quarto-Basic:
    * First install a Tex environment, e.g. Texlive, Miktex or tinytex
    * Use the package manager of TexLive or Miktex and install the package **tudscr**
    * The documentation can be found at: https://github.com/tud-cd/tudscr
    
### Step 4: Open the template file

* Make a copy of the template file (recognizable by “template-” in the name)
* Open the file in Word, TexStudio or RStudio
* Read the notes in the template
* Start writing

## Contribute!

* Share your experience and send comments and suggestions for improvement to the package maintainer
* Create a fork of the repository, modify it according to your needs and report suggestions for improvement, e.g. as a pull request



Good luck!

