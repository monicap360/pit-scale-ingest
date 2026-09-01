# Security Policy

Do not disclose suspected vulnerabilities through public issues, discussions, pull requests, ingest endpoints, or customer-support channels.

Report concerns privately to **@monicap360** through an authenticated business channel. Include the affected component, minimal reproduction steps, likely impact, and redacted supporting evidence. Never include credentials, customer, driver, vehicle, scale, payment, or location data, or unredacted logs.

Do not test against production in a way that changes ingest records, customer or dispatch data, permissions, credentials, integrations, or deployments.

Security changes must be isolated on a review branch, verified with automated checks, reviewed by the designated code owner, and merged through a protected pull request. Secrets must never be committed, placed in URLs, printed to logs, stored in artifacts, or copied into tickets.
