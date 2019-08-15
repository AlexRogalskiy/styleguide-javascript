<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/styleguide-javascript/develop/assets/images/repository-hero.svg?sanitize=true"/></p>

<p align="center">The Arctic Ice Studio JavaScript Code Style based on the <a href="https://github.com/airbnb/javascript" target="_blank">Airbnb JavaScript Style Guide</a>.</p>

<p align="center"><a href="https://github.com/arcticicestudio/styleguide-javascript/releases/latest" target="_blank"><img src="https://img.shields.io/github/release/arcticicestudio/styleguide-javascript.svg?style=flat-square&label=Release&logo=github&logoColor=eceff4&colorA=4c566a&colorB=88c0d0"/></a> <a href="https://arcticicestudio.github.io/styleguide-javascript" target="_blank"><img src="https://img.shields.io/github/release/arcticicestudio/styleguide-javascript.svg?style=flat-square&label=Docs&logo=read-the-docs&logoColor=eceff4&colorA=4c566a&colorB=88c0d0"/></a> <a href="https://github.com/arcticicestudio/styleguide-javascript/blob/develop/CHANGELOG.md" target="_blank"><img src="https://img.shields.io/github/release/arcticicestudio/styleguide-javascript.svg?style=flat-square&label=Changelog&logo=github&logoColor=eceff4&colorA=4c566a&colorB=88c0d0"/></a></p>

<p align="center"><a href="https://www.npmjs.com/package/eslint-config-arcticicestudio" target="_blank"><img src="https://img.shields.io/npm/v/eslint-config-arcticicestudio.svg?style=flat-square&label=eslint-config-arcticicestudio&logoColor=eceff4&colorA=4c566a&colorB=88c0d0&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiI+PHBhdGggZmlsbD0iI2Q4ZGVlOSIgZD0iTTEyIDE0SDRhMiAyIDAgMCAxLTItMlY0YTIgMiAwIDAgMSAyLTJoOGEyIDIgMCAwIDEgMiAydjhhMiAyIDAgMCAxLTIgMnpNNCAzLjMzMkEuNjcuNjcgMCAwIDAgMy4zMzIgNHY4YzAgLjM2Ny4zLjY2OC42NjguNjY4aDhhLjY3LjY3IDAgMCAwIC42NjgtLjY2OFY0QS42Ny42NyAwIDAgMCAxMiAzLjMzMnptMCAwIi8+PHBhdGggZmlsbD0iI2Q4ZGVlOSIgZD0iTTggNmgyLjY2OHY2LjY2OEg4em0wIDAiLz48L3N2Zz4K"/></a> <a href="https://www.npmjs.com/package/eslint-config-arcticicestudio-base"><img src="https://img.shields.io/npm/v/eslint-config-arcticicestudio-base.svg?style=flat-square&label=eslint-config-arcticicestudio-base&logoColor=eceff4&colorA=4c566a&colorB=88c0d0&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiI+PHBhdGggZmlsbD0iI2Q4ZGVlOSIgZD0iTTEyIDE0SDRhMiAyIDAgMCAxLTItMlY0YTIgMiAwIDAgMSAyLTJoOGEyIDIgMCAwIDEgMiAydjhhMiAyIDAgMCAxLTIgMnpNNCAzLjMzMkEuNjcuNjcgMCAwIDAgMy4zMzIgNHY4YzAgLjM2Ny4zLjY2OC42NjguNjY4aDhhLjY3LjY3IDAgMCAwIC42NjgtLjY2OFY0QS42Ny42NyAwIDAgMCAxMiAzLjMzMnptMCAwIi8+PHBhdGggZmlsbD0iI2Q4ZGVlOSIgZD0iTTggNmgyLjY2OHY2LjY2OEg4em0wIDAiLz48L3N2Zz4K"/></a></p>

<p align="center"><a href="https://circleci.com/gh/arcticicestudio/styleguide-javascript" target="_blank"><img src="https://img.shields.io/circleci/project/github/arcticicestudio/styleguide-javascript/develop.svg?style=flat-square&label=Build&logo=circleci&logoColor=eceff4&colorA=4c566a"/></a></p>

Every major open source project has its own style guide, a set of standards and conventions for the writing and design of code, documentations and assets. It is much easier to understand a large codebase when all the code in it is in a consistent style.

A style guide establishes and enforces styles to improve the intelligibility and communication within the project community. It ensures consistency and enforces best practice in usage and language composition.

### Getting Started

The [project documentation][docs] contains chapters to learn about the [comprehensive base rule set][docs-rules] including [ECMAScript +6 (ES 2015+)][docs-rules-ecmascript_6+_styles] and [React][docs-rules-react] specific styles like e.g. [Higher-Order Components][docs-rules-react-hoc], the [component methods & properties ordering][docs-rules-react-ordering-methods_and_properties] and [props][docs-rules-react-props].

