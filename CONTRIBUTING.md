# Contributing to VidSyncAvatar

Thank you for your interest in contributing to VidSyncAvatar! This document provides guidelines for contributing to the project.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [Getting Started](#getting-started)
3. [How to Contribute](#how-to-contribute)
4. [Development Workflow](#development-workflow)
5. [Coding Standards](#coding-standards)
6. [Pull Request Process](#pull-request-process)
7. [Reporting Issues](#reporting-issues)

## Code of Conduct

We are committed to providing a welcoming and inclusive environment for all contributors. Please:

- Be respectful and considerate in your interactions
- Welcome newcomers and help them get started
- Focus on constructive feedback
- Respect differing viewpoints and experiences

## Getting Started

1. Fork the repository on GitHub
2. Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/VidSyncAvatar.git
   cd VidSyncAvatar
   ```
3. Add the upstream repository:
   ```bash
   git remote add upstream https://github.com/ORIGINAL_OWNER/VidSyncAvatar.git
   ```

## How to Contribute

We welcome contributions in several forms:

- **Code contributions**: Bug fixes, new features, performance improvements
- **Documentation**: Improvements to README, tutorials, or API documentation
- **Bug reports**: Detailed reports of issues you encounter
- **Feature requests**: Suggestions for new functionality
- **Research contributions**: Links to relevant papers or technologies

## Development Workflow

1. **Create a branch** for your work:
   ```bash
   git checkout -b feature/your-feature-name
   ```
   Use prefixes: `feature/`, `bugfix/`, `docs/`, `refactor/`

2. **Make your changes** following our coding standards

3. **Test your changes** thoroughly

4. **Commit your changes** with clear, descriptive messages:
   ```bash
   git commit -m "feat: Add new avatar generation feature"
   ```
   Follow conventional commit format: `type: description`
   - `feat`: New feature
   - `fix`: Bug fix
   - `docs`: Documentation changes
   - `refactor`: Code refactoring
   - `test`: Adding or updating tests
   - `chore`: Maintenance tasks

5. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Open a Pull Request** on GitHub

## Coding Standards

### General Principles

- Write clean, readable, and maintainable code
- Follow existing code style and patterns in the project
- Add comments for complex logic
- Keep functions small and focused
- Use meaningful variable and function names

### Python Code (when applicable)

- Follow PEP 8 style guide
- Use type hints for function parameters and return values
- Write docstrings for classes and functions
- Maximum line length: 100 characters

### Documentation

- Keep README.md up to date
- Document all public APIs and functions
- Include examples in documentation
- Update relevant docs when changing functionality

## Pull Request Process

1. **Ensure your PR**:
   - Has a clear, descriptive title
   - References any related issues (e.g., "Closes #123")
   - Includes a detailed description of changes
   - Passes all tests (when test suite is available)
   - Follows the coding standards

2. **PR Review Process**:
   - Maintainers will review your PR
   - Address any feedback or requested changes
   - Be patient and respectful during the review
   - PRs may be merged, closed, or need revisions

3. **After Merge**:
   - Delete your feature branch
   - Pull latest changes from upstream:
     ```bash
     git checkout main
     git pull upstream main
     ```

## Reporting Issues

When reporting bugs or requesting features:

1. **Search existing issues** first to avoid duplicates

2. **For bug reports**, include:
   - Clear, descriptive title
   - Steps to reproduce the issue
   - Expected behavior vs. actual behavior
   - Environment details (OS, Python version, etc.)
   - Screenshots or error messages if applicable

3. **For feature requests**, include:
   - Clear description of the proposed feature
   - Use cases and benefits
   - Any relevant research or examples

## Special: `ai-implement` Label

Issues labeled with `ai-implement` may be automatically implemented by Claude Code automation. These issues should:
- Have clear, specific requirements
- Include acceptance criteria
- Reference related documentation or examples

## Questions?

If you have questions about contributing:
- Open a discussion on GitHub
- Review existing issues and PRs for context
- Check the README and other documentation

Thank you for contributing to VidSyncAvatar!
