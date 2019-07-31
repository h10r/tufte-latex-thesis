# tufte-latex-thesis

This is a PhD thesis template based on [Tiff](ttseng/tufte-latex-mit)'s version of the [MIT's LaTeX thesis template](http://web.mit.edu/thesis/tex/) and the [Tufte-LaTeX] (https://tufte-latex.github.io/tufte-latex/) template. It supports margin figures! Great for small or narrow figures that would otherwise take a lot of space from the main body of text. It also supports bilingual abstracts, ideal for thesis of universities that require abstracts in both English and the local language.

Main differences between this version and [Tiff](ttseng/tufte-latex-mit)'s:
- The first page of each chapter shows the chapter number in a very big font above the title, similar to the [classicthesis template](https://bitbucket.org/amiede/classicthesis/wiki/Home).
- Section titles are preceded by the section number.
- Section titles have a bigger font and are not italized.
- It supports _Parts_ (e.g. Part I, Part II), which also appear in the table of contents.
- The table of content shows the chapter and section numbers next to their titles. 
- The cover is very simple and doesn't show any university-specific information (for MIT's version, check [Tiff](ttseng/tufte-latex-mit)'s template).
- The pages before the "main matter" (the main content of the thesis after the cover, table of contents, acknowledgments, etc) are numbered with arabic characters (i, ii, iii). The first page of the "main matter" uses numbers starting from 1. 
- It adds the ```trabstractpage``` command for adding a translated abstract, ideal for universities that require an additional abstract in the local language.

Check out main.pdf for a preview of what it looks like.

Tweaks to [Tiff](ttseng/tufte-latex-mit)'s template made by Carla [@carlagriggio](https://twitter.com/carlagriggio).
