# My Cookiecutter Project Template

A template that I plan to use on my own projects. 
It is adapted from [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/).

## To start a new project, run:

```
cookiecutter https://github.com/vascoferreira25/my-cookiecutter-project-template-r
```

## The resulting directory structure

The directory structure of your new project looks like this: 

```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- Where the Mkdocs documentation will stay
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
├── mkdocs.yml         <- Settings for Mkdocs
```
