# Contributions Guide

## Introduction

Welcome! We appreciate your interest in contributing to the `jobhunter` project. This document provides a step-by-step guide to help you contribute effectively.

## Looking for Issues

1. **Selecting an Issue**: Begin by looking through open issues tagged with `good first issue` or `help wanted`. 
   - [Open Issues](https://github.com/espin086/jobhunter/issues)
   
2. **Understand Issue Details**: Carefully read the issue description and any associated comments to understand what is expected.

3. **Claim an Issue**: To work on an issue, leave a comment expressing your interest. This prevents multiple contributors from working on the same issue simultaneously.

## Working on the Issue

1. **Fork the Repository**: Create a fork of the `jobhunter` repository to your GitHub account.

2. **Clone Your Fork Locally**: Clone your fork to your local development environment.

   ```bash
   git clone https://github.com/your_username/jobhunter.git
   cd jobhunter
    ```

3. **Setting Up Your Local Environment**: 

Please see [Quickstart Quide](INSTALL.md)

4. **Test Code Before Starting**: run a series of automated tests before starting to contribute. 

    ```bash
    make check
    ```

5. **Create and Checkout a New Branch**: Create a branch for the issue you’re working on. Ensure to name it descriptively.
    ```
    git fetch origin
    git checkout -b issue_number-brief-description
    ```

6. **Work on the Issue**: Make the necessary code changes to resolve the issue.

7. **Create Unit Tests**: Write unit tests for your code contributions and ensure they pass.

    ```bash
    make test
    ```

8. **Commit and Push Your Changes**: Commit your changes with a meaningful commit message, and push them to your forked repository.

    ```bash
    git add .
    git commit -m "Fixed issue_number: brief description"
    git push origin issue_number-brief-description
    ```

## Submitting Pull Request

1. **Create a Pull Request**: Go to the jobhunter repository and create a new pull request from your branch.


2. **Describe Pull Request**: Describe the changes you made, reference the issue number, and mention the maintainers for review.

3. **Wait for Review**: Maintainers will review your pull request and provide feedback. Be patient and address any comments or suggestions they might have.

## Celebrate 🎉

Congratulations, you’ve just contributed to the jobhunter project! Thank you for your valuable contribution!

## Need help?

If you have questions or need help with the contributing process, feel free to reach out to the maintainers or open a new issue. We’re here to help!