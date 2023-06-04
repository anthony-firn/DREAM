# DREAM Style Guide

This document describes the programming style guidelines for contributing to the DREAM project. The DREAM project is multi-language, and as such, this guide provides general style rules as well as Python-specific recommendations. Always prioritize readability and maintainability.

## Table of Contents

- [General Guidelines](#general-guidelines)
- [Python Style Guide](#python-style-guide)
- [Commenting and Documentation](#commenting-and-documentation)
- [Testing](#testing)
- [Best Practices](#best-practices)

## General Guidelines

- **Consistency**: Consistency is key. If you're editing code, take a few minutes to look at the code around you and determine its style. If the codebase has a mix of styles, try to stick to the style of the module or function you're changing.
- **Descriptive Naming**: Use descriptive names for variables, functions, and classes. Avoid abbreviations unless they are well-known.
- **Indentation**: Use 4 spaces for indentation, not tabs, to ensure consistent formatting across various text editors.
- **Max Line Length**: Keep the line length to a maximum of 80 characters where possible. This helps make the code more readable and easier to understand.

## Python Style Guide

- Follow the [PEP 8 style guide](https://www.python.org/dev/peps/pep-0008/) for Python code.
- Use [Type Hints](https://docs.python.org/3/library/typing.html) to make your code more easy to understand and debug.
- Use list comprehensions and generator expressions instead of filter and map when they improve readability and aren't overly complicated.
- Follow [PEP 257](https://www.python.org/dev/peps/pep-0257/) to provide docstrings for all public modules, functions, classes, and methods.

## Commenting and Documentation

- **Code Commenting**: Provide comments for complex code blocks. Comments should be clear and concise.
- **Documentation**: Use Markdown for documentation. All functions/methods should have clear documentation including a brief description, all argument descriptions, and return type.
- **Readme Files**: Ensure every module or sub-project has a README file explaining the purpose, technical architecture, and how to run it.

## Testing

- Write unit tests for your code and ensure they pass before pushing the changes.
- Try to write tests that cover multiple scenarios and edge cases, not just the "happy path".
- Use a consistent naming convention for your test functions, such as `test_<function_name>_<scenario>`.

## Best Practices

- **Code Review**: Participate in code review process, both as a reviewer and reviewee.
- **Refactoring**: Don't be afraid to refactor existing code if it improves readability or efficiency.
- **Error Handling**: Always handle exceptions and error cases. Avoid bare `except:` statements in Python.
- **Security**: Be aware of the security implications of your code. This is especially important for blockchain and distributed computing projects.

---

These guidelines aim to make the DREAM project's codebase clean and coherent, thus making it more maintainable and welcoming for contributors. Let's work together to create a great project!