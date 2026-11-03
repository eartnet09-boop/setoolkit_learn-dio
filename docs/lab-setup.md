# Laboratory Setup Guide

This project is a documentation exercise conducted in a controlled environment. The setup below is intended for academic use only and must remain isolated from any public or production network.

## Recommended topology

Use a small local lab topology such as the following:

- One Kali Linux VM running the Social-Engineer Toolkit.
- One target VM or host that acts as the user endpoint in the lab.
- A local-only network, NAT, or isolated virtual switch.
- No direct exposure to the internet.

The VM environment should be designed to prevent accidental leakage of traffic to external systems. This means the lab network must be private, static, and limited to the authorized machines used for the exercise.

## Minimum requirements

- Kali Linux with SET installed or preloaded.
- One target machine or fictitious test user account.
- A local DNS and network configuration that does not route to the public internet.
- Administrative access to the lab environment only.
- A written authorization from the instructor or lab coordinator for the exercise.

## Handling the environment safely

The purpose of the lab is to demonstrate a social-engineering workflow in a controlled setting, not to simulate or perform real attacks outside the authorized scope. All communications, captures, and artifacts must remain inside the isolated lab network.

Before starting, verify the following:

- The lab VM has no outbound connectivity beyond the local lab network.
- No real credentials or personal data are present in the environment.
- Any cloned content or page replication is limited to test assets created for the exercise.
- All screenshots and notes are kept within the repository and not shared publicly.

## Operational note

This repository intentionally avoids operational or persuasive instructions. It documents the environment, framework, and workflow at a high level so that the academic exercise remains professional and defensible.

The key principle is simple: the lab is an authorized demonstration, executed in a local and isolated setup, with all actions restricted to the controlled environment and the proof of work recorded in screenshots or notes produced by the student.
