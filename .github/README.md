# GitHub Copilot Configuration

This directory contains GitHub Copilot custom instructions for the ai-code-projects repository.

## Files Overview

### `copilot-instructions.md`
Repository-wide instructions that provide context about:
- Project focus on AI/ML development
- Python coding standards and best practices
- Documentation and testing requirements
- Security and privacy guidelines
- Recommended project structures

### `instructions/` Directory
Path-specific instruction files for different types of projects:

- **`ml-projects.instructions.md`** - Guidelines for machine learning projects including model development, experiment tracking, and best practices
- **`notebooks.instructions.md`** - Best practices for Jupyter notebooks focusing on structure, reproducibility, and visualization
- **`deep-learning.instructions.md`** - Specific guidance for deep learning projects covering architecture design, training processes, and deployment

## How It Works

GitHub Copilot automatically reads these instruction files to provide more contextual and relevant code suggestions. The main `copilot-instructions.md` applies to the entire repository, while files in the `instructions/` directory provide specialized guidance for specific types of development work.

## Updating Instructions

When adding new project types or updating coding standards:
1. Update the main `copilot-instructions.md` for repository-wide changes
2. Add new `.instructions.md` files in the `instructions/` directory for specific contexts
3. Keep instructions clear, concise, and focused on actionable guidance

For more information, see [GitHub's documentation on Copilot custom instructions](https://docs.github.com/en/copilot/how-tos/configure-custom-instructions).