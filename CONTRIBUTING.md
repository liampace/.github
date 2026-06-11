
# Contributing

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. It will make it a lot easier for us maintainers and smooth out the experience for all involved. The community looks forward to your contributions. 🎉

> And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:
> - Star the project
> - Tweet about it
> - Refer this project in your project's readme
> - Mention the project at local meetups and tell your friends/colleagues


## Table of Contents

- [I Have a Question](#i-have-a-question)
  - [I Want To Contribute](#i-want-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Your First Code Contribution](#your-first-code-contribution)
  - [Improving The Documentation](#improving-the-documentation)
- [Styleguides](#styleguides)
  - [Commit Messages](#commit-messages)
- [Join The Project Team](#join-the-project-team)



## I Have a Question

> If you want to ask a question, we assume that you have read the available [Documentation](https://github.com/liampace/blank-template/docs/).

Before you ask a question, it is best to search for existing [Q&As](https://github.com/liampace/blank-template/discussions/categories/q-a) that might help you. In the case you have found a Q&A and still need clarification, you can write your question in that Q&A. It is also advisable to search the internet for answers first.

If you then still feel the need to ask a question and need clarification, we recommend the following:

- Open a [Q&A](https://github.com/liampace/blank-template/discussions/new?category=q-a).
- Provide as much context as you can about what you're running into.
- Provide project and platform versions, depending on what seems relevant.

We will then take care of the issue as soon as possible.

## I Want To Contribute

> ### Legal Notice 
> When contributing to this project, you must agree that you have authored 100% of the content, that you have the necessary rights to the content and that the content you contribute may be provided under the project licence.

### Reporting Bugs


#### Before Submitting a Bug Report

A good bug report shouldn't leave others needing to chase you up for more information. Therefore, we ask you to investigate carefully, collect information and describe the issue in detail in your report. Please complete the following steps in advance to help us fix any potential bug as fast as possible.

- Make sure that you are using the latest version.
- Determine if your bug is really a bug and not an error on your side e.g. using incompatible environment components/versions (Make sure that you have read the [documentation](https://github.com/liampace/blank-template/docs/). If you are looking for support, you might want to check [this section](#i-have-a-question)).
- To see if other users have experienced (and potentially already solved) the same issue you are having, check if there is not already a bug report existing for your bug or error in the [bug tracker](https://github.com/liampace/blank-template/issues?q=label%3Abug).
- Also make sure to search the internet (including Stack Overflow) to see if users outside of the GitHub community have discussed the issue.
- Collect information about the bug:
  - Stack trace (Traceback)
  - OS, Platform and Version (Windows, Linux, macOS, x86, ARM)
  - Version of the interpreter, compiler, SDK, runtime environment, package manager, depending on what seems relevant.
  - Possibly your input and the output
  - Can you reliably reproduce the issue? And can you also reproduce it with older versions?


#### How Do I Submit a Good Bug Report?

> You must never report security related issues, vulnerabilities or bugs including sensitive information to the issue tracker, or elsewhere in public. Instead sensitive bugs must be sent by email to <liam.hollum.pace@gmail.com>.
<!-- You may add a PGP key to allow the messages to be sent encrypted as well. -->

We use GitHub issues to track bugs and errors. If you run into an issue with the project:

- Open an [Issue](https://github.com/liampace/blank-template/issues/new). (Since we can't be sure at this point whether it is a bug or not, we ask you not to talk about a bug yet and not to label the issue.)
- Explain the behavior you would expect and the actual behavior.
- Please provide as much context as possible and describe the *reproduction steps* that someone else can follow to recreate the issue on their own. This usually includes your code. For good bug reports you should isolate the problem and create a reduced test case.
- Provide the information you collected in the previous section.

Once it's filed:

- The project team will label the issue accordingly.
- A team member will try to reproduce the issue with your provided steps. If there are no reproduction steps or no obvious way to reproduce the issue, the team will ask you for those steps and mark the issue as `requires: reproduction`. Bugs with the `requires: reproduction` tag will not be addressed until they are reproduced.
- If the team is able to reproduce the issue, it will be marked `requires: fix`, as well as possibly other tags (such as `priority: critical`), and the issue will be left to be implemented by someone.


### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for this repository, **including completely new features and minor improvements to existing functionality**. Following these guidelines will help maintainers and the community to understand your suggestion and find related suggestions.


#### Before Submitting an Enhancement

- Make sure that you are using the latest version.
- Read the [documentation](https://github.com/liampace/blank-template/docs/) carefully and find out if the functionality is already covered, maybe by an individual configuration.
- Perform a [search](https://github.com/liampace/blank-template/issues) to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
- Find out whether your idea fits with the scope and aims of the project. It's up to you to make a strong case to convince the project's developers of the merits of this feature. Keep in mind that we want features that will be useful to the majority of our users and not just a small subset. If you're just targeting a minority of users, consider writing an add-on/plugin library.


#### How Do I Submit a Good Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://github.com/liampace/blank-template/issues).

- Use a **clear and descriptive title** for the issue to identify the suggestion.
- Provide a **step-by-step description of the suggested enhancement** in as many details as possible.
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why. At this point you can also tell which alternatives do not work for you.
- **Explain why this enhancement would be useful** to most users.

### Improving The Documentation

Documentation suggestions are tracked as [GitHub issues](https://github.com/liampace/blank-template/issues).

- Use a **clear and descriptive title** for the issue to identify the suggestion.
- Provide a **thoughrough description of the suggested documentation** in as many details as possible.
- **Describe the current documentation** and **explain what is insufficient or incorrect** and why.
- **Explain why this enhancement would be useful** to most users.

## Styleguides
### Commit Messages
This project uses the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) format.

#### Allowed Commit Types
- `build`: Changes that affect the build system or external dependencies
- `chore`: Changes that indirectly affect the project (.gitignore, merge commits, version bumps, etc)
- `ci`: Changes that affect the project's CI pipeline
- `docs`: Changes that affect the project's documentation
- `feat`: Changes that introduce a new feature
- `fix`: Changes that fixes known bugs
- `perf`: Changes that improve the performance
- `refactor`: Changes that do not change external/user facing behavior
- `revert`: Changes that revert a previous commit
- `test`: Changes to the testing suite
- `wip`: Changes that incrementally build up to a `feat` or `fix` commit
  
#### Commit Format
```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

#### NOTE: Revert Commits
When using a revert commit the following must apply:
- `<subject>` must match the subject of commit being undone
- `<body>` must be `This reverts commit <hash>` where `<hash>` is the SHA hash of the commit being undone

## Attribution
This guide is based on the **contributing-gen**. [Make your own](https://github.com/bttger/contributing-gen)!
