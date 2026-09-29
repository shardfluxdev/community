# Contributing

You can help by reporting reproducible bugs, describing a capability you need, improving an existing report, or correcting this repository's support documentation.

Use the [bug report](https://github.com/shardfluxdev/community/issues/new?template=bug_report.yml) and [feature request](https://github.com/shardfluxdev/community/issues/new?template=feature_request.yml) forms. Search existing reports first and keep each issue focused on one problem. Be respectful and describe the behavior you observed.

Pull requests here should change this repository's community documentation or issue forms. Shardflux client and service implementation changes are maintained separately.

## Maintainer workflow

1. Review `needs-triage` reports, assign an owner, and add the component labels: `typescript`, `python`, `cli`, `mcp`, `api`, `dashboard`, or `docs`. Use `needs-information` if a reproduction or version is missing.
2. Link duplicates to the existing report. Add `confirmed` when a bug has been reproduced, then remove `needs-triage`.
3. Keep private implementation details and customer data out of public updates. Summarize progress in the public issue so the reporter can follow it.
4. Mark implemented fixes `awaiting-release` until the relevant package is published or service change is deployed. Include the public issue URL in the affected package's changelog.
5. Close with the actual package name and published version, or identify the deployed service fix and any required client update. Explain closures without a fix.

Handle security reports through [private reporting](SECURITY.md). Direct SDK, CLI, or MCP feedback is private intake; do not copy it into a public issue without the reporter's agreement.
