# BatSync - documentation

This repository is for the documentation site for BatSync

It's currently at [https://batsync.codeberg.page](https://batsync.codeberg.page)

## How to update

Content on the `main` branch here is auto published when it updates.

`index.html` is currently _not_ automatically re-rendered

[Install Quarto](https://quarto.org/docs/get-started/) if you don't already have it

`quarto render index.qmd` will regenerate the overview presentation

Then `git add index.html` (or `git add -p` to review the changes, commit and push. The updates might take a few minutes to appear.

## TODO

* Import references into references.bib
* Decide on repository hosting