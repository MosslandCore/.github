# Security Policy

## Scope

This is the default security policy for repositories in the MosslandCore
organization. The organization's repositories are private, but the code in
them runs public Mossland services and products. This document therefore
serves two audiences: external security researchers reporting an issue in a
Mossland service, and internal collaborators who see this file as the
default policy in each private repository's Security tab. Individual
repositories may override this default with a `SECURITY.md` of their own,
and a repository-level policy always takes precedence over this document.

## For external security researchers

If you believe you have found a security issue in a Mossland service or
product, or suspect one in code owned by this organization:

**Do not open a public issue anywhere, and do not disclose publicly before
coordination.**

Email **[contact@moss.land](mailto:contact@moss.land)**, the organization's
published security contact. GitHub's Private Vulnerability Reporting is not
available here because it exists only on public repositories, and this
organization's repositories are private — email is the reporting channel.

A useful report includes:

- the affected service or URL, or the affected product;
- impact and a plausible abuse scenario;
- reproduction steps;
- the environment in which you observed the issue;
- disclosure constraints and credit preference.

What to expect: acknowledgment of your report, private triage, remediation,
and coordinated disclosure where appropriate.

## For internal collaborators

If you suspect a vulnerability in a repository you work on, report it to the
repository maintainers through a private channel, or email
[contact@moss.land](mailto:contact@moss.land).

Do not put exploit detail in issues, even in a private repository — issues
are visible to every collaborator and to installed integrations. Keep
reproduction steps, exploit code, and actionable attack paths out of issues
and pull requests; share them only through the private channel.

Repositories may override this default with their own `SECURITY.md`.
