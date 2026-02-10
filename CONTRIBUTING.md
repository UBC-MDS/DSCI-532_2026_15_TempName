# Contributing to the World Education Dashboard project

This outlines how to propose a change to the World Education Dashboard project.

## Coding style <br>
Consistency in coding style is important throughout the project. We recommend following the official Python style guide (PEP 8).
Key points include:
- Indentation: Use consistent tabs or spaces to maintain readability.
- Line Length: Keep lines reasonably short; avoid exceeding half the width of notebook cells if applicable.
- Comments: Use # for comments and write them clearly to explain the code.
- Whitespace: Include proper spacing around operators, function arguments, and within control structures.
- Imports: Organize import statements in logical groups and in the recommended order (standard library, third-party packages, local modules).

## Prerequisites
Before you make a substantial pull request, you should always file an issue and
make sure someone from the team agrees that it's a problem. If you've found a
bug, create an associated issue and illustrate the bug with a minimal reproducible example.

## Pull Request Process <br>
- It is recommended to create a Git branch for each pull request in order to maintain consistency.
- Code should follow the official python style guide
- We will be using Docstring for documentation.

## Code of Conduct <br>
-  Each contributor shall adhere to the examples set below:
Use welcoming and inclusive language
Be respectful of differing opinions and viewpoints
Be cognizant of intention when proivding constructive criticism
Recognize the best in others
Show empathy towards community members
Each contributor should avoid behaviours such as:

- Sexualized language and unwanted sexual attention/advances
Trolling, insults, derogatory comments, and political attacks
Public or private harassment
Ignoring privacy concerns of the community
And other conduct which could reasonably be considered inappropriate in a professional setting

## Development tools, GitHub infrastructure, and practices used <br>

Throughout this project, our team was able to apply various tools used in software engineering and practices in a real-life data science and machine learning workflow. We were able to leverage Git and GitHub for version control, and had a collaborative process throughout the projects - through pull requests, code reviews, and issue tracking. With these tools, we were able to manage changes systematically and document any design changes, and keep a traceable project history. <br>

## Scaling the project: tools and practices <br>

If we were to scale up this project, we would implement stricter CI checks, and add branch protection rules that required passing certain tests before merging. Furthermore, we would use semantic versioning and automated release for the workflows, ensuring that our deployments are stable. <br>

For infrastructure, Docker would be used in order to ensure consistent environment and documentation across all development and deployment which would help for scalable computation and storage if the project was involved in a larger dataset. We would also make sure that all logging, and dependency security would be monitored as well, so the project remains reliable as it grows. <br>

Overall, these tools and practices would help with the reproducibility, collaboration, and reliability of the project, and would scale organically from small academic projects to production-level systems. <br>

## Code of Conduct

This project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md) and by contributing to or otherwise participating in this project you agree to abide by its terms.

## Attribution

These contributing guidelines were adapted from the [dplyr contributing guidelines](https://github.com/tidyverse/dplyr/blob/master/.github/CONTRIBUTING.md).
