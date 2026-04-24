# Security Policy

## Scope

This repository is the public entry point for WorldLines: installation
entry points, public documentation, and the `stoneford-worldlines`
template submodule.

If you find a security issue in any of the following, please report it
privately:

- installer scripts and launcher entry points
- release/download links and update instructions
- documentation that could cause unsafe setup or secret exposure
- submodule wiring, packaging, or public release artifacts

If the report involves the underlying `neonrp` engine as well, still use
the process below and note the affected component.

## Supported Versions

| Version | Supported |
|---|---|
| `v0.1.x` | Yes |
| older preview builds | Best effort |

## Reporting a Vulnerability

Please do **not** open a public GitHub issue for suspected security
problems.

Instead, email `info@worldlines.gg` with:

- a short summary of the issue
- affected repository, file, tag, or release artifact
- reproduction steps or proof of concept
- impact assessment, if known
- whether you would like public credit after a fix

Use a subject line such as:

`[SECURITY][WorldLines] short description`

## Response Expectations

- Initial acknowledgement target: within 5 business days
- Status update target: within 10 business days
- Fix timing: depends on severity, exploitability, and release cadence

We may ask follow-up questions, coordinate a fix window, and request that
details remain private until users can reasonably protect themselves.

## Disclosure

After a fix is available, we may disclose the issue in release notes or a
security advisory. If you want attribution, let us know in the initial
report.
