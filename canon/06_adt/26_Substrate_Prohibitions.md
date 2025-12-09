**26 — Substrate Prohibitions

Actions and States That Are Never Permitted in the Sovereign Substrate**

Overview

Substrate Prohibitions define the absolute boundaries of the authenticated internet — the actions, conditions, or system states that can never occur, regardless of identity, role, or intent.

These are not policies (which may change)
and not consequences (which respond to violations).
Prohibitions are hard constraints, enforced as part of the substrate’s core logic and invariants.

If an operation violates a prohibition, it cannot execute — the substrate blocks it before it begins.

26.1 Characteristics of Substrate Prohibitions
1. Absolute

No exceptions. No overrides. No conditional approval.

2. Non-negotiable

Cannot be relaxed through policy or configuration.

3. Pre-Execution

Prohibited actions never enter the event pipeline.

4. Canon-Enforced

All layers enforce prohibitions together.

5. Immutable

Prohibitions cannot be altered after definition.

26.2 Prohibited Identity States

The substrate forbids:

Unauthenticated or pseudonymous actors

Identity spoofing attempts

Role changes mid-sequence

Credential injection or substitution

Multi-actor masquerade

Identity is the bedrock — anything that threatens it is disallowed.

26.3 Prohibited Vault/Data Behaviors

Forbidden under all conditions:

Storing unverified or unauthenticated data

Exposing data without policy constraints

Altering vault state outside the canonical sequence

Direct raw data export

Creating shadow data copies

Mutating data without integrity signatures

Vaults must remain sovereign.

26.4 Prohibited MAIAi Behaviors

MAIAi cannot:

Reason without grounding

Accept incomplete or contradictory context

Execute ungoverned autonomy

Produce nondeterministic outputs

Override policy or identity constraints

Generate or act on hallucinated data

Intelligence must remain authenticated.

26.5 Prohibited Architect Actions

The Architect is forbidden from:

Skipping sequence steps

Approving conflicting policies

Authorizing execution without identity

Allowing unbounded workflows

Overriding vault or CSR truth

Governance must remain deterministic and sovereign.

26.6 Prohibited Execution (BAINCA) States

Execution cannot:

Run without an approved packet

Produce nondeterministic results

Access external resources without L8

Continue after anomaly detection

Launch enclaves with inconsistent inputs

Execute privileged operations without policy

Computation must be verifiable and bounded.

26.7 Prohibited ADT Behaviors

Autonomy is forbidden from:

Acting without fresh canonical context

Running loops or recursions beyond allowed scope

Creating self-modifying logic

Changing its own permissions

Continuing after violation or correction triggers

Autonomy must remain contained and governed.

26.8 Prohibited CSR States

History cannot:

Fork

Reorder

Be rewritten

Omit required events

Include unsigned or unverifiable entries

Contain contradictory events

The Canon must remain the single source of truth.

26.9 Prohibited Interlinking (L8) Behaviors

The substrate disallows:

Accepting unverified external requests

Exposing vault data to external systems

Allowing protocol downgrade

Accepting unsigned or malformed payloads

Permitting egress without explicit policy

Allowing external override attempts

External interactions must remain fully authenticated.

26.10 Prohibited System Conditions

The entire substrate forbids:

Ambiguity

Nondeterminism

Drift between layers

Partial rollback

Shadow execution paths

Silent failures

Any state lacking complete provenance

Time-order contradictions

Unbounded operations

These are the conditions most likely to cause collapse.

26.11 Failure Modes Prevented

By enforcing prohibitions, the substrate prevents:

Catastrophic inconsistencies

Rogue AI behavior

External takeover

State corruption

User data exposure

Policy circumvention

Execution hijacking

Event forgery

Timeline manipulation

26.12 Summary

Substrate Prohibitions define the non-negotiable limits of the authenticated internet.
They ensure that no actor — human, AI, subsystem, or external integration — can push the system into dangerous, ambiguous, or unverifiable states.

These are the walls of the sovereign framework.
If something is prohibited, it simply cannot happen.
