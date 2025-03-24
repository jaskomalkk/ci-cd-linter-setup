# CI/CD Linter Setup

This repository shows how to use GitHub Actions and the Super-Linter GitHub Action to set up continuous integration (CI) and continuous deployment (CD) in a simple way.

## Overview

When code is committed or merged into the main branch, this project is configured to automatically lint it. The Super-Linter action helps keep the code in the repository clear and error-free by checking it for a variety of problems, including syntax and style faults.

## Features

- **Super-Linter GitHub Action**: Lints the code upon commits and pull requests.
- **Development Workflow**: A `dev` branch for development and peer reviews before merging into `main`.
- **Collaborative Workflow**: Pull requests and code reviews from collaborators before merging into the main branch.

## How It Works

1. **Super-Linter Action**: Automatically triggered when code is committed to the repository.
2. **Branches**: Code development is done in the `dev` branch, with pull requests created to merge into the `main` branch after review.
3. **Collaborator Review**: A team member reviews the pull request and approves it before merging.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/jaskomalkk/ci-cd-linter-setup.git
