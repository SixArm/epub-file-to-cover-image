# epub file to cover image

Input a book as an epub file; output the book cover image.

Syntax:

```sh
epub-file-to-cover-image <file>
```

Example:

```sh
epub-file-to-cover-image book.epub
```

The output file is named cover.jpg.

This script is deliberately simple:

- The epub file must use a typical zip format.

- The epub file must contain './images/cover.jpg'

If your needs are different, then adjust as you wish.
