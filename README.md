# Quarto clean inspired theme for TUM

A minimalist and elegant presentation theme for Quarto Reveal.js, inspired by
[Quarto clean](https://github.com/grantmcdermott/quarto-revealjs-clean).

An example of how the template would look like:

![](clean-title.png "live demo")

## Use

Depending on your use case, here are some [Quarto CLI](https://quarto.org/)
commands to get started.

If you would like to add the **tum** theme to an existing directory:

```bash
quarto install extension pratikvn/quarto-revealjs-tum
```

Alternatively, you can use a
[Quarto template](https://quarto.org/docs/extensions/starter-templates.html)
that bundles the **tum** theme plus a .qmd starter document. This is a better
option if you are starting a new project from scratch, since it will automatically
create a new directory with all of the necessary scaffolding in one go. We provide
two template options.

- Bare bones template

```bash
quarto use template pratikvn/quarto-revealjs-tum
```

## Fonts

TUM recommends the [TUM Neue Helvetica font](http://portal.mytum.de/corporatedesign). If you wish, you can set the `mainfont` and `sansfont` with the fonts that you would like to use as shown the [Quarto documentation](https://quarto.org/docs/output-formats/html-themes.html#basic-options)

## Slide overview

You can also add a slide overview using the `.sectionhead` class like so:  

``` markdown
::: {.sectionhead}
[Outline]{style="opacity:0.25"} Intro [Results Summary]{style="opacity:0.25"}
:::
```

This produces an overview above the slide as shown below

![](section-head.png "section head")
