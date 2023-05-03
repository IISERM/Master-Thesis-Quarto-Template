# Master Thesis

This assumes you know what Quarto is, and you have set it up. Otherwise, see [TheWiki](https://iiserm.github.io/thewiki/thesis-writing#quarto).

1. Download the entire repository by clicking [here](https://github.com/IISERM/Master-Thesis-Quarto-Template/archive/refs/heads/main.zip)
2. Extract the zip file you just downloaded.
3. You **must** to do the following _before_ you start writing.
   - [ ] Fill the correct `title` in `_quarto.yml`.
   - [ ] Fill the correct `author` in `_quarto.yml`.
   - [ ] Fill the correct `date` in `_quarto.yml`. This is the submission date.
   - [ ] Fill the correct `date-title` in `_quarto.yml`. It must be in the format "May 2023".
   - [ ] Fill the correct `regno` in `_quarto.yml`.
   - [ ] Fill the correct `supervisor` in `_quarto.yml`.
   - [ ] Fill the correct `TC1`, `TC2` and `TC3` in `_quarto.yml`.
   - [ ] Create your `references.bib` file, either manually or by zotero. See [TheWiki](https://iiserm.github.io/thewiki/thesis-writing#citations)
4. Now, start writing your chapters.
   1. Write the introduction in `intro.qmd`.
   2. Write chapter x in `chapterx.qmd`. You don't _need_ to name it like that, but it is easier. Create new files as necessary.
   3. Insert the file name into `chapters` in `_quarto.yml`.
   4. Put images in the `images` folder
   5. Write appendix x in `appendixx.qmd` files.
   6. Insert the file name into `appendices` in `_quarto.yml`.
5. Every time you have written a chunk of text, or you just want to procrastinate, run `quarto render`, or if you are using VS-Code, use `Ctrl-Shift-K`, to render your master's thesis.
6. Write your acknowledgements in `acknowledgements.txt`.
7. Write your abstract in `index.qmd`. Do not write anything else in that file.
8. Repeat steps 4 to 7 again and again up until the due-date, or your guide is happy, whichever is later.

The template also creates a html version of your thesis. Simply copy the generated `_book` folder onto your web host, or host it on github pages. This is left as an exercise for the reader.
