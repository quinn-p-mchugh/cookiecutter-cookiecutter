# Cookiecutter Cookiecutter

A [cookiecutter](https://github.com/cookiecutter/cookiecutter) template for creating other kinds of cookiecutter templates.

## Features

- Create flexible templates for any language or framework using [cookiecutter](https://github.com/cookiecutter/cookiecutter), which utilizes the [Jinja2](https://jinja.palletsprojects.com/en/3.1.x/) templating engine.
- Includes…
  - Templates for README, code of conduct, and license
  - Automatic updating of templates using [cruft](https://github.com/cruft/cruft?tab=readme-ov-file#automating-updates-with-github-actions)

## Getting Started

### Prerequisites

This template is meant to be used with [cruft](https://github.com/cruft/cruft), a fork of cookiecutter. With cruft, any updates made to this top-level template can be easily propagates to templates created with it.

To install cruft, please see [installation instructions](https://github.com/cruft/cruft?tab=readme-ov-file#installation).

### Usage

With cruft installed, run the following command to generate a new template:

```
cruft create https://github.com/quinn-p-mchugh/cookiecutter-cookiecutter
```

## License

This project is licensed under the **GPL-3.0 license** - see the [LICENSE.md](LICENSE.md) for details.

