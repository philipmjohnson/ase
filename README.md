# ase-spring-2015

To develop this paper:

  1. Download [TexLive 2014](https://www.tug.org/texlive/) for your platform of choice.

  2. Clone this repo.

  3. Type `make` to build the paper. 

Note that .gitignore is set up so that top-level pdf and image files are ignored.  Please place PDFs of paper into the out/ directory, and all image files into the images/ directory so that they can be committed.

The paper is organized into the following files:

  * paper.tex: top-level, contains title and then \\inputs the following .tex files.
  * paper-introduction.tex: the intro section
  * paper-ase-overview.tex: an overview of the ASE technique.
  * paper-experiences.tex: initial experiences. 
  * paper-future.tex: implications for the future of software engineering education.
  * paper.bib: the bibliography.

CFP is [here](http://www.computer.org/web/computingnow/swcfp1).

Author guidelines are [here](http://www.computer.org/web/peer-review/magazines).

Length: "Articles submitted to IEEE Software  should not exceed 4,700 words, including all text, the abstract, keywords, bibliography, biographies, and table text. The word count should include 200 words for each table and figure." 

Use `wc *.tex` to get a rough word count.




