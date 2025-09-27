# Contributing to ZenYukti

🎉 First off, thank you for considering contributing to ZenYukti! 🎉

ZenYukti is a community-driven innovation hub built on the values of collaboration, learning, and growth. We bring together creators, developers, and innovators to Learn, Build, Share, and grow as professionals while uplifting one another. We welcome contributions of all kinds, from bug fixes and feature implementations to documentation improvements and design suggestions.

This document outlines how to get started as a contributor, our development workflows, coding standards, and communication channels. By following these guidelines, you'll help us maintain a high-quality, consistent codebase and ensure a smooth contribution process.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Community Engagement Tiers](#community-engagement-tiers)
- [Getting Started](#getting-started)
  - [Setting Up Your Development Environment](#setting-up-your-development-environment)
  - [Finding Issues to Work On](#finding-issues-to-work-on)
- [Development Workflow](#development-workflow)
  - [Branching Strategy](#branching-strategy)
  - [Commit Message Guidelines](#commit-message-guidelines)
  - [Pull Request Process](#pull-request-process)
  - [Code Review Process](#code-review-process)
- [Coding Standards](#coding-standards)
  - [General Guidelines](#general-guidelines)
  - [Language-Specific Guidelines](#language-specific-guidelines)
  - [Testing Requirements](#testing-requirements)
  - [Documentation Guidelines](#documentation-guidelines)
- [Communication Channels](#communication-channels)
- [Recognition and Rewards](#recognition-and-rewards)
- [License](#license)

## Code of Conduct

We are committed to providing a welcoming and inclusive experience for everyone. Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before participating in the ZenYukti community.

## Community Engagement Tiers

ZenYukti has three engagement tiers for community members:

1. **Members**: Anyone who uses ZenYukti projects, files issues, or participates in discussions.
2. **Active Contributors**: Regular contributors who submit PRs, provide reviews, improve documentation, or actively participate in community discussions.
3. **Mentors**: Experienced contributors who guide the community, review PRs, and help shape project direction.

We encourage progression through these tiers as you become more familiar with the project and community.

## Getting Started

### Setting Up Your Development Environment

1. **Fork the Repository**
   - Visit the [ZenYukti GitHub organization](https://github.com/ZenYukti) and fork the repository you want to contribute to.

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
   cd REPOSITORY-NAME
   ```

3. **Add Upstream Remote**
   ```bash
   git remote add upstream https://github.com/ZenYukti/REPOSITORY-NAME.git
   ```

4. **Install Dependencies**
   ```bash
   # For frontend projects (React + Vite)
   npm install
   ```

5. **Start Development Server**
   ```bash
   # For frontend projects (React + Vite)
   npm run dev
   ```
   
   The development server will start, and you can access the site at `http://localhost:3000` or the port specified in the console.

### Finding Issues to Work On

- For website contributions, check the [Issues](https://github.com/ZenYukti/zenyukti.github.io/issues) tab on GitHub.
- Look for issues labeled `good first issue` if you're new to the project.
- Feel free to ask questions on our [Discord server](https://go.zenyukti.in/discord) if you need help finding a suitable issue.
- Join the "Contributors" channel on Discord to connect with other contributors.

## Development Workflow

### Branching Strategy

- `main` - Production-ready code
- `develop` - Development branch (default branch for PRs)
- Feature branches - Created from `develop` branch

When working on an issue, create a branch with a descriptive name:
```bash
git checkout develop
git pull upstream develop
git checkout -b feature/add-login-component
# or
git checkout -b fix/navigation-menu-mobile
```

### Commit Message Guidelines

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

Types:
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, semicolons, etc)
- `refactor`: Code changes that neither fix a bug nor add a feature
- `perf`: Performance improvements
- `test`: Adding or fixing tests
- `chore`: Changes to build process or auxiliary tools

Example:
```
feat(auth): implement social login with Google

Added OAuth integration with Google for seamless login experience.

Closes #123
```

### Pull Request Process

1. **Update Your Fork**
   ```bash
   git checkout develop
   git pull upstream develop
   ```

2. **Create Your Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Changes and Commit**
   ```bash
   git add .
   git commit -m "feat: add your feature description"
   ```

4. **Push to Your Fork**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Create a Pull Request**
   - Go to the original ZenYukti repository
   - Click "New Pull Request"
   - Select "Compare across forks"
   - Select your fork and branch
   - Fill out the PR template with all required information

6. **Address Review Feedback**
   - Make requested changes
   - Push additional commits to your branch
   - The PR will update automatically

### Code Review Process

All contributions undergo review before being merged:

1. Automated checks must pass (tests, linting, etc.)
2. At least one approval from a maintainer or mentor is required
3. Address all review comments and resolve discussions
4. Wait for final approval and merge

## Coding Standards

### General Guidelines

- Write clean, readable, and maintainable code
- Follow the principle of DRY (Don't Repeat Yourself)
- Use meaningful variable and function names
- Add comments for complex logic, but prefer self-documenting code

### Language-Specific Guidelines

**JavaScript/TypeScript:**
- Follow [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- Use ES6+ features appropriately
- Prefer functional programming patterns when suitable
- Use TypeScript type annotations properly

**React:**
- Use functional components and hooks
- Follow the [React Best Practices](https://react.dev/learn/thinking-in-react)
- Keep components small and focused on a single responsibility
- Use proper component composition
- For our website project (built with React + Vite), follow the project structure and component patterns established in the codebase

**CSS/SCSS:**
- Follow BEM (Block Element Modifier) naming convention
- Use variables for colors, fonts, and other repeated values
- Design with responsiveness in mind

### Testing Requirements

- Write tests for all new features and bug fixes
- Aim for high test coverage, especially for critical paths
- Use Jest for unit tests and React Testing Library for component tests
- Write both unit and integration tests when appropriate

### Documentation Guidelines

- Keep README files up-to-date
- Document complex functions and components with JSDoc comments
- Create or update API documentation when changing interfaces
- Add usage examples for new features

## Communication Channels

- [GitHub Discussions](https://github.com/ZenYukti/discussions) - For feature discussions and community questions
- [Discord Server](https://go.zenyukti.in/discord) - For real-time communication
- [WhatsApp Community](https://go.zenyukti.in/whatsapp) - For updates and community interaction
- [ZenYukti Website](https://zenyukti.in) - For general information and resources
- [LinkedIn](https://linkedin.com/company/zenyukti) - For professional updates
- [X (Twitter)](https://x.com/zenyukti) - For announcements and updates
- [Instagram](https://instagram.com/zenyukti) - For community highlights and visual content
- [Commudle](https://www.commudle.com/communities/zenyukti) - For events and community engagement
- Email: [info@zenyukti.in](mailto:info@zenyukti.in)

## Recognition and Rewards

We recognize contributors in several ways:

- Acknowledgment in release notes
- Featured on our contributors page
- Opportunities to become mentors or maintainers
- Invitations to special community events
- Digital badges and certificates for significant contributions

## License

By contributing to ZenYukti, you agree that your contributions will be licensed under the same license as the project you're contributing to. Most ZenYukti projects use the [MIT License](../LICENSE).

---

Thank you for contributing to ZenYukti! Together, we can build an amazing community that embodies our mission: "Learn. Build. Share."