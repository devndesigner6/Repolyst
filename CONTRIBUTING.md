# Contributing to Repolyst

Thank you for your interest in contributing to Repolyst! 🎉

## 🚀 Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/Repolyst.git`
3. Create a feature branch: `git checkout -b feature/your-feature-name`
4. Make your changes
5. Commit with clear messages: `git commit -m "feat: add new feature"`
6. Push to your fork: `git push origin feature/your-feature-name`
7. Open a Pull Request

## 📝 Commit Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` - New feature
- `fix:` - Bug fix
- `docs:` - Documentation changes
- `style:` - Code style changes (formatting, no logic change)
- `refactor:` - Code refactoring
- `test:` - Adding or updating tests
- `chore:` - Maintenance tasks

**Examples:**
```
feat: add export to PDF functionality
fix: resolve memory leak in file tree component
docs: update installation instructions
```

## 🛠️ Development Setup

```bash
# Install dependencies
pnpm install

# Copy environment variables
cp .env.example .env.local

# Add your API keys to .env.local
# GITHUB_TOKEN=your_token
# OPENROUTER_API_KEY=your_key

# Start development server
pnpm dev
```

## ✅ Before Submitting

- [ ] Code follows the existing style
- [ ] No console errors or warnings
- [ ] Tested locally with `pnpm dev`
- [ ] Updated documentation if needed
- [ ] Commit messages follow convention

## 🐛 Reporting Bugs

Open an issue with:
- Clear title and description
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable
- Environment details (browser, OS)

## 💡 Feature Requests

We welcome new ideas! Open an issue describing:
- The problem you're trying to solve
- Your proposed solution
- Any alternative solutions considered

## 📜 Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Focus on what's best for the project

## 🙏 Thank You!

Every contribution, no matter how small, helps make Repolyst better for everyone.
