# NYU GSAS PhD thesis template

A PhD dissertation/thesis template satisfying the [requirements](https://gsas.nyu.edu/content/dam/nyu-as/gsas/documents/dissertationsubmissionrelated/Doctoral%20Dissertation%20Formatting%20Requirements%2010-09-15.pdf) of NYU's Graduate School of Arts and Sciences (as of 2019).

This is based on a template by José Koiller (2007-2008).

How to use:
- The `thesis.tex` file is the main file for the thesis.
  `abstractpage.tex` is to create a stand-alone abstract page (required for the preliminary submission).
- In both, modify the macros under "Thesis Metadata" with your name, thesis title, etc.
- Add your own macros and additional latex packages to `defs.tex`.
- Replace the content under "Body of Thesis" with your thesis.
  I'd recommend using a file per chapter and using `\input` commands to include them in `thesis.tex`.

I hope this helps! Feedback (via issues) and updates (via pull requests) welcome.
