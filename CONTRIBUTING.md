# Contributing to Tiation Headscale Admin

🎉 Thank you for your interest in contributing to Tiation Headscale Admin! We welcome contributions from the community and are excited to work with you to make this project even better.

## 🌟 Code of Conduct

By participating in this project, you are expected to uphold our Code of Conduct. Please report unacceptable behavior to [tiatheone@protonmail.com](mailto:tiatheone@protonmail.com).

## 🚀 Getting Started

### Prerequisites

- **Node.js** 18.0 or higher
- **npm** 8.0 or higher
- **Git**
- **Modern Browser** for testing

### Development Setup

1. **Fork and clone the repository**
   ```bash
   git clone https://github.com/your-username/headscale-admin.git
   cd headscale-admin
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   Navigate to `http://localhost:5173`

## 📋 Development Guidelines

### Code Style

We maintain consistent code style using:
- **ESLint** for code linting
- **Prettier** for code formatting
- **TypeScript** for type safety
- **Svelte/SvelteKit** conventions

Run formatting and linting:
```bash
npm run format
npm run lint
```

### Commit Convention

We use conventional commits for clear, semantic commit messages:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes
- `refactor`: Code refactoring
- `perf`: Performance improvements
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

**Examples:**
```bash
git commit -m "feat(users): add user role management"
git commit -m "fix(api): resolve authentication timeout issue"
git commit -m "docs: update installation instructions"
```

### Branch Naming

Use descriptive branch names with prefixes:
- `feature/description` - New features
- `fix/description` - Bug fixes
- `docs/description` - Documentation updates
- `refactor/description` - Code refactoring

## 🎯 How to Contribute

### 1. Issue Reporting

Before creating an issue, please:
- Search existing issues to avoid duplicates
- Use our issue templates
- Provide clear, detailed descriptions
- Include steps to reproduce (for bugs)
- Add relevant labels

### 2. Feature Requests

When proposing new features:
- Describe the use case and benefit
- Consider existing functionality
- Provide mockups or examples if applicable
- Discuss implementation approach

### 3. Pull Requests

#### Process

1. **Create an issue** first (unless it's a trivial fix)
2. **Fork the repository**
3. **Create a feature branch** from `main`
4. **Make your changes** following our guidelines
5. **Test thoroughly**
6. **Update documentation** if needed
7. **Submit a pull request**

#### PR Requirements

- [ ] **Clear title and description**
- [ ] **Link to related issue**
- [ ] **Tests pass** (`npm test`)
- [ ] **Linting passes** (`npm run lint`)
- [ ] **Build succeeds** (`npm run build`)
- [ ] **Documentation updated** (if applicable)
- [ ] **Screenshots included** (for UI changes)
- [ ] **Mobile responsive** (for frontend changes)

#### PR Template

```markdown
## Description
Brief description of changes

## Related Issue
Fixes #(issue number)

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Testing
- [ ] Tests added/updated
- [ ] Manual testing completed
- [ ] Cross-browser testing (if applicable)

## Screenshots
(Include screenshots for UI changes)

## Checklist
- [ ] Code follows project style guidelines
- [ ] Self-review completed
- [ ] Documentation updated
- [ ] Tests pass
```

## 🏗️ Project Structure

```
src/
├── lib/           # Shared components and utilities
├── routes/        # SvelteKit routes and pages
├── app.html       # App template
├── app.postcss    # Global styles
└── app.d.ts       # App type definitions

docs/              # Documentation files
static/            # Static assets
tests/             # Test files
```

## 🎨 Design Guidelines

### Tiation Design System

- **Colors**: Dark neon theme with cyan (#00FFFF) and magenta (#FF00FF)
- **Typography**: Quicksand for body, Space Grotesk for headings
- **Components**: Skeleton UI framework with custom theming
- **Mobile-first**: Responsive design for all screen sizes

### UI/UX Principles

- **Accessibility**: WCAG 2.1 AA compliance
- **Performance**: Fast loading and smooth interactions
- **Consistency**: Follow established patterns
- **Enterprise-grade**: Professional, polished interface

## 🧪 Testing

### Running Tests

```bash
# Run all tests
npm test

# Run tests in watch mode
npm run test:watch

# Run tests with coverage
npm run test:coverage
```

### Test Types

- **Unit tests**: Component and utility testing
- **Integration tests**: Feature workflow testing
- **E2E tests**: Full application testing

### Writing Tests

- Follow existing test patterns
- Test both success and error cases
- Mock external dependencies
- Use descriptive test names

## 📚 Documentation

### Types of Documentation

- **README**: Project overview and quick start
- **API docs**: Technical API reference
- **User guides**: End-user documentation
- **Developer docs**: Technical implementation details

### Documentation Standards

- Clear, concise writing
- Code examples for complex topics
- Screenshots for UI features
- Keep documentation up-to-date

## 🚢 Release Process

### Versioning

We use [Semantic Versioning](https://semver.org/):
- **MAJOR**: Breaking changes
- **MINOR**: New features (backward compatible)
- **PATCH**: Bug fixes (backward compatible)

### Release Checklist

- [ ] All tests pass
- [ ] Documentation updated
- [ ] Changelog updated
- [ ] Version bumped
- [ ] GitHub release created
- [ ] Deployment verified

## 🆘 Getting Help

### Community Support

- **GitHub Discussions**: General questions and discussions
- **GitHub Issues**: Bug reports and feature requests
- **Documentation**: Comprehensive guides and references

### Enterprise Support

For enterprise customers:
- Priority support channels
- Custom development services
- Training and consultation

Contact: [tiatheone@protonmail.com](mailto:tiatheone@protonmail.com)

## 📄 License

By contributing, you agree that your contributions will be licensed under the MIT License.

## 🙏 Recognition

Contributors will be recognized in:
- README contributor section
- GitHub releases
- Project documentation

Thank you for helping make Tiation Headscale Admin better! 🚀

---

<div align="center">
  <p>
    <strong>Built with ❤️ by the Tiation Team</strong>
  </p>
  <p>
    <a href="https://github.com/tiation">
      <img src="https://img.shields.io/badge/Powered%20by-Tiation-cyan.svg" alt="Powered by Tiation">
    </a>
  </p>
</div>
