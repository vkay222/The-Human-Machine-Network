# Contributing Guidelines <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Forking the Repository](#forking-the-repository)
- [Cloning Your Fork](#cloning-your-fork)
- [Creating Commit Messages](#creating-commit-messages)

## Forking the Repository

- Click the **Fork** button at the top-right of this page to create your own copy of the repository.

## Cloning Your Fork

```bash
git clone https://github.com/yourusername/The-Human-Machine-Network.git
cd Human-Machine-Network
```

## Creating Commit Messages

We use commitizen with gitmoji for standardized commit messages. To generate a proper commit message in Cursor IDE:

a. In the Cursor AI chat:

- Type `@` and select "PR (Diff with Main Branch)"
- Type `@` again and select "commit.txt"
- Press Enter

The AI will generate a properly formatted commit message based on your changes.

b. Use the generated message with git commit:

```bash
git commit -m "📚 docs: add new feature documentation"
```

Note: This commit message workflow is designed for use with Cursor IDE and its integrated AI assistant.
