**27 — Substrate Permissions

Controlled, Authenticated Allowances for System Operation**

Overview

Substrate Permissions define the allowed actions inside the Sovereign Substrate.
They operate alongside Prohibitions and Policies, but serve a different purpose:

Prohibitions → What can never happen

Policies → Rules that must be followed

Permissions → What an actor or system is allowed to do

Permissions are finely granular, identity-bound, and dynamically enforced.
No action can be taken unless explicitly permitted.

27.1 Characteristics of Permissions
1. Identity-Bound

Permissions tie directly to verified identities and roles.

2. Vault-Referenced

Permissions may depend on what data exists, its state, and its integrity.

3. Policy-Governed

Permissions exist within the constraints of Substrate Policies.

4. Deterministic

Permissions always produce the same decision for the same input.

5. Dynamic but Controlled

Permissions can evolve, but only through canonical governance flows.

6. Multi-Layered

Permissions cascade across Identity → Vault → MAIAi → Architect → Execution → ADT → CSR → L8.

27.2 Permission Categories
A. Identity Permissions

Define what an authenticated actor can do.

Examples:

Read vault X

Write to vault Y (policy-bound)

Initiate specific workflows

Approve or deny actions

Modify their ADT (within rules)

B. Vault/Data Permissions

Define how actors and layers may interact with data.

Examples:

Allowed read scopes

Redaction rules

Metadata-only access

Write restrictions

Data lifespan and visibility

C. MAIAi Permissions

Define what MAIAi is allowed to classify or decide.

Examples:

Risk evaluation scopes

Allowed action categories

Context reconstruction boundaries

Ambiguity escalation limits

D. Architect Permissions

Define what the Architect is allowed to authorize.

Examples:

Permitted sequence paths

Allowed enforcement methods

Permitted integration channels

Resource and rate limits

E. Execution (BAINCA) Permissions

Define what computation an actor or system may initiate.

Examples:

Permitted enclave types

Resource allocation limits

Execution time boundaries

Allowed packet categories

F. ADT Permissions

Define what autonomy is allowed to do.

Examples:

Permitted lifecycle scope

Maximum allowed steps

Allowed triggers (time, condition, event)

Retry and failure-handling rules

G. CSR Permissions

Define allowable forms of canonical contribution.

Examples:

Event categories permitted for a given role

Allowed metadata fields

Restrictions on anchoring frequency

Governance update rights

H. Interlinking (L8) Permissions

Define allowable external interactions.

Examples:

Allowed origin systems

API endpoint access

Data egress controls

Permitted request signatures

27.3 Permission Determination Flow

Identity Validation

Vault Context Evaluation

MAIAi Interpretation

Policy Enforcement by Architect

Execution Boundary Check (BAINCA)

Continuity Check (ADT)

Canon Consistency Check

L8 External Permission Check (if applicable)

An action is allowed only if it clears every stage.

27.4 Invalid Permission Conditions

A permission is invalid if:

It introduces nondeterminism

It conflicts with a prohibition

It contradicts CSR history

It bypasses policy or identity constraints

It cannot be enforced by the Architect

It allows ambiguous execution

It permits unsafe autonomy

It exposes sovereign vault data without constraints

Invalid permissions are rejected at issuance.

27.5 Permission Versioning and Change Control

Changes to permissions require:

Identity authentication

Vaulted governance record

MAIAi evaluation

Architect authorization

CSR anchoring

ADT synchronization

Permissions cannot change silently.

27.6 Failure Modes Prevented

Privilege escalation

Unauthorized data access

Rogue compute

Shadow autonomy

Policy misalignment

External exploitation

Drift between identity, policy, and execution

Accidental over-permissioning

27.7 Summary

Substrate Permissions define what actors and systems are explicitly allowed to do — and nothing more.

They ensure that every action is:

Authenticated

Policy-aligned

Deterministic

Contextually grounded

Governed

Canon-consistent

If a behavior is not permitted,
it cannot occur — even if not explicitly prohibited.
