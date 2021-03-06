# mkdocs-simple-plugin

![mkdocs-simple-plugin](https://github.com/athackst/mkdocs-simple-plugin/raw/main/media/mkdocs-simple-plugin.png)

[![Test](https://github.com/athackst/mkdocs-simple-plugin/workflows/Test/badge.svg)](https://github.com/athackst/mkdocs-simple-plugin) [![Docs](https://github.com/athackst/mkdocs-simple-plugin/workflows/Docs/badge.svg)](https://athackst.github.io/mkdocs-simple-plugin) [![Docker](https://img.shields.io/docker/pulls/athackst/mkdocs-simple-plugin?color=blue)](https://hub.docker.com/r/athackst/mkdocs-simple-plugin) [![pypi](https://img.shields.io/pypi/dm/mkdocs-simple-plugin?label=pypi%20downloads&color=blue)](https://pypi.org/project/mkdocs-simple-plugin/) [![Github Action](https://img.shields.io/badge/github%20action-download-blue)](https://github.com/marketplace/actions/mkdocs-simple-action)

| [Code](https://github.com/athackst/mkdocs-simple-plugin) | [Docs](https://athackst.github.io/mkdocs-simple-plugin)  | [PyPi](https://pypi.org/project/mkdocs-simple-plugin/) | [Docker](https://hub.docker.com/r/athackst/mkdocs-simple-plugin) | [GitHub Action](https://github.com/marketplace/actions/mkdocs-simple-action) |

This plugin enables you to build a documentation site from markdown interspersed within your code using [mkdocs](https://www.mkdocs.org/).  It is designed for the way developers commonly write documentation in their code -- with simple markdown files and/or markdown comment blocks in the code.

## About

You may be wondering why you would want to generate a static site for your project, without doing the typical "wiki" thing of consolidating all documentation within a single `docs` folder or using a single `README` file.

* **My repository is too big for a single documentation source.**

    Sometimes it isn't feasible to consolidate all documentation within an upper level `docs` directory.  This is often the case with medium/large repositories.  In general, if your codebase is too large to fit well within a single `include` directory, your codebase is probably also too large for documentation to fit within a single `docs` directory.  

    Since it's typically easier to keep documentation up to date when it lives as close to the code as possible, it is better to create multiple sources for documentation.

* **My repository is too simple for advanced documentation.**

    If your codebase is _very very_ large, something like the [monorepo plugin](https://github.com/spotify/mkdocs-monorepo-plugin) might better fit your needs.

    For most other medium+ repositories that have grown over time, you probably have scattered documentation throughout your code.  By combining all of that documentation while keeping folder structure, you can better surface and collaborate with others. And, let's face it.  That documentation is probably all in markdown since Github renders it nicely.

* **I want a pretty documentation site without the hassle.**

    Finally, you may be interested in this plugin if you have a desire for stylized documentation, but don't want to invest the time/energy in replicating information you already have in your README.md files or in block comments in your code, and you want to keep them where they are (thank you very much).

See [mkdocs-simple-plugin](http://athackst.github.io/mkdocs-simple-plugin) for usage.

## Contributing

See the [contributing guide](http://athackst.github.io/mkdocs-simple-plugin/CONTRIBUTING)

## License

This software is licensed under [Apache 2.0](https://github.com/athackst/mkdocs-simple-plugin/blob/master/LICENSE)
