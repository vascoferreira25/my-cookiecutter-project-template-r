# {{ cookiecutter.project_name }}

{{ cookiecutter.description }}

## Project Organization

```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- Where the build of the docs will stay
├── docs-markdown      <- Where the mdBook documentation will stay
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── {{cookiecutter.project_slug}}.Rproj <- r-project environment variables
│
├── book.toml          <- Settings for mdBook
```

## Open the project

Open the project by double clicking on the
`{{cookiecutter.project_slug}}.Rproj` file.

## Build the docs

```
mdbook build
```

## Serve the docs

```
mdbook serve
```

## Clean the build

```
mdbook clean
```
