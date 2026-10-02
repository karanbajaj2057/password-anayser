# Security Policy

## Purpose

PassGuard is an educational defensive-security project focused on password-strength analysis and security awareness.

## Reporting a Security Issue

Please do not publicly post sensitive security findings, credentials, tokens, or private user data in GitHub Issues.

For a suspected vulnerability, contact the repository owner privately and include:

- A clear description of the issue
- Reproduction steps
- Affected component or file
- Security impact
- Suggested remediation, when available

## Secret Handling

Never commit:

```text
.env
.env.*
*.pem
*.key
credentials.*
secrets.*
```

Also never include real passwords, authentication tokens, or API keys in examples.

## Safe Usage

Use only test/demo passwords when recording screenshots or demonstrations. The live project explicitly recommends demo passwords for screenshots. citeturn177074view0
