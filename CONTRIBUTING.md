# Contributing to Ultimate Prompt Engineering Playbook

Thank you for your interest in contributing! This repository aims to be the most comprehensive, practical resource for prompt engineering. Every contribution helps the community learn and build better AI applications.

## 🎯 How to Contribute

### 1. Adding New Techniques

- Check if the technique already exists in the repository
- Create a new notebook following the [template structure](#notebook-template)
- Place it in the appropriate category folder
- Use the next available technique number
- Include practical examples, failure cases, and benchmarks

### 2. Improving Existing Notebooks

- Fix bugs or errors in code examples
- Add clearer explanations
- Include additional model providers (Claude, Gemini, etc.)
- Expand real-world examples
- Add more interactive elements

### 3. Reporting Issues

- Use GitHub Issues to report bugs
- Include notebook name and cell number
- Describe expected vs. actual behavior
- Provide minimal reproduction steps

### 4. Documentation

- Fix typos or unclear explanations
- Add missing references
- Improve README sections
- Translate content (future goal)

## 📝 Notebook Template

Each notebook must include:

```markdown
1. Title with Colab badge
2. Description (what, when, why)
3. How It Works (step-by-step)
4. Setup (install + API keys)
5. Basic Example
6. Real-World Example
7. Failure Case
8. Benchmark (if available)
9. Interactive Playground
10. Tips & Tricks
11. References
```

### Code Standards

- Use `getpass` for API keys (never hardcode)
- Include comments for clarity
- Make code runnable in Google Colab
- Test all cells before submitting
- Support multiple model providers when possible

## 🔧 Development Setup

```bash
# Clone the repository
git clone https://github.com/amerob/ultimate-prompt-engineering-playbook.git
cd ultimate-prompt-engineering-playbook

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

## 📋 Submission Checklist

Before submitting a PR:

- [ ] Notebook runs without errors in Colab
- [ ] All code cells execute successfully
- [ ] No API keys are hardcoded
- [ ] Colab badge points to correct path
- [ ] Follows naming convention: `##_technique_name.ipynb`
- [ ] Includes all required sections
- [ ] References are included and valid

## 🏆 Recognition

Contributors will be:
- Listed in the README acknowledgments
- Credited in release notes
- Mentioned in social media announcements

## 📞 Questions?

- Open a GitHub Discussion for questions
- Tag `@amerob` for urgent issues
- Join our community Discord (coming soon)

## 📝 License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

**Happy Prompt Engineering!** 🚀
