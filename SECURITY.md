# Security Policy

## Supported Versions

Security fixes are applied to `main`, the branch the site is published from.

## Reporting a Vulnerability

Do not use the regular issue tracker. Report vulnerabilities through the
repository's **Security → Report a vulnerability** flow. If that option is
unavailable, email `security@cuesoft.io` with the subject
`Security vulnerability: irealty-proposal`.

Include the impact, affected route or component, reproduction steps, and any
suggested mitigation. Do not include production credentials or client-confidential
material. We aim to acknowledge reports within three business days.

## Secret and Data Handling

- Never commit `.env` files, keys or unpublished client material.
- Use synthetic data in examples and screenshots.
- Rotate a credential immediately if exposure is suspected.
