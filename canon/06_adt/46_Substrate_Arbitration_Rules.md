**46 — Substrate Arbitration Rules

How the Substrate Chooses Among Multiple Valid Paths**

Overview

Arbitration Rules define how the Sovereign Substrate selects one path when more than one option is:

valid

safe

policy-aligned

deterministic

sovereign

canonical

Arbitration occurs only when every available option is legitimate, and the decision is about which preferred path to take — not which path is safe.

Arbitration ensures forward progress without ambiguity.

46.1 When Arbitration Is Used

Arbitration triggers when:

two governance policies both allow a workflow

MAIAi produces multiple equally valid reasoning chains

execution can proceed with different resource allocations

ADT can choose between several continuity branches

CSR is anchoring a compound event with multiple allowed groupings

L8 receives multiple valid external confirmations

vault mutations have more than one safe sequencing order

Arbitration occurs only if all paths are already safe.

If any path is unsafe → arbitration is not allowed → use Correction/Preclusion instead.

46.2 Arbitration vs. Reconciliation

Clear distinction:

Reconciliation

→ merges multiple partial truths into one.

Arbitration

→ selects between multiple complete and valid truths or actions.

Arbitration is choosing between good options.
Reconciliation is fixing alignment among partial or divergent inputs.

46.3 The Substrate’s Arbitration Hierarchy

When more than one valid option exists, the substrate chooses based on the following hierarchy (in order):

1. Deterministic Predictability

Choose the path with the most predictable, reproducible outcome.

2. Canon Proximity

Choose the path closest to current canonical truth with the least divergence.

3. Identity Sovereignty

Choose the option that maximizes user or entity sovereignty.

4. Vault Integrity

Choose the option that best preserves precise truth.

5. Policy Strictness

When two policies apply, choose the stricter one.

6. Autonomy Stability

Choose the path that best preserves ADT continuity.

7. Execution Efficiency

Performance is a valid tiebreaker only after all higher priorities hold.

8. External Minimization

Prefer paths that reduce dependency on L8 external systems.

Arbitration always follows these priorities—no exceptions.

46.4 Layer-Level Arbitration Rules
Identity Layer

Rarely used. If multiple identity proofs exist (e.g., redundant signatures), choose the most recent authenticated proof.

Vault Layer

If two safe sequences of mutation exist, choose the sequence that yields:

least canonical divergence

highest integrity

lowest exposure

MAIAi Layer

If MAIAi generates multiple valid reasoning paths:

choose the path with minimal context assumptions

choose the path requiring the least extrapolation

MAIAi must remain grounded.

Architect Layer

If two policies permit an action:

enforce the stricter one

or the one that preserves most sovereignty

or the one that minimizes risk

Architect always chooses safety over flexibility.

Execution (BAINCA)

If execution can use multiple valid enclaves or compute pathways:

choose the deterministic-equal path

break ties with efficiency

ADT Layer

If ADT can follow multiple continuity branches:

choose the branch closest to current Canon

OR the branch with least governance risk

CSR Layer

If CSR can group events in different allowed ways:

choose the ordering with least ambiguity

OR the ordering that reduces future reconciliation needs

L8 Layer

If multiple external confirmations are valid:

choose the one requiring least trust

OR the earliest authenticated confirmation

External minimization wins.

46.5 Arbitration Failures

Arbitration must not occur when:

any option violates an invariant

any option is nondeterministic

identity sovereignty is jeopardized

canonical order would become ambiguous

external systems disagree

autonomy continuity would fork

If unsafe → arbitration not allowed → correction or termination.

46.6 Guarantees Provided by Arbitration

Arbitration ensures:

forward progress even with multiple valid paths

decisions are deterministic, not random

autonomy never becomes ambiguous

Canon never contains arbitrary outcomes

external systems never choose for the substrate

vault state never diverges

MAIAi never chooses speculative reasoning

Arbitration is how the substrate “prefers without guessing.”

46.7 Summary

Substrate Arbitration Rules define how the system chooses one path when multiple valid, sovereign, deterministic, safe paths exist.

The selection is:

predictable

priority-aligned

canonical

sovereignty-preserving

safe

never random

Arbitration ensures the substrate moves forward with precision — even when several good options are available.
