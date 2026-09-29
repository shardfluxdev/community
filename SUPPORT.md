# Getting help

| What you need | Where to go |
| --- | --- |
| Installation, examples, and API reference | [Shardflux documentation](https://docs.shardflux.dev) |
| A reproducible bug or incorrect documentation | [Report a bug](https://github.com/shardfluxdev/community/issues/new?template=bug_report.yml) |
| A missing capability or product idea | [Request a feature](https://github.com/shardfluxdev/community/issues/new?template=feature_request.yml) |
| Usage questions, account access, billing, or confidential details | [Email the Shardflux team](mailto:shardflux@heliosone.fi) |
| A security vulnerability | [Report it privately](SECURITY.md) |

You can open a GitHub report without a Shardflux account or API key. If installation or authentication fails, use the public bug form or email; you do not need a working client to report it.

## Feedback while you work

The clients also provide direct feedback to the Shardflux team:

- CLI 0.5.0+: `shard feedback --category bug "what happened and what you expected"`
- TypeScript SDK 0.9.0+: `cloud.sendFeedback({ message: 'what happened and what you expected', category: 'bug' })`
- Python SDK 0.5.0+: `sf.send_feedback('what happened and what you expected', category='bug')`
- MCP server 0.4.0+: the `send_feedback` tool.

These send direct feedback; they do not create a public GitHub issue. Use GitHub when you want a public discussion and a report you can follow. Include an existing issue URL in direct feedback if the reports concern the same problem.

Keep reports short and specific. Include the package version, error code, and request ID when available. Never send API keys, session tokens, or passwords. If a reproduction contains confidential data, use a small sanitized example or contact the team by email.

## Resolution

For a client bug, the closing update names the fixed package and its published version so you know what to install. For a service bug, it says that the service fix has been deployed and whether a client update is needed. A fix that is only committed stays open with `awaiting-release`.

Duplicate reports link to the original issue. A report closed without a fix includes the reason or workaround.
