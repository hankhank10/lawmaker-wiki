# Contributing to the Lawmaker Wiki

Thank you for your interest in contributing to the Lawmaker Game Wiki! This guide will help you get started with contributing to the wiki documentation.

## Quick Start

The easiest way to contribute is to edit files directly on GitHub:

1. Navigate to the [lawmaker-wiki repository](https://github.com/hankhank10/lawmaker-wiki)
2. Browse to the file you want to edit in the `docs/` folder
3. Click the pencil icon (✏️) to edit the file
4. Make your changes
5. Click "Propose changes" to create a pull request
6. Submit your pull request for review

## Contributing Workflow

### 1. Fork the Repository

1. Go to [https://github.com/hankhank10/lawmaker-wiki](https://github.com/hankhank10/lawmaker-wiki)
2. Click the "Fork" button in the top right
3. This creates a copy of the repository in your GitHub account

### 2. Create a Feature Branch

```bash
git clone https://github.com/YOUR_USERNAME/lawmaker-wiki.git
cd lawmaker-wiki
git checkout -b your-feature-branch-name
```

### 3. Make Your Changes

Edit the markdown files in the `docs/` directory:

- Documentation files are in `docs/`
- Main pages are directly in `docs/`
- Gameplay guides are in `docs/gameplay/`
- Country guides are in `docs/countries/`

### 4. Test Locally

Before submitting, test your changes locally:

```bash
# Install dependencies (if not already installed)
pip install -r requirements.txt

# Serve the documentation locally
mkdocs serve

# Open http://127.0.0.1:8000 in your browser
```

This lets you preview your changes and ensure everything looks correct.

### 5. Commit and Push

```bash
git add .
git commit -m "Description of your changes"
git push origin your-feature-branch-name
```

### 6. Submit a Pull Request

1. Go to your forked repository on GitHub
2. Click "New Pull Request"
3. Select your feature branch
4. Add a description of your changes
5. Submit the pull request

## What Can You Contribute?

We welcome contributions in many areas:

### Content Improvements

- **Clarifications** - Make existing content clearer or easier to understand
- **Examples** - Add practical examples to illustrate concepts
- **Corrections** - Fix errors, typos, or outdated information
- **Completeness** - Fill in missing information or expand on brief sections

### New Content

- **Guides** - Write new guides for game features or strategies
- **FAQs** - Add common questions and answers
- **Tips** - Share strategies and best practices
- **Country Guides** - Expand information about specific countries

### Formatting and Structure

- **Organization** - Improve the structure of existing pages
- **Navigation** - Suggest improvements to the menu structure
- **Visuals** - Add diagrams, tables, or formatting improvements

## Documentation Style Guide

### Markdown Formatting

- Use clear headings to organize content
- Use code blocks for examples
- Use lists for step-by-step instructions
- Use tables for structured data

### Admonitions

We use MkDocs admonitions for callouts:

```markdown
!!! tip "Helpful Tip"
This is a helpful tip for players.

!!! warning "Important Warning"
This is an important warning.

!!! success "Success"
This indicates a successful outcome.

!!! info "Information"
This provides additional information.
```

### Links

- Use relative links for internal documentation: `[Getting Started](getting-started.md)`
- Use absolute links for external resources: `[Game Website](https://lawmakergame.com)`
- Link to Discord: `[Discord](https://discord.gg/gKAvGTFKzB)`

### Code Examples

Use code blocks with appropriate syntax:

````markdown
```python
# Example code
def example():
    return "Hello"
```
````

## Testing Your Changes

### Local Testing

Always test locally before submitting:

```bash
mkdocs serve
```

Check for:

- ✅ Markdown renders correctly
- ✅ Links work (both internal and external)
- ✅ Images display properly
- ✅ Tables format correctly
- ✅ Code blocks have proper syntax highlighting
- ✅ Navigation structure makes sense

### Build Testing

Test the full build:

```bash
mkdocs build
```

This creates the `site/` directory with the static site. Check for any build errors or warnings.

## Pull Request Guidelines

### Before Submitting

- [ ] Tested changes locally with `mkdocs serve`
- [ ] Checked for typos and grammar errors
- [ ] Verified all links work correctly
- [ ] Ensured consistent formatting with existing content
- [ ] Added appropriate callouts (tips, warnings, etc.) where relevant

### PR Description

Include in your pull request:

- **What changed** - Brief summary of your changes
- **Why** - Reason for the change (if not obvious)
- **Testing** - How you tested the changes
- **Screenshots** - If you added visual content or made significant layout changes

## Getting Help

If you need help or have questions:

- **Discord** - Join our [Discord server](https://discord.gg/gKAvGTFKzB) to ask questions
- **GitHub Issues** - Open an issue in the repository for bugs or feature requests
- **Pull Request Comments** - Ask questions directly in your pull request

## License

By contributing to the Lawmaker Wiki, you agree that your contributions will be licensed under the MIT License, the same license as the rest of the project.

## Thank You!

Your contributions help make the Lawmaker documentation better for everyone. We appreciate your time and effort!

---

**Questions?** Feel free to reach out on [Discord](https://discord.gg/gKAvGTFKzB) or open an issue in the repository.
