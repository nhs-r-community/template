
<!-- README.md is generated from README.Rmd. Please edit that file -->

# template [<img alt="NHS-R Community Logo" src="man/figures/logo.png" align="right" />](https://nhsrcommunity.com/)

<!-- badges: start -->
<!-- badges: end -->

## Set-up

This is a template repository for NHS-R packages. It set’s up a number
of things ready to start developing R-packages.

After creating a new repository from this template make sure to update:

-   Update the title and installation section in Readme.Rmd
-   Remove the Set-up section in Readme.Rmd
-   Update the DESCRIPTION file as relevant
-   Update the [universe](https://github.com/nhs-r-community/universe)
    repository, so your package is included in
    [nhs-r-community.r-universe.dev](https://nhs-r-community.r-universe.dev/ui#builds)

### Actions

This template set’s up the following actions:

-   R-CMD check on PR’s and merges to the main branch
-   [`{lintr}`](https://github.com/jimhester/lintr) on all pushes
-   [`{covr}`](https://github.com/r-lib/covr) code coverage on PR’s
-   [`{pkgdown}`](https://github.com/r-lib/pkgdown) deployment to GitHub
    pages on merges to the main branch

These actions will ensure that your package is building correctly,
passing tests, and will help you stick to the [tidyverse style
guide](https://style.tidyverse.org/).

## Installation

You can install the released version of template from
[GitHub](https://github.com/) with:

``` r
install.packages("remotes")
remotes::install_github("nhs-r-community/[YOUR_REPOSITORY])
```

## Development

As this is using a Readme.Rmd file to generate the Readme.md file you
should enable the git hooks to prevent occidentally checking in
Readme.Rmd without updating Readme.md. Make sure to run
`usethis::use_readme_rmd()` after you checkout this repository.
