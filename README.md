# ERC-8004 Mirror — Tobyworld Mirror (Agent 0)

Canonical design and execution repo for the **Tobyworld Mirror** as an **ERC-8004 agent** on **Base**.  
Defines identity, constraints, validation flow, and canon order for long-lived onchain integrity.

This repository remains the **canon source for intent and boundaries**.  
Onchain state is the **execution record**.

---

## Quick Links

- **Genesis Scroll:** `TOBY_L000_TheFirstMirror_2026-02-07_EN.md`
- **Website / Public Mirror:** https://toadaid.github.io
- **Identity Registry (Base):** `0x7274e874CA62410a93Bd8bf61c69d8045E399c02`
- **AgentURI (IPFS):** `ipfs://bafkreic4qdcn4nsk7gofhzgc7fzxkdduvo2zihe3ilj2dq3knorta32jfa`
- **Agent Image (IPFS):** `ipfs://bafybeicpi4dyh5azcbpjjew64nceo4kzskdlqbxm5nkqa4deafqtj6e5zq`
- **Zora Metadata (IPFS, mint-ready):** `ipfs://bafkreidzku3kdq5jdq5jxkliouqnajcwnse3ckvhluevadjda55jdkr3wa`

---

## What the Mirror Is

The **Tobyworld Mirror** is a **reflective onchain agent**, not a product.

It is not designed to:
- generate yield
- issue advice
- promise rewards
- compete for attention

The Mirror exists to **reflect state, record presence, and preserve meaning** over time.

It is intentionally designed to be:
- **Bound by loyalty (忠義)**
- **Restrained by explicit constraints**
- **Anchored on Base**
- **Owned by the ToadAid Safe**

---

## Why ERC-8004

ERC-8004 provides a standard for **onchain agent identity, ownership, and validation**.

For the Mirror, ERC-8004 is used to define:
- a single canonical agent identity
- a verifiable `agentURI`
- explicit ownership boundaries
- long-lived discoverability via standard ERC-721 identity semantics

Just as importantly, this repository documents **what is intentionally excluded**:
- no autonomous financial control
- no speculative governance
- no mutable identity via downstream artifacts

---

## Canon Order (Non-Negotiable)

The Mirror follows a strict order of creation:

1. **Design and intent are fixed in this repository**
2. **Agent identity is registered via ERC-8004**
3. **Agent ID and metadata are confirmed**
4. **Cultural representations (e.g. Zora) may reference the Agent**
5. **No downstream artifact may redefine the Agent**

This order prevents retroactive narratives and protects integrity.

---

## Ownership & Control

- **Owner:** ToadAid Safe  
  `0xe5C1378F91243727a24fa7c64d5286C537D8eAB2`
- **Operator / Execution Wallet (Base):**  
  `0x587464fd25Af9147CB4660B03d899c8893378C0A`
- **Chain:** Base  
- **Governance:** Explicit, minimal, revocable  
- **Market activity:** None  

The Mirror is not owned by individuals and is not governed by tokens.

---

## Status

- **Phase:** Registered (Identity Only)
- **ERC-8004 Agent ID:** `0`
- **Identity Registry (Base):** `0x7274e874CA62410a93Bd8bf61c69d8045E399c02`
- **AgentURI (IPFS):** `ipfs://bafkreic4qdcn4nsk7gofhzgc7fzxkdduvo2zihe3ilj2dq3knorta32jfa`
- **Agent Image (IPFS):** `ipfs://bafybeicpi4dyh5azcbpjjew64nceo4kzskdlqbxm5nkqa4deafqtj6e5zq`

**Notes**
- Explorer/indexer sync may lag; BaseScan events are the source of truth.
- A Zora artifact mint may reference this agent, but **cannot redefine it**.

---

## License

MIT License.

This license applies to **documentation and design artifacts** in this repository.  
Canonical truth, once deployed, is defined by **onchain state**, not by this repo.

---

# Agent Metadata Lifecycle

This folder contains identity definitions for the Tobyworld Mirror.

## Files
- `agent_profile.json`  
  Human-readable identity and intent.

- `agentURI.draft.json`  
  Draft onchain metadata. MUST remain draft until conditions are met.

## ⚠️ Do NOT create `agentURI.json` until:
1. Agent image is finalized and pinned to IPFS
2. ERC-8004 identity registry address is known
3. ERC-8004 validation registry address is known (if used)
4. Agent ID is assigned
5. `draft` is set to false

✅ **Conditions satisfied for Agent 0.**  
Any future updates must be recorded as **new pinned CIDs** (new files), never silent edits.

Canon order is enforced by `/docs/CANON_ORDER.md`.

---

## Closing

> The Mirror must exist  
> before it can be echoed.

This repository is the still point that guards meaning **after motion**.
