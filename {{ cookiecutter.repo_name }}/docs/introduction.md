# Introduction

Introduction to `{{ cookiecutter.project_name }}`.

{{ cookiecutter.description }}

## Project structure

The directory structure of this project looks like this: 

```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- Where the mdBook documentation will stay
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
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── {{cookiecutter.project_slug}}.Rproj <- r-project environment variables
│
├── book.toml          <- Settings for mdBook
```

## Include files

You can include files by adding a code block and writing

````
```
\{{"{{"}}#include ../{{cookiecutter.project_slug}}.Rproj{{"}}"}}
```
````

Written by {{ cookiecutter.full_name }}.

