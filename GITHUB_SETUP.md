# GitHub Setup — PassGuard

## Repository name

```text
passguard-password-strength-analyzer
```

## GitHub description

```text
Privacy-focused password strength analyzer with entropy estimation, pattern detection, crack-time estimation, passphrase generation, and local security guidance.
```

## Suggested GitHub topics

```text
cybersecurity
password-security
password-analyzer
security-tool
information-security
ethical-hacking
infosec
web-security
privacy
entropy
defensive-security
password-strength
passphrase-generator
```

## Upload an existing local project

From the root directory of your downloaded/exported project:

```bash
git init
git add .
git commit -m "feat: initial PassGuard password security analyzer"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/passguard-password-strength-analyzer.git
git push -u origin main
```

## If the GitHub repository already exists

```bash
git remote -v
git branch -M main
git push -u origin main
```

## Recommended release tag

```bash
git tag -a v1.0.0 -m "PassGuard v1.0.0"
git push origin v1.0.0
```

## Before pushing

Check that you are NOT committing:

```text
.env
API keys
access tokens
real passwords
private credentials
```

Review the files first:

```bash
git status
git diff --cached
```
