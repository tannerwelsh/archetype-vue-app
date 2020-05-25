# Archetypal Vue App Template

This repo serves as a starting template to be used for Vue web applications.

It incorporates sensible defaults and best practices that apply to nearly any repo.

To use this repo as a template:

- [ ] Remove files which do not apply to your project
    ```shell
    rm -rf ./files-ruby
    mv ./files-js/* .
    rmdir ./files-js
    ```
- [ ] Replace all template strings (pattern: `{{LABEL}}`) with actual values
    ```shell
    grep '{{.*}}' *
    ```
- [ ] Replace placeholders in [README-TEMPLATE.md](README-TEMPLATE.md) with useful content for your project. (Format: `[INCLUDE: ...]`)
- [ ] Replace this [README.md](README.md) file with the contents from [README-TEMPLATE.md](README-TEMPLATE.md)
    ```shell
    mv README-TEMPLATE.md README.md
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
