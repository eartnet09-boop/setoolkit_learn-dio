# SEToolkit Phishing Lab

> [!IMPORTANT]
> This repository documents a controlled cybersecurity lab exercise using the Social-Engineer Toolkit (SET) in an isolated, authorized environment. The content is for academic study only and must not be used against systems or people without explicit written authorization.
>
> See [ETHICS.md](ETHICS.md) for the full ethical use statement and legal boundaries.

## Overview

This project is a professional academic report on a laboratory exercise involving the Social-Engineer Toolkit (SET). The purpose is to explain the role of the tool in a red-team or awareness exercise, document the lab environment, and show how the tool sits within the early stages of a real-world attack chain.

The workflow is intentionally presented at a high level and is restricted to documentation and report writing. The repository does not include ready-to-use phishing pages, payloads, or attack automation.

## Contents

- [ETHICS.md](ETHICS.md) — ethical use statement and boundaries
- [docs/setoolkit-overview.md](docs/setoolkit-overview.md) — overview of SEToolkit, modules, and relevant lab context
- [docs/lab-setup.md](docs/lab-setup.md) — local network and isolated environment requirements
- [docs/lab-walkthrough.md](docs/lab-walkthrough.md) — screenshot placeholders and walkthrough structure
- [docs/c2-frameworks-comparison.md](docs/c2-frameworks-comparison.md) — concise comparison with major C2 platforms
- [screenshots/README.md](screenshots/README.md) — screenshot naming convention and placeholders

## SEToolkit in context

The Social-Engineer Toolkit is designed to support social-engineering and phishing-oriented attack vectors in a controlled lab. It is relevant for demonstrating concepts around the initial access stage, credential harvesting, and site cloning in a local environment. The tool is not a full command-and-control framework; it operates at the front end of the attack chain, where the defender or student studies how an attacker would establish the first interaction and gather the first credentials or foothold.

## Comparison with C2 frameworks

SEToolkit and C2 frameworks are not equivalent. SET focuses on the early user-facing deception stage, whereas C2 frameworks such as Mythic, Sliver, Havoc, and Cobalt Strike are oriented toward post-compromise persistence, command execution, and long-running operational control. The comparison in this repository is conceptual and limited to a technical report, not operational guidance.

## Scope and restrictions

This repository is documentation only. It intentionally avoids:

- phishing texts or persuasive social-engineering scripts
- real target data or credential captures
- executable attack payloads or malicious HTML templates
- operational installation or post-exploitation instructions

For all screenshots and examples, the student must replace the placeholders with evidence collected only from a controlled, authorized laboratory environment.
