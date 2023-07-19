
# Annual Reviews Quarto Template

## Creating a New Article

To create a new article using this format:

```bash
quarto use template christopherkenny/annual-reviews
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add christopherkenny/annual-reviews
```

Then, add the format to your document options:

```yaml
format:
  annual-reviews-pdf: default
```    

## Options

- `runningtitle`: a short paper title
- `runningauthor`: author names, listed out if less than 4, or First Author et al. if 4 or more.
- `journal-name`: Journal name
- `journal-volume`: Journal volume, default is placeholder AA.
- `journal-year`: Journal year, default is 2023, as this must be a number.
- `doi`: DOI, default is "10.1146/"
- `conflict-of-interest`: Disclosure statement

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

<!-- pdftools::pdf_convert('template.pdf',pages = 1) -->
![[template.qmd](template.qmd)](template_1.png)

