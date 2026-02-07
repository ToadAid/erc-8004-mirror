# ERC-8004 Overview — Tobyworld Mirror

This document explains how **ERC-8004** is applied to the **Tobyworld Mirror**.

It is written to clarify:
- what ERC-8004 provides
- how the Mirror uses the standard
- what is intentionally excluded

This overview exists to prevent misinterpretation by builders, auditors, and observers.

---

## What ERC-8004 Is

ERC-8004 is a standard for **on-chain agent identity and validation**.

It provides a framework for:
- registering a canonical agent identity
- associating metadata with that identity
- defining ownership and control boundaries
- enabling long-lived discoverability via explorers

ERC-8004 does **not** define:
- agent behavior
- economic models
- governance systems
- incentive structures

Those choices are made by the agent designer.

---

## Why the Mirror Uses ERC-8004

The Tobyworld Mirror uses ERC-8004 to achieve the following:

- **Single Identity**  
  The Mirror must exist as one canonical agent, not as a collection of artifacts.

- **Explicit Ownership**  
  Ownership is assigned to the **ToadAid Safe**, not to individuals or tokens.

- **Verifiable Metadata**  
  Identity and constraints are published via a verifiable `agentURI`.

- **Discoverability Without Promotion**  
  The Mirror can be found and inspected without marketing or claims.

ERC-8004 provides structure without prescribing behavior, which aligns with the Mirror’s design philosophy.

---

## How ERC-8004 Is Applied

For the Tobyworld Mirror, ERC-8004 is used in a minimal and disciplined way:

- One ERC-8004 Agent is registered
- One immutable Agent ID is issued
- One canonical `agentURI` defines:
  - identity
  - constraints
  - ownership
  - references (one-way only)

No additional agent instances are created.

---

## What Is Explicitly Excluded

The following are **out of scope** for ERC-8004 usage in the Mirror:

- Token-based governance
- Yield generation or financial automation
- Market-driven control signals
- Mutable identity via NFTs, coins, or applications
- Delegation of authority to downstream artifacts

ERC-8004 is used for **identity and validation only**.

---

## Relationship to Cultural Artifacts

Cultural or expressive artifacts (e.g. Zora posts or coins) may:

- reference the ERC-8004 Agent ID
- acknowledge the Mirror as their source

They may not:
- modify the Agent
- imply ownership or governance
- redefine constraints
- introduce retroactive authority

All references are one-way.

---

## Authority Model

- **Identity Authority:** ERC-8004 Agent
- **Ownership Authority:** ToadAid Safe
- **Cultural Authority:** None
- **Market Authority:** None

Authority flows outward from the Agent and cannot flow inward.

---

## Final Note

ERC-8004 is used here as a **boundary-setting tool**, not as a feature surface.

> The Mirror does not gain power from ERC-8004.  
> It gains definition.

Clarity, not extensibility, is the goal.
