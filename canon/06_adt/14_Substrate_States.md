**14 — Substrate States

The Valid Operating Conditions of the Sovereign Substrate**

Overview

Substrate States define the allowed operational conditions of the Sovereign Substrate.
They describe how the system behaves, transitions, pauses, enforces, and restores, ensuring every part of the substrate remains coherent with the Canon.

These are the only valid system states.
Any condition not represented here is considered an anomaly and triggers enforcement.

14.1 Active State

The normal operating condition.

Characteristics:

Actions follow canonical flows

Identity and vaults are synchronized

MAIAi, Architect, ADT, and BAINCA operate continuously

CSR records all transitions

Interlinking interactions occur through authenticated gateways

This is the steady-state of the authenticated internet.

14.2 Evaluation State

Triggered when the system is assessing an action or request.

Characteristics:

Identity verification in progress

Vault state retrieval

MAIAi analyzing context and meaning

Architect applying policy constraints

The system has not yet committed to execution.

14.3 Execution State

A workload or operation is being performed.

Characteristics:

BAINCA enclaves active

Deterministic execution underway

ADT monitoring continuity

Architect validating step boundaries

Execution must follow canonical flows.

14.4 Continuity State

ADT-managed state where the system is maintaining long-running processes or monitoring conditions.

Characteristics:

Timers, watchers, or lifecycle processes active

No drift allowed

All updates must re-enter canonical flows

MAIAi re-checks changed conditions

Architect revalidates transitions

This is how autonomy stays governed.

14.5 Enforcement State

The system has detected a violation or anomaly.

Characteristics:

Architect halts unauthorized actions

ADT isolates impacted processes

CSR references last valid known-good state

Enforcement flow begins

Restoration or corrective action initiated

This state ensures sovereignty under attack.

14.6 Restoration State

Triggered after a detected violation or desynchronization.

Characteristics:

Substrate rolls back to last valid Canon event

Vault state restored

ADT continuity corrected

Any unauthorized events discarded

CSR records restoration event

The system returns to truth, not best effort.

14.7 Quarantine State

A subsystem or integration is isolated due to detected risk.

Characteristics:

L8 gates external access

ADT freezes autonomy for impacted processes

Architect blocks execution for that context

MAIAi operates in constrained mode

CSR logs quarantine event

Used to contain threats without halting the entire substrate.

14.8 Pause/Suspended State

Temporary freeze of a process or action without enforcement or violation.

Characteristics:

Waiting for additional data

Indeterminate or incomplete context

External dependency delay

ADT holds lifecycle

Execution not authorized yet

No action progresses until the condition is resolved.

14.9 Terminal State

The end state for a process, action, or workflow.

Characteristics:

Successful completion or intentional termination

CSR logs final result

ADT deallocates continuity

No further transitions allowed

System returns to Active State for new actions

This represents the natural end of a canonical flow.

14.10 Failure Modes Prevented

Indeterminate execution

Stray or zombie processes

Drift in long-running tasks

Half-completed operations

Silent policy violations

Unbounded autonomy

Cross-layer contradictions

State corruption under attack

14.11 Summary

Substrate States define the complete lifecycle of authenticated operations.
They ensure that every action has a beginning, middle, and end — all governed by identity, policy, truth, and deterministic execution.

If a state is not represented here,
it is invalid,
and the Substrate must enforce correction or restoration.
