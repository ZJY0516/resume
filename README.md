My Resume
============================

Introduction
------------

This resume is modified from [liweitianux/resume](https://github.com/liweitianux/resume), thanks!

I haven't translated my resume into English yet, so `resume-en.tex` is the same as the original.

Usage
-----
* Linux

  1. Install XeLaTeX, latexmk, GNU Make, and GhostScript packages;
  2. Install the [required fonts](#required-fonts);
  3. Replace `resume-zh.tex` and `resume-en.tex` with your versions;
  4. Compile to PDFs with a simple `make` :-)

* Windows

  1. Install [MiKTeX](https://miktex.org/);
  2. Install the [required fonts](#required-fonts);
  3. Replace `resume-zh.tex` and `resume-en.tex` with your versions;
  4. Open `resume-*.tex` in TeXWorks, choose `XeLaTeX` to compile,
     and confirm the prompts to install the missing packages along
     the run.


Required Fonts
--------------

* [IBM Plex](https://github.com/IBM/plex)

* [Noto Serif CJK](https://github.com/notofonts/noto-cjk)

* [Font Awesome 5](https://fontawesome.com/)

On Debian Linux, simply do `apt install fonts-ibm-plex fonts-noto-cjk texlive-fonts-extra`. `texlive-fonts-extra` includes Font Awesome 5.

Of course, you can use the fonts you prefer by modifying the template directly.

However, you may need to tweak the
[column width in the template](resume.cls#L158)
accordingly.
