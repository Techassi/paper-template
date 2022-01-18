# paper-template

This is my personal LaTeX template for writing papers. I originally created this template during my studies at HFU. It
is inspired by the ASME Conference Paper template, see [here](https://www.ctan.org/pkg/asmeconf).

## Usage

### Authors

To print a list of authors use:

```latex
\setAuthors{{John Doe, -, john.doe@example.com}, {Jane Doe, -, jane.doe@example.com}, {Catherine Parr, -, catherine.parr@example.com}}
```

![Authors Example](./img/authors_example.jpg)

All provided names will be rendered as a grid table directly under the title (and subtitle).

### Affiliations

```latex
\setAuthors{{John Doe, 1, john.doe@example.com}, {Jane Doe, 2, jane.doe@example.com}}
\setAffiliations{Fantasy University, A Very Real University}
```

![Affiliation Example](./img/affiliation_example.jpg)

All provided universities will be rendered under the grid table of authors with continuous numbering. Providing `-` as
a second argument in the `\setAuthors{}` command will hide the affiliation.