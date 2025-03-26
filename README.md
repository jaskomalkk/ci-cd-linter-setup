# CI/CD Linter Setup

This repository uses GitHub Actions and Super-Linter for automatic code linting.

## Features

- **Super-Linter GitHub Action**: Checks code quality on commits and pull requests.
- **Branching Workflow**: Code is developed in `dev` and merged into `main` after review.
- **Collaboration**: Pull requests require review before merging.

## How It Works

1. **Linting**: Runs automatically on commits.
2. **Development**: Work happens in `dev`, then merges into `main` via pull requests.
3. **Review**: A team member approves before merging.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/jaskomalkk/ci-cd-linter-setup.git
