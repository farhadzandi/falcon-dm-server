# Security Policy

## Public repository boundary

This repository is a public distribution/update channel. It must contain only information that is safe to disclose publicly.

Do not commit:

- real license keys or activation records;
- personal or customer email addresses;
- passwords, API keys, access tokens, or private keys;
- customer financial or identity data;
- production secrets or internal infrastructure credentials.

Use synthetic demo values for examples and tests.

## Accidental disclosure

If sensitive information is committed:

1. remove it from the current branch immediately;
2. rotate or invalidate the exposed credential/license;
3. review Git history because deleting the current value does not remove prior commits;
4. rewrite history when appropriate and re-check the repository.

## Reporting

For security issues, contact the maintainer privately rather than opening a public issue containing sensitive details.
