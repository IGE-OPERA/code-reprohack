# Introduction

Review scientific software repositories, with a focus on reproducibility!

# How it works

To review a repository:

 - Create a file named `reviews/YYYY-MM-DD_name-of-repo.md`
 - Copy-paste the following review template
 - Review the repository by filling out said template (remove any irrelevant section from the "Specific cases" section)
 - Feel free to add relevant "free-text" comments and suggestions in your review
 - Use full sentences and avoid cryptic language and abbreviations
 - Do not create any issue or pull request in the repository being reviewed: the task of taking appropriate corrective measures in response to the review is the responsibility of the repository's maintainers

In the template below, reviewing criteria are ranked:

 - L1 (level 1): all repositories should check these.
 - L2 (level 2): these criteria are a bit more advanced.

```
 - URL of the repository:

 - Commit being reviewed:

 - Reviewers (name or Github handle):

 - Findability, accessibility, reusability

   * [ ] [L1] The repository is public

   * [ ] [L1] The repository is backed up on [Software Heritage](https://www.softwareheritage.org/)

   * [ ] [L1] The software has an explicit license

   * [ ] [L1] The license is listed as a free and open source software license by the [open source initiative](https://opensource.org/licenses) and/or the [GNU project](https://www.gnu.org/licenses/license-list.html).

 - Software documentation

   * [ ] [L1] There is a `README.md` file at the root of the repository

   * Said `README.md` file contains/describes:

     - [ ] [L1] The name of the programme

     - [ ] [L1] What the intended use of the programme is

     - [ ] [L1] Instructions on how to install the programme and its dependencies

     - [ ] [L1] "Quick start" instructions: how to run the programme on a basic example, as simple as possible

     - [ ] [L2] A link to a more exhaustive documentation if any.

   * The documentation contains (it can be in the `README.md`, somewhere else in the repository, or in another repository):

     - [ ] [L1] A description of all the options / functionality of the software

     - [ ] [L2] Examples on how to use the software in a variety of applications

   * [ ] [L2] The repository contains a sample dataset (or a proper citation) which can be used to test the software

   * [ ] [L1] A DOI is given for each paper / dataset that is cited in the documentation

   * [ ] [L2] The repository contains a file named `citation.cff`, formatted according to the [citation file format](https://citation-file-format.github.io/)

   * [ ] [L2] The repository contains the files `CONTRIBUTING.md` and/or `GOVERNANCE.md` that explain how to contribute to the project

   * [ ] [L2] The repository contains a changelog a release note that explain changes between the different versions of the software

- Code clarity and documentation

   * [ ] [L1] The code is written in a clear and modular way (short functions, libraries, modules, ...)

   * [ ] [L1] Each function' signature is properly documented with a docstring, and docstrings use a consitent format

   * [ ] [L1] The repository contains a `.gitignore` file to prevent inclusion of undesirable files

   * [ ] [L2] The code is linted

   * [ ] [L2] Code linting is enforced by continuous integration facilities

- Tests

   * [ ] [L1] The repository contains unit tests

   * [ ] [L1] The repository contains integration tests

   * [ ] [L2] Tests are enforced by continuous integration facilities

   * [ ] [L2] Test coverage is measured

- Versioning

   * [ ] [L1] The software has clearly identified versions (tags, releases, ...)

- Specific cases:

   * [ ] Python:

     - [ ] [L1] The repository contains a file named `pyproject.toml` that respects [the "standard" format](https://peps.python.org/pep-0621/)

     - [ ] [L1] The package can be installed by `pip`
```
