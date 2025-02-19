# Hello there :unicorn:

![Potato](../docs/logo.jpeg)

This is the organisation GitHub for [sudoblark](https://sudoblark.com).

It can get quite busy round here, so here's a rough guide to the repo structure:

- `sudoblark.terraform.module` repos are data-structure and algorithm driven Terraform components, allowing creation of
`n` instances of their respective domain(s) of interest via an extensible, mutable, data structure.
- [sudoblark.monsternames.api](https://github.com/sudoblark/sudoblark.monsternames.api) is a simple, open source, RESTAPI utilising the data-structure
and algorithm driven approach to create a RESTAPI available on the web.
- [sudoblark.terraform.github](https://github.com/sudoblark/sudoblark.terraform.github) is a realisation of the Terraform data-structure and algorithm driven principles,
but rather than as re-usable component, or a grouping of such components to fulfill a use-case, it is a mono-repo
for the management of all of Sudoblark's GitHub.
- [sudoblark.terraform.modularised-demo](https://github.com/sudoblark/sudoblark.terraform.modularised-demo) is a demo of the data-structure and algorithm driven Terraform principles
with a simpler setup than `sudoblark.monsternames.api`.
  - It is also the first port of call for demos of other features, such as CI/CD operational models.
- [sudoblark.github-actions.library](https://github.com/sudoblark/sudoblark.github-actions.library) is a template library of re-usable components for usage in GitHub Actions,
see the aforementioned [sudoblark.terraform.modularised-demo](https://github.com/sudoblark/sudoblark.terraform.modularised-demo) for how this may be utilised in a pull pattern
for CI/CD.