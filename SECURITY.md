# Security policy

Cryptunnel moves money, so we take reports seriously and prefer to hear about a problem from you before anyone else does.

## Reporting a vulnerability

Email [support@cryptunnel.io](mailto:support@cryptunnel.io) with "Security" in the subject. Include what you found, where (host, endpoint, package and version), and the steps to reproduce it. We acknowledge every report and keep you informed while we work on it.

Please do not open a public GitHub issue for a security problem.

## Scope

- `api.cryptunnel.io`, `pay.cryptunnel.io`, `contragent.cryptunnel.io`, `cryptunnel.io`
- The published packages: `cryptunnel` on PyPI and npm, `cryptunnel/cryptunnel` on Packagist, and the repositories in this organization

## Testing

Use the sandbox: create payments with `is_test: true` on your own merchant. Never test against other merchants' payments or wallets, and never attempt to move real funds that are not yours.
