# GitHub Copilot Instructions for AI Code Projects

This repository contains small AI projects and experiments. Please follow these guidelines when generating code suggestions and assistance.

## Repository Context

This is a collection of small AI projects focused on:
- Machine learning experiments and prototypes
- AI utility scripts and tools
- Educational AI code examples
- Data science projects and notebooks

## Programming Languages & Frameworks

**Primary Language:** Python
- Use Python 3.8+ compatible syntax
- Follow PEP 8 style guidelines
- Prefer type hints for function signatures
- Use descriptive variable and function names

**Common AI/ML Libraries:**
- NumPy, pandas for data manipulation
- scikit-learn, TensorFlow, PyTorch for ML/DL
- matplotlib, seaborn for visualization
- Jupyter notebooks for experiments

## Code Style & Best Practices

### General Guidelines
- Write clean, readable, and well-documented code
- Include docstrings for all functions and classes
- Add inline comments for complex logic
- Use meaningful variable names that describe the data/purpose
- Follow the principle of single responsibility

### AI/ML Specific Guidelines
- Always include data validation and error handling
- Document model architectures and parameters clearly
- Include performance metrics and evaluation code
- Use reproducible random seeds where applicable
- Comment on hyperparameter choices and tuning strategies

### File Organization
- Keep related functionality in separate modules
- Use descriptive file names that indicate content
- Include requirements.txt or environment.yml for dependencies
- Add README files for individual projects explaining setup and usage

## Documentation Standards

- Include clear README files for each project
- Document data sources and preprocessing steps
- Explain model choices and evaluation methodology
- Provide usage examples and expected outputs
- Include installation and setup instructions

## Testing & Quality

- Write unit tests for utility functions
- Include data validation tests
- Test edge cases and error conditions
- Validate model outputs and performance metrics
- Use appropriate assertion messages

## Security & Privacy

- Never hardcode API keys, credentials, or sensitive data
- Use environment variables for configuration
- Sanitize and validate all input data
- Be mindful of data privacy when working with datasets
- Comment on any data usage limitations or restrictions

## Project Structure Preferences

For new AI projects, suggest this structure:
```
project_name/
├── README.md
├── requirements.txt
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
│   ├── __init__.py
│   ├── data_processing.py
│   ├── models.py
│   └── utils.py
├── tests/
└── results/
```

## Code Generation Preferences

- Prioritize readability over cleverness
- Include error handling and edge case considerations
- Suggest appropriate logging for debugging
- Recommend performance optimizations when relevant
- Consider memory usage for large datasets
- Suggest parallel processing opportunities where applicable

## Educational Focus

When generating code:
- Include explanatory comments for learning purposes
- Suggest alternative approaches with trade-offs
- Explain algorithmic choices and complexity considerations
- Provide links to relevant documentation or papers
- Include examples of common pitfalls and how to avoid them