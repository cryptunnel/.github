# Cryptunnel

Non-custodial crypto payment gateway. Your buyers pay in crypto straight to your own wallets - Cryptunnel never holds the funds. It detects the on-chain transfer, confirms the payment and notifies your system.

[Website](https://cryptunnel.io) · [Documentation](https://docs.cryptunnel.io) · [API reference](https://docs.cryptunnel.io/reference) · [Cabinet](https://contragent.cryptunnel.io)

## Integrate from anything

Every integration is two headers and JSON over HTTPS. The SDKs save you the request building, the error mapping and the two parts people get wrong - webhook verification and polling - but they are an option, not a requirement.

| Path | Start here |
| --- | --- |
| Plain HTTP - any language, any no-code tool | [First payment in 30 minutes](https://docs.cryptunnel.io/docs/getting-started) |
| Python | [`cryptunnel`](https://pypi.org/project/cryptunnel/) on PyPI - [cryptunnel-python](https://github.com/cryptunnel/cryptunnel-python) [![PyPI](https://img.shields.io/pypi/v/cryptunnel)](https://pypi.org/project/cryptunnel/) |
| Node | [`cryptunnel`](https://www.npmjs.com/package/cryptunnel) on npm - [cryptunnel-node](https://github.com/cryptunnel/cryptunnel-node) [![npm](https://img.shields.io/npm/v/cryptunnel)](https://www.npmjs.com/package/cryptunnel) |
| PHP | [`cryptunnel/cryptunnel`](https://packagist.org/packages/cryptunnel/cryptunnel) on Packagist - [cryptunnel-php](https://github.com/cryptunnel/cryptunnel-php) [![Packagist](https://img.shields.io/packagist/v/cryptunnel/cryptunnel)](https://packagist.org/packages/cryptunnel/cryptunnel) |
| Coding agents | [MCP server](https://docs.cryptunnel.io/docs/mcp-server): `claude mcp add --transport http cryptunnel https://api.cryptunnel.io/mcp` |
| Telegram bots | [Telegram bot recipe](https://docs.cryptunnel.io/docs/telegram-bot) for telegraf and aiogram; no-code guides for Bot-T, SaleBot and PuzzleBot |
| No code at all | Payment links and one-off invoices from the cabinet |

Try everything on test networks first - [Sandbox and faucets](https://docs.cryptunnel.io/docs/sandbox) - the sandbox is a flag on the payment, not a second account.

## Support

- Bugs and questions about a package: GitHub Issues in that package's repository
- Everything else: [support@cryptunnel.io](mailto:support@cryptunnel.io) or [@cryptunnel_support_bot](https://t.me/cryptunnel_support_bot) on Telegram
- Security: see [SECURITY.md](https://github.com/cryptunnel/.github/blob/main/SECURITY.md)
