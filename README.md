# Concise note on Plant Breeding and Genetics

[![bookdown](https://github.com/DeependraD/concise-plbgen/actions/workflows/bookdown.yaml/badge.svg)](https://github.com/DeependraD/concise-plbgen/actions/workflows/bookdown.yaml)

## Automated deployment with github actions

- A pre-requisite to bookdown builds is use of renv in the project. For that,
  - Install renv (if not already)
  - run `renv::init()`
  - run `renv::activate()`

1. `usethis::use_github_action(name = "check-standard")` # this is for use with packages only?
2. `usethis::use_github_action(name = "bookdown"")`
3. `usethis::use_github_actions_badge("Build-Book")`
