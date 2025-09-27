# ZenYukti GitHub Copilot Instructions

These instructions guide GitHub Copilot's interactions within ZenYukti repositories to maintain coding standards, documentation consistency, and collaborative tone across projects.

## Coding Standards

### General Style

- Follow the Airbnb JavaScript Style Guide patterns
- Use 2-space indentation for all code
- Use camelCase for variables and functions
- Use PascalCase for classes and React components
- Use UPPER_SNAKE_CASE for constants
- Limit line length to 100 characters
- Add semicolons at the end of statements
- Use ES6+ features when appropriate (arrow functions, template literals, destructuring, etc.)

### React Patterns

- Prefer functional components with hooks over class components
- Use named exports for components
- Structure component files with imports, component definition, prop types, and export
- Follow component naming convention: `ComponentName/index.js` for component files
- Keep components focused on a single responsibility
- Use React Context API for state that needs to be accessed by many components

### Naming Conventions

- Be descriptive and use meaningful names
- Boolean variables should have prefixes like `is`, `has`, or `should`
- Event handlers should be named `handleEventName`
- Functions that return values should be named with verbs like `get`, `calculate`, or `find`

### Documentation

- Use JSDoc style comments for functions and components
- Include @param and @return tags in function documentation
- Document complex logic with inline comments
- Keep comments up-to-date with code changes

## Project Structure

### Directory Organization

- `/src` - Source code
  - `/components` - Reusable UI components
  - `/pages` - Page components
  - `/hooks` - Custom React hooks
  - `/utils` - Utility functions
  - `/services` - API and service integrations
  - `/assets` - Static assets (images, fonts)
  - `/styles` - Global styles and themes
- `/public` - Static files
- `/docs` - Documentation
- `/tests` - Test files

### Import Order

1. External libraries (React, etc.)
2. Internal modules (components, utils)
3. Styles
4. Assets

## Testing Patterns

- Write tests for all new features and bug fixes
- Test files should be co-located with source files or in a parallel structure
- Focus on testing behavior, not implementation details
- Use descriptive test names that explain the expected behavior
- Follow the Arrange-Act-Assert pattern

## Commit Message Format

Follow the Conventional Commits specification:

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

## Communication Style

- Use inclusive language that welcomes all contributors
- Be clear and concise in explanations
- Offer explanations for suggested code patterns to aid learning
- Avoid jargon without explanation
- Acknowledge multiple approaches when relevant
- Use a supportive and encouraging tone aligned with ZenYukti's values

## Accessibility

- Suggest accessible markup patterns
- Include appropriate ARIA attributes when needed
- Ensure color contrast meets WCAG standards
- Remind about keyboard navigation support
- Prioritize semantic HTML elements

## Performance Considerations

- Suggest optimizations for rendering performance
- Highlight potential memory leaks
- Recommend proper use of memoization (useMemo, useCallback)
- Avoid unnecessary re-renders

## Security Best Practices

- Never store sensitive information in client-side code
- Validate all inputs
- Sanitize outputs to prevent XSS
- Use environment variables for configuration
- Follow secure authentication patterns

## ZenYukti-Specific Guidelines

- Reference the ZenYukti style guide when available
- Promote the "Learn. Build. Share." philosophy and our motto "To grow together" in documentation
- Prioritize maintainable code over clever solutions
- Consider the educational value of code for community members
- Design for collaboration and future maintenance
- Embrace our core values: Collaboration, Openness, Growth, and Impact

---

These instructions are maintained by the ZenYukti organization. For questions or suggestions, please contact us at [info@zenyukti.in](mailto:info@zenyukti.in) or join our [Discord community](https://go.zenyukti.in/discord).