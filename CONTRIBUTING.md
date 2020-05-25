# Contributing

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to {{PROJECT_NAME}}. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

- [Code of Conduct](#code-of-conduct)
- [Asking Questions](#asking-questions)
- [How Can I Contribute?](#how-can-i-contribute)
  - [Reporting Bugs](#reporting-bugs)
    - [How Do I Submit A (Good) Bug Report?](#how-do-i-submit-a-good-bug-report)
  - [Requesting Features](#requesting-features)
    - [How Do I Submit A (Good) Feature Request?](#how-do-i-submit-a-good-feature-request)
  - [Your First Code Contribution](#your-first-code-contribution)
  - [Pull Requests](#pull-requests)
- [Version Control Standards](#version-control-standards)
- [Code Style Standards](#code-style-standards)
  - [Linting & Formatting](#linting--formatting)
  - [General Style Guidelines](#general-style-guidelines)


## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to {{OWNER_EMAIL}}.

## Asking Questions

Don't want to read this whole doc, just have a question?

Please don't file an issue to ask a question. You'll get faster results by using the resources below.

{{CHAT_APP_URL}}

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer: :computer:, and find related reports :mag_right:.

[Report a bug :bug:]({{REPO_URL}}/issues/new?template=bug_report.md&labels=bug&title=New%20bug%20report)

When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report).

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue on that repository.

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Did the problem start happening recently**
* If the problem started happening recently, **can you reproduce the problem in an older version?** What's the most recent version in which the problem doesn't happen?
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.
* If the problem is related to working with files (e.g. opening and editing files), **does the problem happen for all files and projects or only some?** Does the problem happen only when working with local or remote files (e.g. on network drives), with files of a specific type (e.g. only JavaScript or Python files), with large files or files with very long lines, or with files in a specific encoding? Is there anything else special about the files you are using?

Include details about your configuration and environment:

* **Which version are you using?**
* **What's the name and version of the OS you're using**?

### Requesting Features

This section guides you through submitting an enhancement suggestion, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

[Request a feature :star2:]({{REPO_URL}}/issues/new?template=feature_request.md&labels=enhancement&title=New%20feature%20request)

When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion).

#### How Do I Submit A (Good) Feature Request?

Feature requests are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue on that repository and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots and animated GIFs** which help you demonstrate the steps.

### Your First Code Contribution

Once you've gotten your local environment up and running (see "Installation" in the [README](README.md)), you can:

1. Create a new git branch
2. Write your code, following the [Code Style Standards](#code-style-standards)
3. Create your commit(s) using the commit guidelines in [Version Control Standards](#version-control-standards)
4. Push the branch up to GitHub
5. Open a [pull request](#pull-requests)!

### Pull Requests

We follow the [GitHub flow](https://guides.github.com/introduction/flow/) to create and manage pull requests. When you have a PR ready, request a review from one or more teammates.

## Version Control Standards

We use the [commitizen](https://github.com/commitizen/cz-cli) tool to keep our commit messages clear, readable, and consistently formatted. This helps ensure that all contributors can benefit from a useful version control history.

When you commit your code, please use the provided commit command instead of `git commit`:

```shell
$ {{COMMIT_COMMAND}}
? Select the type of change that you're committing:
  feat:     A new feature
  fix:      A bug fix
❯ docs:     Documentation only changes
  style:    Changes that do not affect the meaning of the code (white-space, formattin
g, missing semi-colons, etc)
  refactor: A code change that neither fixes a bug nor adds a feature
  perf:     A code change that improves performance
(Move up and down to reveal more choices)
```

## Code Style Standards

### Linting & Formatting

We use {{LINTER_TOOL}} to lint/format the code in this project.

In many cases, this tool can automatically fix style errors in your code by integrating direclty with your editor and/or through running the fix command `{{LINTER_FIX_COMMAND}}`.

Before your commit your changes, make sure that they pass the linter's specifications using the command `{{LINTER_COMMAND}}` and then fixing the errors & warnings shown.

### General Style Guidelines

In addition to the rules enforced by the linter, we also request that you follow these general purpose guidelines to ensure that the codebase remains readable and maintainable. When in doubt, aim leave the code you touch in better condition than when you found it!

- Use names that make sense
- Keep your functions small
- Practice good code composition and encapsulation
- Write tests for the important stuff
- Keep scalability and performance in mind

---

**Attribution:** _This file is heavily influenced by the [Atom Contributing Guide](https://github.com/atom/atom/blob/master/CONTRIBUTING.md)._