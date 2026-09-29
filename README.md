# Shardflux community

Bug reports, feature requests, and help for [Shardflux](https://shardflux.dev): cloud computers for AI agents.

[Documentation](https://docs.shardflux.dev) · [Report a bug](https://github.com/shardfluxdev/community/issues/new?template=bug_report.yml) · [Request a feature](https://github.com/shardfluxdev/community/issues/new?template=feature_request.yml) · [Get help](SUPPORT.md)

## Packages

| Client | Package | Documentation |
| --- | --- | --- |
| JavaScript / TypeScript SDK | [@shardflux/sdk on npm](https://www.npmjs.com/package/@shardflux/sdk) | [TypeScript reference](https://docs.shardflux.dev/reference/typescript) |
| Python SDK | [shardflux on PyPI](https://pypi.org/project/shardflux/) | [Python reference](https://docs.shardflux.dev/reference/python) |
| Command-line client | [@shardflux/cli on npm](https://www.npmjs.com/package/@shardflux/cli) | [CLI reference](https://docs.shardflux.dev/reference/cli) |
| SDK and CLI bundle | [shardflux on npm](https://www.npmjs.com/package/shardflux) | [Getting started](https://docs.shardflux.dev) |
| MCP server | [@shardflux/mcp on npm](https://www.npmjs.com/package/@shardflux/mcp) | [MCP reference](https://docs.shardflux.dev/reference/mcp) |

One issue tracker covers all clients, the API, cloud workspaces, and documentation. If you cannot tell which part caused a problem, choose **Not sure** in the form and describe what happened.

## Reporting a problem

[Search existing issues](https://github.com/shardfluxdev/community/issues) first. If your problem is already reported, add your reproduction or environment details there. Otherwise, open a bug report with:

- The package name and version, plus your Node.js or Python version and operating system when relevant.
- The smallest example or steps that reproduce the problem.
- What you expected and what actually happened.
- The error code and request ID, if available. Share confidential logs by email instead.

Issues are public. Remove API keys, session tokens, customer data, and confidential code before posting. Send account or billing questions to [shardflux@heliosone.fi](mailto:shardflux@heliosone.fi). Report vulnerabilities through [private security reporting](SECURITY.md).

## Following a fix

New reports start with `needs-triage`. The Shardflux team adds the affected component label and may ask for a reproduction. Confirmed bugs get `confirmed`; a fix awaiting publication gets `awaiting-release`. When a client fix ships, the issue records the package name and published version. Service fixes are identified separately as deployed service changes.

This repository hosts community reports and support documentation. See [contributing](CONTRIBUTING.md) for how to help.
