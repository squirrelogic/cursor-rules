# Cursor Rules

A collection of standardized rules and guidelines for maintaining high-quality code using Cursor IDE.

## Overview

This repository contains a set of rules that help maintain consistency and quality in codebases using Cursor IDE. These rules cover various aspects of development including:

- Code organization and file structure
- Naming conventions
- Git commit standards
- SOLID principles implementation
- Conversation style guidelines
- And more...

## Rules

1. **Conventional Commits** - Standards for commit message formatting
2. **Community Projects** - Standards for initializing and maintaining community-focused open source projects
3. **Conversation Style** - Guidelines for AI-human interaction in Cursor
4. **Cursor Rules Location** - Standards for rule file placement
5. **File Organization** - Guidelines for code organization
6. **Git Commit Workflow** - Process for validating and committing changes
7. **Naming Conventions** - Standards for naming files and code elements
8. **SOLID Principles** - Implementation of SOLID design principles

## Installation

1. Create a `.cursor/rules` directory in your project root:
   ```bash
   mkdir -p .cursor/rules
   ```

2. Copy the desired rule files into the `.cursor/rules` directory:
   ```bash
   cp path/to/rules/*.mdc .cursor/rules/
   ```

## Usage
In the event that the rules do not load automatically, I have found that the best way to load them is to open the agent composer and say:
```
For the remainder of this session, remember the following @rules
```

It will then respond with:
```
🦄 Let me fetch the rules

🦄 I understand and will follow all the provided rules for our session. Here's a summary of how I'll incorporate them:

1. Conversation Style: I'll start each message with 🦄 and maintain a structured response format.

2. Naming Conventions: I'll ensure all files, types, and functions follow the specified patterns:
- Files in kebab-case
- Types in PascalCase
- Functions in camelCase

3. SOLID Principles: Follow:
   - Single Responsibility: One reason to change
   - Open/Closed: Open for extension, closed for modification
   - Liskov Substitution: Derived classes must be substitutable
   - Interface Segregation: Keep interfaces focused
   - Dependency Inversion: Depend on abstractions

4. Conventional Commits: Format commits as `type(scope): description` with proper body and footer. Types include feat, fix, docs, style, refactor, perf, test, build, ci, chore.

5. Cursor Rules Location: Place all `.mdc` rule files in `.cursor/rules/` directory using kebab-case naming.

6. File Organization: One definition per file, use kebab-case filenames with appropriate suffixes (`.interface.ts`, `.service.ts`), group related files in feature-based directories, organize imports (external/internal/relative).

7. Git Commit Workflow: Run tests, type checks, and build before committing. Follow sequence: validate → test → type-check → build → check changes → stage → commit.

8. Community Projects: I'll ensure any project work follows the community standards with proper README.md, CONTRIBUTING.md, LICENSE, and CODE_OF_CONDUCT.md files.

```
Once installed, these rules will be automatically applied when using Cursor IDE. The rules provide guidance for:

- File naming and organization
- Code structure and design
- Git commit messages
- Development workflows
- And more...

## Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

## Code of Conduct

This project follows a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
