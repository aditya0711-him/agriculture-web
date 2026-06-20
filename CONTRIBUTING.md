# Contributing to Agriculture Web

Thank you for your interest in contributing to this project! Please follow these guidelines.

## Code of Conduct

Be respectful and professional in all interactions.

## Development Workflow

### Branching Strategy

- **main**: Production-ready code (stable releases)
- **develop**: Development branch (integration point)
- **feature/**: New features (branch from develop)
- **bugfix/**: Bug fixes (branch from develop)
- **hotfix/**: Urgent fixes for production (branch from main)

### Creating a Feature Branch

```bash
git checkout develop
git pull origin develop
git checkout -b feature/your-feature-name
```

### Commit Messages

Follow this format:
```
[TYPE] Brief description

Detailed explanation (if needed)

Fixes #issue_number
```

Types: feat, fix, docs, style, refactor, test, chore

### Pull Request Process

1. Ensure all tests pass
2. Update documentation
3. Create PR with clear description
4. Link related issues
5. Wait for code review
6. Address feedback and re-request review

## Code Style

### Frontend
- Use consistent indentation (2 spaces)
- Follow ES6+ standards
- Use meaningful variable names
- Add comments for complex logic

### Backend
- Follow PEP 8 (Python) or Node.js conventions
- Use type hints where applicable
- Write unit tests for new features
- Document API endpoints

## Testing

All new code should include tests:

```bash
# Run tests
npm test          # Frontend
pytest            # Backend
```

## Documentation

- Update README.md if adding features
- Add comments to complex code
- Keep API documentation current

## Getting Help

- Check existing issues and PRs
- Ask questions in issue discussions
- Contact the maintainers

Thank you for contributing! 🌾
