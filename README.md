# Vulnerable-VM
## Overview

This virtual machine is an intentionally insecure Ubuntu 16.04 system designed for hands‑on security practice.
It focuses on realistic misconfigurations, human error, and poor operational habits, rather than artificial vulnerabilities.

The goal is to practice:

- Enumeration

- Credential hygiene failures

- Account lifecycle mistakes

- Secret reuse

- Privilege boundaries

- Realistic attacker reasoning

- Intended Audience

- Beginners learning Linux security fundamentals

- Students practicing local and network enumeration

- Anyone who wants a realistic practice environment instead of puzzle‑style challenges

- No advanced exploitation knowledge is required.

## Rules of Use

1. Only use this VM in an isolated environment

2. Do not expose it to public or production networks

3. Only attack systems you own or have permission to use

This VM is provided for educational purposes only.

## System Details

OS: Ubuntu 16.04 LTS

Architecture: x86_64

Default configuration: intentionally misconfigured

Network: recommended host‑only / isolated

## Accounts

Multiple local users exist on the system.
They reflect different roles and habits, not challenge hints.

Some accounts:

- Reuse credentials

- Contain leftover files

- Were created temporarily and never cleaned up

- Have poor security practices

- You are expected to discover and reason about this, not brute‑force blindly.

## What This VM Is Not

- Not a CTF

- Not a speed‑run challenge

- Not a collection of exploit binaries

- Not a checklist of obvious flags

- If something feels “too easy”, ask why it exists — not how to exploit it.

## Learning Objectives

By working through this VM, you should practice:

- Separating noise from signal

- Identifying human‑caused risk

- Understanding how small mistakes compound

- Thinking like both an attacker and a defender

- Documenting findings clearly

## Suggested Approach

- Observe before acting

- Enumerate carefully

- Take notes

- Question assumptions

- Stop when you understand the full failure chain

- Only then attempt remediation

## Distribution

- This VM is distributed as a disk image (.qcow2) and can be imported into:

- virt‑manager / KVM

- Any hypervisor that supports qcow2

## Download

The practice VM image can be downloaded here:  
[ubuntu16.04.qcow2.xz](https://drive.google.com/file/d/1VvH--ka__rPfl0YOAeq_UsJCAd3wbWSA/view?usp=sharing)



## Legal Notice

This virtual machine is intentionally insecure and provided as‑is for educational purposes.
The author assumes no responsibility for misuse or damage resulting from improper deployment.
