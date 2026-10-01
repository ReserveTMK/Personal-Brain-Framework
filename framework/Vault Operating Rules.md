---
type: operating-rules
status: live
updated: YYYY-MM-DD
---
# Vault Operating Rules

Canonical shared rules for Personal-Brain.

## Purpose

Personal-Brain is a durable personal context layer, not a complete life database. It is designed first for ChatGPT Instant with Memory off: a new conversation must be able to recover useful continuity from the repository and owning live sources without remembered chat context.

Keep the smallest useful body of context that prevents repeated reconstruction: stable facts, stated preferences, decisions and rationale, plans, constraints, interpreted system context, ongoing personal matters and useful history.

Keep volatile operational records in the system that owns them. Personal-Brain captures durable meaning and interpretation rather than duplicating entire inboxes, calendars, ledgers or provider databases.

## Source ownership and provenance

There is no universal source hierarchy. Use the source that owns the claim.

The user owns their stated preference, intent and personal decision. A provider owns its current terms/account state. A live application owns the records maintained there. Personal-Brain owns the durable interpretation, rationale and reconciled personal context derived from those sources.

A verification marker means a claim was checked against the named source on that date; it does not permanently outrank a newer live source.

When sources disagree, use clear ownership when it resolves the issue. Otherwise preserve the discrepancy and identify what would resolve it. Imported chats, summaries and AI memory are leads to reconcile, not truth to paste.

## Retrieval

For substantial personal work:
1. start at Home when the domain is unclear;
2. read the relevant domain doorway;
3. for a complex topic, read its workspace doorway;
4. search for the exact subject and aliases;
5. open the strongest canonical notes;
6. prefer current notes over sessions, Inbox, Archive or old chat; and
7. check a live source only when the question depends on truth owned there.

Retrieve proportionately.

## Autonomous memory contract

The agent owns ordinary knowledge-system mechanics: retrieval path, source selection, save threshold, canonical filing, reconciliation, index/current-work maintenance and avoidance of duplicate/stale material.

Do not delegate repository administration back to the user.

### Read gate

Retrieve Personal-Brain when an ongoing personal matter, prior decision/preference, personal constraint or continuity could materially affect the work. Skip it for general self-contained questions.

### Live-source gate

Consult the live source when the answer/action depends on state that can change independently of the repository: balances, transactions, bookings, correspondence, calendar state, provider terms, prices, live documents/models or similar operational records.

### Write gate

Reconcile durable memory when work establishes or changes a decision, preference, plan, constraint, risk, trigger, next action, interpretation rule, material source conclusion, ongoing matter or expensive-to-reconstruct reasoning.

Do not save raw operational exhaust merely because it was read.

### Revalidation gate

Recheck the owning source when a consequential future answer/action depends on a volatile fact. Stable personal facts/preferences need no repeated verification without reason.

### Compaction gate

Reconcile rather than append. Merge overlapping context, remove stale current wording and preserve explicit history only when it has future value.

## Filing

Stay domain-first. Prefer existing canonical notes and domains.

Every new durable note should be reachable from its domain doorway. Use one canonical home where practical. Do not create `v2`, `final` or `latest` duplicates.

Create a nested workspace only when a topic has multiple durable artefacts or sustained moving parts and a single note stops being a useful doorway.

Use Inbox only for genuinely unresolved capture. Archive only after current durable outcomes are promoted elsewhere.

## Authority and lifecycle

Recommended note authority:
- `draft`: developing work;
- `live`: current reference;
- `locked`: explicitly settled durable decision;
- `superseded`: retained history replaced by a newer source;
- `closed`: completed work.

Optional work lifecycle:
- `idea`, `planning`, `active`, `waiting`, `parked`, `complete`.

Keep domain-specific state in a separate field rather than overloading `status`.

Only the user can turn a developing personal decision into a locked decision.

## Frontmatter

Durable Markdown notes should normally include only metadata that helps retrieval, authority, lifecycle or freshness:

```yaml
---
type: <useful note type>
status: draft | live | locked | superseded | closed
updated: YYYY-MM-DD
---
```

Use `stage:` for current work when useful and `last_reviewed:` where freshness matters.

## Capture and reconciliation

Ordinary scoped Personal-Brain context capture is standing-authorised unless the user opts out. Explicit requests such as “remember this”, “save this” or “update the brain” are clear capture instructions but should not be required when context clearly crosses the write gate.

Before writing, read the current canonical note and reconcile the new material. Update navigation/current work only when it changed.

## Sessions

Sessions are optional working history, not the primary memory layer. Use them only when chronology, rejected approaches, handoff context or unfinished threads materially help later work. Promote durable outcomes into canonical domain notes.

## Approval boundaries

Ordinary Personal-Brain reading and scoped durable-memory reconciliation do not require repeated approval.

Get explicit approval before consequential external actions such as sending, spending, publishing, deleting, changing provider state or similar mutations. Repository restructuring/deletion also requires appropriate approval.

## Secret boundary

Never store passwords, API keys, OAuth tokens, authentication caches, private keys or equivalent secrets. Avoid storing sensitive source artefacts such as identity-document images, signatures or signed forms when a secure source system should own them. Retain only the durable interpretation needed for continuity.

## Maintenance

Keep maintenance proportionate. Review current work and Inbox when useful, run structural checks after meaningful changes, reconcile stale active context and never automate deletion.
