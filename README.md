# Kito's Personal Claude Code Configuration Repository

This is Kito's personal Claude Code configuration repository, used for backup and sharing purposes.

## About

I'm a Toolchain Developer currently working on integrating Claude Code workflows into daily LLVM and GNU toolchain development. This repository contains my personal configurations, custom commands, and workflow optimizations that help streamline compiler development tasks.

## Purpose

This repository contains personal Claude Code configurations and settings for backup and collaboration, specifically tailored for toolchain development workflows.

## How to Use

- Clone this repository directly to your `~/.claude/` or `~/.augment/` directory
- Or clone this repository and copy the `commands` directory to `~/.claude/commands` or `~/.augment/commands`

## Features

- Personal Claude Code configurations backup
- Custom commands and workflows for compiler development
- LLVM and GCC development workflow optimizations
- Toolchain debugging and testing automation scripts
- Settings sharing with the compiler development community
- Version control for configuration files

## Note on Language

Most commands in the `commands` directory are written in Traditional Chinese, as they are tailored for personal use and workflow optimization.

## Structure

- `/commands` - Custom command configurations (mostly in Traditional Chinese)
  - Compiler testing automation
  - Code review workflows
- `/CLAUDE.md` - Global instructions and guidelines
- Other configuration files as needed

## Use Cases

- Automating repetitive LLVM/GCC development tasks
- Cross-compilation workflow automation
- Patch review and submission workflows

## Usage

Clone this repository to access and use the configurations:

```bash
git clone [repository-url]
```

## How to Use Commands in Claude or Auggie

### Basic Command Usage

Once the commands are in your `~/.claude/commands` or `~/.augment/commands` directory, you can invoke them directly in your Claude Code or Augment session:

1. **List available commands**: Type `/` to see all available custom commands
2. **Execute a command**: Type `/command-name` to run a specific command
3. **Command with parameters**: Some commands accept parameters, use `/command-name parameter1 parameter2`

### Example Workflow

```bash
# Available commands for toolchain development
/commit-log                    # Generate commit log messages
/gcc-commit-log               # GCC-specific commit log formatting
/llvm-commit-log              # LLVM-specific commit log formatting
/review-as-craig              # Code review with Craig's style
/review-as-linus              # Code review with Linus's style
/review-github-pr             # Review GitHub pull requests
/review-github-pr-and-reply   # Review and reply to GitHub PRs
/process-review-comment       # Process and address review comments
```

### Tips for Effective Use

- Commands can be chained together for complex workflows
- Use tab completion (if available) to quickly access frequently used commands
- Commands respect your current working directory context
- Output from commands can be piped or redirected as needed

## Contributing

Feel free to fork, share your own configurations, or suggest improvements through issues and pull requests.

## License

This project is for personal use and community sharing.
