This repository contains:

* decls.tex: the basic LaTeX macros that I use in all my papers
* paper.tex: a sample LaTeX file for the paper itself
* slides.tex: a similar sample file for making beamer slides
* all.bib: my master BibTeX database

I generally copy decls.tex into each new LaTeX project (so that future
updates to it don't break old projects).  But I symlink all.bib in
each new project to a copy checked out of this repository (and
periodically committed), so that when I add new references I only have
to do it once and then all projects can see them.
