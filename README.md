# DrWhyTemplate
pkgdown template for MI2 DataLab projects related to DrWhy.AI universe

[Example pkgdown site with up-to-date MI2 template](https://modeloriented.github.io/DALEX/)

## Instructions

### Installation

This template is up to date with `v1.4.1` of the [`pkgdown`](https://github.com/r-lib/pkgdown) package.

```
# install.packages("devtools")
devtools::install_github("r-lib/pkgdown")
devtools::install_github("ModelOriented/DrWhyTemplate")
```

### Usage

To use DrWhyTemplate, add `_pkgdown.yml` file to your repository. 
This file should have the following content:

```
template:
  package: DrWhyTemplate
  default_assets: false
```

#### Creating site

Run pkgdown from the package directory:
```
pkgdown::build_site()
```
This will generate a `docs/` directory with a website for your package.


#### Publishing site 

- navigate to **Settings** of your GitHub repository,

- in **GitHub Pages** section choose **master branch /docs folder** as your **Source**

- Save

Site should be published: `<user/organization>.github.io/<repistory name>`

### Template

Inspired by [tidytemplate](https://github.com/tidyverse/tidytemplate/).
