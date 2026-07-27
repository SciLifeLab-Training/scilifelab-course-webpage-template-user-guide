# SciLifeLab Course Webpage Template User Guide

This repository contains the use guide for the **[SciLifeLab Course Page Template](https://scilifelab-training.github.io/scilifelab-training-template-staging/)**, a Quarto-based template for creating, publishing, and maintaining reusable training materials with GitHub Pages.

## Read the User Guide

The published User Guide is available at:

**[SciLifeLab Course Page Template User Guide](https://scilifelab-training.github.io/scilifelab-course-webpage-template-user-guide/)**

The guide provides step-by-step instructions for:

- setting up the template for a new course;
- customising the course landing page;
- creating and managing course instances;
- previewing and publishing changes;
- preparing training materials for publication, citation, and reuse.

## Course Page Template

The template itself is maintained in a separate repository:

**[SciLifeLab Course Page Template](https://github.com/SciLifeLab-Training/scilifelab-training-template-staging)**

Users of the template should normally start with the published User Guide rather than the files in this repository.

## Working on the User Guide locally

The User Guide is built with [Quarto](https://quarto.org/).

After cloning this repository, open the repository directory and preview the guide with:

```bash
quarto preview
```

To render the complete guide without starting a preview server, run:

```bash
quarto render
```

The rendered site is generated locally and should not be edited directly. Changes to the documentation should be made in the source `.qmd` files.

## Publishing

The User Guide is published through GitHub Pages.

Changes pushed to the `main` branch are automatically rendered and deployed by the GitHub Actions workflow in:

```text
.github/workflows/publish.yml
```

The published website is maintained on the `gh-pages` branch. Do not edit the `gh-pages` branch directly.

## Contributing

Changes and improvements to the User Guide can be made by editing the relevant `.qmd` files in this repository.

Before committing documentation changes, preview the guide locally to check that pages, links, images, and formatting render as expected.

## Licence

Unless otherwise stated, the SciLifeLab Course Page Template User Guide is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) licence.
