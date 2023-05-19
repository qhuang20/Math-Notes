# Notes
`Templates` contains all the latex template files.
`LeTeX-snippets` has all the relevant files when writing Letax in VScode.
`Exercise` is the folder for the solution to the textbook exercises.

### Adding chapters to an existing book
Click the book and add `les_xx.tex` to the folder, then open `master.tex` and add `\input{les_xx.tex}` to the table of contents.

### Adding a new book
Copy the folder `Notes/Templates/book_temp` and rename `book_temp` with the title. Or use your own template. (Also feel free to add new templates to the `Templates` folder)

# Writing Letax in VScode
1. Download "LaTeX" and "LeTeX Workshop" extensions, and configure them according to `LeTeX/settings.json`.
2. Open `Application Support/Code/User/snippets/latex.json`(Mac) `AppData\Roaming\Code\User\snippets\latex.json`(Windows) and add snippets to the files. My `latex.json` file is in `LeTeX` folder.
3. (Optional) If you want to replace the writing with latex code immediately after typing, search and download the "HyperSnips for Math" extension. Adding snippets to `Application Support/Code/User/hsnips/latex.hsnips`(Mac) `AppData\Roaming\Code\User\hsnips\latex.hsnips`(Windows). My `latex.hsnips` file is in `LeTeX` folder.
