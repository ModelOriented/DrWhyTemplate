# DrWhyTemplate
pkgdown template for MI2 DataLab projects related to DrWhy.AI universe

[Example pkgdown site with up-to-date MI2 template](https://mi2-warsaw.github.io/auditor/index.html)

## Instructions

### Installation

Make sure you have installed the current versions of the [`pkgdown`](https://github.com/hadley/pkgdown) and `DrWhyTemplate` packages. 

```
# install.packages("devtools")
devtools::install_github("hadley/pkgdown")
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
