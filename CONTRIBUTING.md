# Contributing to Testing Multi-Agent

Thank you for considering contributing to **Testing Multi-Agent**! We welcome contributions of all kinds – bug reports, feature requests, documentation improvements, and code contributions.

## How to Contribute

1. **Fork the repository**
   Click the *Fork* button at the top right of the repository page.

2. **Clone your fork**
   ```bash
   git clone https://github.com/yourusername/Testing-Multi-Agent.git
   cd Testing-Multi-Agent
   ```

3. **Create a new branch**
   ```bash
   git checkout -b my-feature-branch
   ```
   Use a descriptive name for the branch, e.g., `fix-typo-readme` or `add-new-agent`.

4. **Make your changes**
   - Follow the existing code style and conventions.
   - Ensure your changes are well‑documented.
   - Add or update tests as appropriate.

5. **Run the test suite**
   ```bash
   pytest
   ```
   All tests should pass before you submit a pull request.

6. **Commit your changes**
   ```bash
   git add .
   git commit -m "Brief description of the change"
   ```

7. **Push to your fork**
   ```bash
   git push origin my-feature-branch
   ```

8. **Open a Pull Request**
   - Navigate to the original repository and click *New pull request*.
   - Select your branch as the source and `add-docs` (or `main` if appropriate) as the target.
   - Provide a clear title and description of your changes.

## Code Style

- Follow PEP 8 guidelines.
- Use meaningful variable and function names.
- Keep lines under 88 characters where possible.
- Include docstrings for public modules, classes, and functions.

## Documentation

- Update the `README.md` or add files in the `docs/` directory as needed.
- Ensure any new public APIs are documented.

## Reporting Issues

If you encounter a bug or have a feature request, please open an issue with:
- A clear title.
- A detailed description.
- Steps to reproduce (for bugs).
- Expected vs. actual behavior.

## License

By contributing, you agree that your contributions will be licensed under the same MIT License as the project.
