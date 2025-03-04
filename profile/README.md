# Hello there :unicorn:

![Potato](../docs/logo.jpeg)

This is the organisation GitHub for [sudoblark](https://sudoblark.com).

It can get quite busy round here, so here's a rough guide to the repo structure:

## Terraform
- `sudoblark.terraform.module` repos are data-structure and algorithm driven Terraform components, allowing creation of
`n` instances of their respective domain(s) of interest via an extensible, mutable, data structure.
- [sudoblark.terraform.github](https://github.com/sudoblark/sudoblark.terraform.github) is a realisation of the Terraform data-structure and algorithm driven principles,
but rather than as re-usable component, or a grouping of such components to fulfill a use-case, it is a mono-repo
for the management of all of Sudoblark's GitHub.
- [sudoblark.terraform.modularised-demo](https://github.com/sudoblark/sudoblark.terraform.modularised-demo) is a demo of the data-structure and algorithm driven Terraform principles
with a simpler setup than [sudoblark.monsternames.api](https://github.com/sudoblark/sudoblark.monsternames.api).
  - It is also the first port of call for demos of other features, such as CI/CD operational models.

## Python
- [sudoblark.python.core](https://github.com/sudoblark/sudoblark.python.core) is a core
Python library of re-usable components, with extensive - online - documentation to boot, and
is available on PyPI. It forms one anchor of the usage of internal CLI tooling to plug
gaps in CI/CD platform for organisations, and helps decouple core business logic
from any particular platform limitations or tooling.
  - It also shows usage of behave! Within pipelines, and automatic documentation generation.
- [sudoblark.monsternames.api](https://github.com/sudoblark/sudoblark.monsternames.api) is a simple, open source, RESTAPI 
utilising the data-structure and algorithm driven Terraform approach to create a 
RESTAPI available on the web.

## GitHub Actions
- [sudoblark.github-actions.library](https://github.com/sudoblark/sudoblark.github-actions.library) is a template library of re-usable components for usage in GitHub Actions,
see the aforementioned [sudoblark.terraform.modularised-demo](https://github.com/sudoblark/sudoblark.terraform.modularised-demo) for how this may be utilised in a pull pattern
for CI/CD.
