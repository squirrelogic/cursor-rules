# Contributing to Cursor Rules

We love your input! We want to make contributing to Cursor Rules as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the rules
- Submitting a fix
- Proposing new rules
- Improving documentation

## Development Process

We use GitHub to host code, to track issues and feature requests, as well as accept pull requests.

1. Fork the repo and create your branch from `main`
2. If you've added new rules, make sure they follow our existing format
3. Update documentation if needed
4. Issue that pull request!

## Rule File Standards

When creating or modifying rule files:

1. Place all rule files in `.cursor/rules/` directory
2. Use kebab-case for filenames with `.mdc` extension
3. Follow the standard rule format:
   ```markdown
   # Rule Name
   Description of the rule

   <rule>
   name: rule_name
   description: Detailed description
   filters:
     # ... filters ...
   actions:
     # ... actions ...
   </rule>
   ```

## Commit Messages

We follow the Conventional Commits specification. Each commit message should be structured as follows:

```
type(scope): description

[optional body]

[optional footer]
```

Types:
- feat: New feature or rule
- fix: Bug fix
- docs: Documentation changes
- style: Formatting changes
- refactor: Code refactoring
- test: Adding/modifying tests
- chore: Maintenance tasks

## Pull Request Process

1. Update the README.md with details of changes if needed
2. Follow the pull request template
3. You may merge the Pull Request once you have the sign-off of at least one other developer

## Any Contributions You Make Will Be Under the MIT Software License

In short, when you submit code changes, your submissions are understood to be under the same [MIT License](LICENSE) that covers the project. Feel free to contact the maintainers if that's a concern.

## Report Bugs Using GitHub's [Issue Tracker](../../issues)

Report a bug by [opening a new issue](../../issues/new); it's that easy!

## Write Bug Reports With Detail, Background, and Sample Code

**Great Bug Reports** tend to have:

- A quick summary and/or background
- Steps to reproduce
  - Be specific!
  - Give sample code if you can
- What you expected would happen
- What actually happens
- Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

## License

By contributing, you agree that your contributions will be licensed under its MIT License.
