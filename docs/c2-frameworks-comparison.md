# C2 Frameworks Comparison

This document provides a high-level comparison between the Social-Engineer Toolkit (SET) and current command-and-control (C2) frameworks. The purpose is to contextualize the role of SET within a realistic attack chain without crossing into operational abuse or step-by-step attack guidance.

## Why this comparison matters

SEToolkit is focused on the initial access stage: it helps deliver a lure, present a trusted-looking interface, and capture the first meaningful credential or interaction. In contrast, C2 frameworks are designed to maintain remote control over an already compromised endpoint. They work after the initial foothold has been established and are typically associated with post-exploitation workflows such as command execution, pivoting, stealth, persistence, and long-running remote operations.

This means the tools are complementary rather than direct competitors. SET is best understood as the first-phase vector; C2 frameworks are the infrastructure used after the first foothold is achieved.

## Comparative overview

| Tool | Type | License | Main strengths | Typical observation |
| --- | --- | --- | --- | --- |
| SEToolkit | Social-engineering toolkit (phishing, site cloning, credential capture) | Open source (BSD) | Straightforward, educational, focused on the initial access stage and user interaction | Not a full C2 framework; it is used to establish the first contact or credential capture vector |
| Metasploit Framework | Exploitation and post-exploitation | Open source (with paid Pro edition) | Large public exploit base, strong documentation, accessible to beginners | Often described as a natural next step after a lab introduction to SET |
| Sliver | C2 framework | Open source | Lightweight, cross-platform, fast setup, useful for pivoting and SOCKS5-style movement | Gained adoption after attention to C2 infrastructure alternatives |
| Havoc | C2 framework | Open source (Go) | Modern development cycle, good evasion discussion in recent threat reports, lightweight payloads | Smaller ecosystem than some more mature C2 suites |
| Mythic | Multi-agent C2 platform | Open source | Strong collaboration features, long-running operations, support for multiple agents | More complex to deploy than some smaller alternatives |
| Brute Ratel C4 | C2 framework | Commercial | Strong "off-the-shelf" evasion profile, heavily discussed in advanced threat reporting | Paid, restricted licensing, not a general-purpose lab tool |
| Cobalt Strike | Commercial C2 framework | Commercial | Mature, well-documented, widely recognized as a market standard | Highly visible in adversary emulation and EDR discussions |

## Framing for the lab report

In a real-world engagement, the path often looks like this: an attacker triggers an initial interaction using social engineering, then follows up with a foothold and later transitions into post-exploitation tooling. SEToolkit sits at the front of that chain; C2 frameworks sit after it. This distinction is important for both technical literacy and ethical framing.

The student repository should therefore present SET as the demonstrative tool for the early stage of the attack chain and C2 frameworks as examples of the infrastructure used after a first-stage compromise. This keeps the report technically accurate, ethically responsible, and consistent with a defensive or academic understanding of cyber operations.

## Scope note

This comparison is intentionally general and non-operational. It does not provide installation commands, C2 listeners, payload generation, or evasion guidance. The aim is to emphasize conceptual differences and the educational role of the tools in a security laboratory.
