**41 — Substrate Fallback Conditions

Mandatory Behaviors When Required State Is Missing or Uncertain**

Overview

Fallback Conditions define how the substrate responds when critical elements like identity, vault state, context, policy, execution determinism, autonomy continuity, or canonical ordering are unavailable, incomplete, or uncertain.

Fallbacks ensure the system:

never guesses

never fabricates

never proceeds unsafely

never accepts ambiguity

never loses sovereignty

A fallback is not a shortcut —
it is the mandatory safe alternative when the preferred path is impossible.

41.1 When Fallbacks Activate

Fallback logic triggers when the system detects:

missing identity

incomplete or conflicted vault state

insufficient context for MAIAi

missing or contradictory policy

nondeterministic execution

ADT continuity gaps

CSR ordering uncertainty

external verification failures

Fallbacks prevent the substrate from entering invalid or unsafe states.

41.2 Core Fallback Rules
Rule 1 — Without identity, deny.

No identity → no operation.

Rule 2 — Without current vault state, defer.

Missing or stale vault data → pause, wait, or request recovery.

Rule 3 — Without context, MAIAi refuses to reason.

No inference. No guessing.
Only deferral.

Rule 4 — Without valid policy, halt.

Governance cannot be skipped.
No policy → no execution.

Rule 5 — Without deterministic execution, reject.

If execution cannot be reproduced → output invalid.

Rule 6 — Without ADT continuity, freeze autonomy.

No forward motion until continuity is restored.

Rule 7 — Without canonical ordering, block anchoring.

CSR cannot commit out of order.

Rule 8 — Without external authentication, drop the request.

If L8 cannot verify → deny or quarantine.

41.3 Layer-Specific Fallback Behaviors
Identity Layer

Fallback: Deny all actions.

Vault Layer

Fallback: Request recovery → block dependent layers.

MAIAi Layer

Fallback: Defer all reasoning until context is available.

Architect Layer

Fallback: Apply the strictest possible policy (or halt if none valid).

Execution Layer (BAINCA)

Fallback: Reject nondeterministic outputs; re-run inside safe enclaves.

ADT Layer

Fallback: Freeze the agent; require reinstatement conditions.

CSR Layer

Fallback: Stop anchoring; revert to last known valid event.

L8 Layer

Fallback: Quarantine external system; no payload acceptance.

41.4 Conflict-Based Fallbacks

When conflicts arise:

Ambiguity → defer

Contradiction → freeze and correct

Uncertainty → safety-first

Missing data → wait or restore

Multiple truths → Canon resolution

Execution mismatch → deterministic rejection

If the system cannot determine a safe way forward, it must stop.

41.5 Escalation-Based Fallbacks

If fallback conditions persist:

Tier 1 → increased scrutiny

Tier 2 → restricted activity

Tier 3 → containment mode

Tier 4 → quarantine

Tier 5 → sovereign protection mode

Fallbacks often precede escalations.

41.6 Guarantees Provided by Fallbacks

Fallbacks ensure:

No unsafe reasoning

No hallucinated truth

No identity confusion

No policy inconsistency

No execution drift

No autonomy gaps

No incorrect anchoring

No external override

Fallbacks preserve sovereignty by preventing unsafe progress.

41.7 Summary

Fallback Conditions define exactly how the substrate behaves when required state is missing or uncertain.

If the system does not know,
it defers.

If the system cannot prove,
it denies.

If the system cannot verify,
it freezes.

Fallbacks ensure that uncertainty never becomes error —
and error never becomes collapse.
