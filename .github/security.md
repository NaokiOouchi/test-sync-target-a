# Security Guidelines

## Mandatory Checks

- [ ] No hardcoded secrets (API keys, passwords, tokens)
- [ ] All user inputs validated
- [ ] SQL injection prevention (parameterized queries)
- [ ] XSS prevention (sanitized output)
- [ ] CSRF protection enabled
- [ ] Authentication/authorization verified

## Secret Management

- Use environment variables for all secrets
- Never commit secrets to version control
- Rotate secrets regularly
- Use secret scanning tools
