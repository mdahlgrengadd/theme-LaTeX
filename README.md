# GitBook LaTeX theme

This Gitbook theme uses [Typeset](https://github.com/bramstein/typeset) as an implementation of the Knuth and Plass line breaking algorithm. Uses [Hypher](https://github.com/bramstein/hypher) for hyphenation.

![Image](https://raw.github.com/mdahlgrengadd/theme-LaTeX/master/screenshot.png)

# USAGE

You might have to add the following to website.css in your book.

```css
.book.font-size-0 .book-body .page-inner section {
    font-size: inherit !important;
}

.book.font-family-0 {
    font-family: inherit !important;
}
````

# TODO
- Fix broken support for images
- Fix so that different fonts & sizes work
- Fix mobile screens support
- Fix so that ebooks & pdf's uses same rendering as html

# Credits
Thanks to Bram Stein who is the person behind all the typesetting stuff.
And thanks to the Gitbook team for their wonderful work.
