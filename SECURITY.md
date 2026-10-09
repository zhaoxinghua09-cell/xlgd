# Security Policy

## Reporting a vulnerability

Please report suspected security issues **privately** — do not open a public
issue. Use GitHub's private vulnerability reporting on the affected repository
(Security → Report a vulnerability), or email **zhaoxinghua09@gmail.com**.

Include: what you found, where (repository + path), how to reproduce it, and
what impact you believe it has. We will acknowledge receipt and keep you
informed of the resolution.

## Scope

This umbrella repository contains documentation and index metadata only. Its
security surface is small; the executable surface lives in the layer
repositories it points to. Report issues against the repository where the code
actually is:

| Layer | Repository |
|---|---|
| Protocol (reference implementation) | `zhaoxinghua09-cell/uibc-core` |
| Verifier side | `zhaoxinghua09-cell/silent-failure-catalog` |
| Agent skills | `zhaoxinghua09-cell/agent-skills` |

## Supported versions

The project is pre-1.0 and evolving. The tip of the default branch is what is
supported; there are no maintained back-branches yet. Reports against any
tagged release are still welcome.
