# catalog-tool-comments

How tools parse comments that ignore rules.

| Tool | Section | Next Line Only | Current Line Only | Specific Rules | Link |
| - | - | - | - | - | - |
| [ESLint](https://github.com/eslint/eslint) | `eslint-{disable,enable}` | `eslint-disable-next-line` |  `eslint-disable-line` | Yes | [Docs](https://eslint.org/docs/latest/use/configure/rules#disabling-rules) |
| [TSLint](https://palantir.github.io/tslint) | `tslint:{disable,enable}` | `tslint:disable-next-line` | `tslint:disable-line` | Yes | [Docs](https://palantir.github.io/tslint/usage/rule-flags)
| [Prettier](https://github.com/prettier/prettier) | `prettier-ignore-{start,end}` | `prettier-ignore` | | Yes | [Docs](https://prettier.io/docs/en/ignore.html)
| [Stylelint](https://github.com/stylelint/stylelint) | `stylelint-{disable,enable}` | `stylelint-disable-next-line` | `stylelint-disable-line` | Yes | [Docs](https://stylelint.io/user-guide/ignore-code)
| [Markdownlint](https://github.com/DavidAnson/markdownlint) | `markdownlint-{disable,enable}` | `markdownlint-disable-next-line` | `markdownlint-disable-line` | Yes | [Docs](https://github.com/DavidAnson/markdownlint?tab=readme-ov-file#configuration)
| [Biome](https://biomejs.dev) | `biome-ignore lint:` | | | Yes | [Docs](https://biomejs.dev/linter/#ignoring-code)
| [Go](https://go.dev) | `nolint:*` | | | | | |
| [RuboCop](https://rubocop.org) | `rubocop:{enable,disable}` | | | | [Docs](https://docs.rubocop.org/rubocop/configuration.html)
| [Sorbet](https://sorbet.org) | `typed: true` | | | | [Docs](https://sorbet.org/docs/static)
| Cpp | `#pragma GCC diagnostic ignored *`