The development chapters contain information about the [requirements][docs-dev-requirements], [how to build][docs-dev-building] this style guide documentation and [run the tests][docs-dev-testing].

#### ESLint Configurations

To make sure a project adheres to this style guide, use the official extensible code linter configuration [eslint-config-arcticicestudio-base][eslint-config-arcticicestudio-base-ghio] for [ESLint][eslint]. The advanced [eslint-config-arcticicestudio][eslint-config-arcticicestudio-ghio] package provides support for [React][react] and [JSX A11Y][npm-eslint-plugin-jsx-a11y] specific rules as well as an compatibility integration for [Prettier][].

### Contributing

Read the [contributing guide][docs-dev-contributing] to learn about the development process and how to propose [enhancement suggestions][docs-dev-contributing-enhancements] and [report bugs][docs-dev-contributing-bug-reports], how to [submit pull requests][docs-dev-contributing-pr] and the project's [styleguides][docs-dev-contributing-styleguides], [branch organization][docs-dev-contributing-branch-org] and [versioning][docs-dev-contributing-versioning] model.

The guide also includes information about [minimal, complete, and verifiable examples][docs-dev-contributing-mcve] and other ways to contribute to the project like [improving existing issues][docs-dev-contributing-other-improve-issues] and [giving feedback on issues and pull requests][docs-dev-contributing-other-feedback].

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/nord/repository-footer-separator.svg?sanitize=true" /></p>

<p align="center">Copyright &copy; 2018-present <a href="https://www.arcticicestudio.com" target="_blank">Arctic Ice Studio</a> and <a href="https://www.svengreb.de" target="_blank">Sven Greb</a></p>

<p align="center"><a href="https://github.com/arcticicestudio/styleguide-javascript/blob/develop/LICENSE.md" target="_blank"><img src="https://img.shields.io/static/v1.svg?style=flat-square&label=License&message=MIT&logoColor=eceff4&logo=github&colorA=4c566a&colorB=88c0d0"/></a></p>

[docs-dev-building]: https://arcticicestudio.github.io/styleguide-javascript/development/building.html
[docs-dev-contributing-branch-org]: https://arcticicestudio.github.io/styleguide-javascript/development/contributing.html#branch-organization
[docs-dev-contributing-bug-reports]: https://arcticicestudio.github.io/styleguide-javascript/development/contributing.html#bug-reports
[docs-dev-contributing-enhancements]: https://arcticicestudio.github.io/styleguide-javascript/development/contributing.html#enhancement-suggestions
[docs-dev-contributing-mcve]: https://arcticicestudio.github.io/styleguide-javascript/development/contributing.html#mcve
[docs-dev-contributing-other-feedback]: https://arcticicestudio.github.io/styleguide-javascript/development/contributing.html#give-feedback-on-issues-and-pull-requests
[docs-dev-contributing-other-improve-issues]: https://arcticicestudio.github.io/styleguide-javascript/development/contributing.html#improve-issues
[docs-dev-contributing-pr]: https://arcticicestudio.github.io/styleguide-javascript/development/contributing.html#pull-requests
[docs-dev-contributing-styleguides]: https://arcticicestudio.github.io/styleguide-javascript/development/contributing.html#styleguides
[docs-dev-contributing-versioning]: https://arcticicestudio.github.io/styleguide-javascript/development/contributing.html#versioning
[docs-dev-contributing]: https://arcticicestudio.github.io/styleguide-javascript/development/contributing.html
[docs-dev-requirements]: https://arcticicestudio.github.io/styleguide-javascript/development/requirements.html
[docs-dev-testing]: https://arcticicestudio.github.io/styleguide-javascript/development/testing.html
[docs-rules-ecmascript_6+_styles]: https://arcticicestudio.github.io/styleguide-javascript/rules/ecmascript_6+_styles.html
[docs-rules-react-hoc]: https://arcticicestudio.github.io/styleguide-javascript/rules/react/higher_order_components.html
[docs-rules-react-ordering-methods_and_properties]: https://arcticicestudio.github.io/styleguide-javascript/rules/react/ordering.html#component-methods-and-properties
[docs-rules-react-props]: https://arcticicestudio.github.io/styleguide-javascript/rules/react/props.html
[docs-rules-react]: https://arcticicestudio.github.io/styleguide-javascript/rules/react/index.html
[docs-rules]: https://arcticicestudio.github.io/styleguide-javascript/rules/index.html
[docs]: https://arcticicestudio.github.io/styleguide-javascript
[eslint-config-arcticicestudio-base-ghio]: https://arcticicestudio.github.io/eslint-config-arcticicestudio-base
[eslint-config-arcticicestudio-ghio]: https://arcticicestudio.github.io/eslint-config-arcticicestudio
[eslint]: https://eslint.org
[npm-eslint-plugin-jsx-a11y]: https://www.npmjs.com/package/eslint-plugin-jsx-a11y
[prettier]: https://prettier.io
[react]: https://reactjs.org
