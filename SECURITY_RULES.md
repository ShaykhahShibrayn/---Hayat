# SECURITY_RULES.md

## Security Rules

- Never expose secrets, passwords, or API keys in the source code.
- Never hardcode API keys or sensitive credentials.
- Store sensitive information using environment variables (.env).
- Validate all user inputs before processing.
- Sanitize all user inputs to prevent malicious data.
- Encrypt user passwords using a secure hashing algorithm (e.g., bcrypt).
- Enforce strong passwords with a minimum length of 8 characters.
- Ensure each username is unique before creating an account.
- Verify the user's phone number before activating the account.
- Apply authentication and role-based authorization for protected resources.
- Protect sensitive user information and personal data.
- Use HTTPS for secure communication in production.
- Handle errors securely without exposing internal system details.
- Keep dependencies updated to reduce security vulnerabilities.