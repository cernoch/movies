Movie Data Set
==============

This is a dataset of **[Movies](http://archive.ics.uci.edu/ml/datasets/Movie)**.
The original data from the [UCI database](http://archive.ics.uci.edu/ml/)
have been cleaned up and converted from HTML to CSV.

- Syntax errors in the original HTML files have been cleaned up. 
- Script for converting HTML files into CSV was added (see file `data/make`).
- Some additional columns (eg. `Ref:`) were omitted from the CSV output as
  they can not be parsed easily by a computer (the HTML files were intact,
  you can continue working on this easily).
- The following list of files should be “ready”:
  - `actors.csv`
  - `casts.csv`
  - `remakes.csv`
  - `studios.csv`
  - `synonyms.csv`
  - `main.html`
  - `people.html`

  
How to contribute
-----------------

Despite the effort, there are many ways this dataset can be enhanced:

- Characterize what type of films the database contains.
  Currently, the description only says
  *over 10000 films including many older, odd, and cult films*,
  which is not a very precise definition...
- Clean up one of these files: `awtypes.html`,
  `locales.html`, `quotes.html` or `sayings.html`.
- Devise a way of making the non-machine-readable columns
  (usually the last one) machine-readable.
- Make the *date* columns machine-readable (lot of noise currently).  
- Check for errors in the data.
