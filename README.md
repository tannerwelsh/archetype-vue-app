# Archetype Template

This repo serves as a starting template to be used for other repos.

It incorporates sensible defaults and best practices that apply to nearly any repo, as well as more specific practices for particular languages / frameworks.

To use this repo as a template:

- [ ] Remove files which do not apply to your project
  - [ ] For Ruby projects:
    ```shell
    rm .nvmrc .gitignore-node package.json yarn.lock
    mv .gitignore-ruby .gitignore
    ```
  - [ ] For JavaScript / Node.js projects:
    ```shell
    rm .ruby-version .gitignore-ruby Gemfile
    ```
- [ ] Replace this [README.md](README.md) file with the contents from [README-TEMPLATE.md](README-TEMPLATE.md)
    ```shell
    mv README-TEMPLATE.md README.md
    ```
- [ ] Replace all template strings (pattern: `{{LABEL}}`) with actual values
    ```shell
    grep '{{.*}}' *
    ```

<!-- TODO: Use npx with a customizeable setup script (see npm enquirer) to automate the above tasks -->

## General Purpose Files

- [README.md](README-TEMPLATE.md)
  Covering: installation, usage, foundations, contributing, versioning, authors, acknowledgments
- [CONTRIBUTING.md](CONTRIBUTING.md)
  Covering: reporting bugs, requesting features, opening pull requests
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [LICENSE](LICENSE)
- GitHub [Issue Templates](.github/ISSUE_TEMPLATE)
  - for bugs: [bug_report.md](.github/ISSUE_TEMPLATE/bug_report.md)
  - for feature requests: [feature_request.md](.github/ISSUE_TEMPLATE/feature_request.md)
- GitHub [Pull Request Templates](.github/PULL_REQUEST_TEMPLATE.md)

## JavaScript / Node.js Files

- [.gitignore-node](.gitignore-node)
  ```shell
  mv .gitignore-node .gitignore
  ```
- [.nvmrc](.nvmrc)
- [package.json](package.json)
- [yarn.lock](yarn.lock)

## Ruby Files

- [.gitignore-ruby](.gitignore-ruby)
  ```shell
  mv .gitignore-ruby .gitignore
  ```
- [.ruby-version](.ruby-version)
- [Gemfile](Gemfile)