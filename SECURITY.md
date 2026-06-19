# Security Policy

This repository contains the **static landing page** for Vexor
(https://vexormon.com). It has no backend, accounts, or user data.

## Supported versions

Only the current `main` HEAD (what is deployed at vexormon.com) is supported.

## Reporting a vulnerability

**Do not file public GitHub issues for security problems.**

Report privately by one of these channels:

1. **GitHub Security Advisory** — use the **Security** tab → *Report a
   vulnerability* on this repository (private to maintainers).
2. **Email** — `security@vexor.local`.

Include the commit / URL, a description of the issue and impact, and
reproduction steps or a PoC if possible.

We aim to **acknowledge** reports within **3 business days** and to fix or
mitigate confirmed issues affecting the deployed site promptly.

## Scope

In scope: code and configuration in this repository (HTML/CSS/assets) and
anything here that could lead to content injection or redirect on
vexormon.com.

Out of scope: findings against the separate Vexor application/demo (report
those on the `vexor-monitoring` repository), and purely informational
findings with no demonstrable impact.
