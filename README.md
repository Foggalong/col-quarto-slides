# COL Quarto Slides

Template for using [Quarto](https://quarto.org/) to create 'accessible by default' presentations that involve maths or code. The default applies [Centre for Open Learning](https://col.ed.ac.uk/) branding.

## Rendering Outputs

Slides are formatted as [Quarto Presentations](https://quarto.org/docs/presentations/) that export to [revealjs](https://quarto.org/docs/presentations/revealjs/) format. This means they can be embedded in a website or VLE, presented through [RStudio](https://posit.co/products/open-source/rstudio) or browser, or downloaded as a PDF for portable use.

To render the presentation, either click **Render** in RStudio, or type the following in the terminal:

```sh
quarto render slides-template.qmd --to revealjs
```

## Speaker View

To aid other teachers who might need to deliver these, speaker notes can be included in blocks like the example below.

```markdown
::: {.notes}
Additional notes intended for the teacher that will only appear in speaker view.
:::
```

These notes will appear if the presenter clicks "Speaker View" (keyboard shortcut `s`) within the hamburger menu.

## Licenses

The template files `slides-template.qmd` and `edtheme.scss` are both provided under the [CC0 public domain license](LICENSE). The image `col-logo.png` is a registered trademarks; they are not to be used as part of derived or independent works without the permission of The University of Edinburgh. This does not affect use as part of documents using this stylesheet for the University.
