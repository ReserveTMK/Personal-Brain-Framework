---
type: agent-entrypoint
agent: chatgpt
status: live
updated: YYYY-MM-DD
---
# ChatGPT in Personal-Brain

This is the retrieval, navigation and durable-memory entry point for ordinary ChatGPT using this private Personal-Brain repository.

[[Vault Operating Rules]] is canonical for shared retrieval, capture, source, approval and authority boundaries.

Assume ChatGPT Memory is disabled and that every new conversation may begin with no remembered personal context. Personal-Brain is the durable continuity layer. If Memory is available, treat it only as a discovery lead until reconciled against Personal-Brain or the source that owns the claim.

## Find the right context

For substantial personal work, start from the smallest useful doorway:

1. Read [[_HOME|Home]] when the domain is unclear.
2. Read the relevant domain index.
3. Search for the exact subject and useful aliases.
4. Open the strongest matching canonical notes and follow useful links.
5. Prefer current canonical notes over sessions, Inbox, Archive or old chat.
6. Expand into a live connected system only when the question requires truth owned there.

Retrieve proportionately. Do not load the whole repository merely because it is available. General, casual and self-contained questions do not require Personal-Brain.

## Operate the memory layer for the user

The user should interact with their life and decisions, not the repository machinery.

For a personal request, silently decide:

1. **Read gate:** does existing personal context materially improve the answer, continuity or safety?
2. **Domain gate:** which domain/canonical doorway owns the subject?
3. **Live-source gate:** does the answer depend on operational truth that can change independently of the repository?
4. **Write gate:** did this work establish or change durable context likely to matter later?
5. **Canonical-home gate:** where should that durable delta be reconciled?
6. **Human gate:** is a genuine personal decision, missing fact, sensitive boundary or external-action approval required?

Do not ask the user to choose files, folders, metadata, indexes, capture mechanics or retrieval strategy.

## Source ownership

Personal-Brain owns durable personal meaning: decisions, stated preferences, plans, interpretation, constraints, ongoing matters and useful history.

Live systems own volatile operational records. Examples can include finance systems, email, calendars, source documents, booking systems and provider records.

Use the source that owns each claim. A cached repository value does not become current merely because it was previously verified.

If the owning live source is unavailable, state the last durable understanding and what remains unverified. Do not invent continuity from stale values.

## Durable capture

Ordinary scoped Personal-Brain context capture is standing-authorised unless the user opts out.

Write/reconcile when the work establishes or changes something likely to matter later, such as:
- a decision or durable stated preference;
- changed plan, constraint, risk, trigger or next action;
- stable rule for interpreting a live system;
- material conclusion from source investigation;
- source relationship future work needs to understand;
- named ongoing personal matter; or
- reasoning costly to reconstruct.

Usually do not save one-off answers, temporary speculation, discarded brainstorming, raw operational exhaust or context already represented canonically.

Before writing, read the current canonical note. Reconcile rather than append another version. Update the closest domain index or [[_WORK|Current Work]] only when navigation or lifecycle changes.

Do not treat brainstorming or comparison as a locked decision.

## Revalidation

When a future answer/action materially depends on a fact that can change, recheck the source that owns it. Verification dates and `last_reviewed` are freshness signals, not guarantees.

Stable personal facts and explicit preferences do not require repeated checking without reason to think they changed.

## Compaction

Durable memory is a reconciled current view, not a transcript archive.

Remove stale current wording from the active view, merge overlapping context and preserve explicit history only when the change itself has future value. Git carries routine wording history.

## Instant, Work and optional repository clients

- **ChatGPT Instant with Memory off** is the primary design case. Treat each new chat as potentially memoryless.
- **ChatGPT Work** uses the same memory contract for longer multi-step investigation, connected-source work, app/browser interaction and finished artefacts. Promote only the durable delta from its working state.
- **Native Codex or another repository client** is optional. It follows the same canonical rules and is never required as a relay for ordinary Personal-Brain use.

## Pause and resume

At a meaningful stopping point in substantial unfinished work, preserve continuity when doing so will materially help resumption. Distinguish confirmed context from proposals, assumptions and unresolved questions.

Do not create handoff machinery for routine chat.

## Approval and safety

Follow [[Vault Operating Rules]]. Repository read/write authority does not authorise sending, spending, publishing, deleting, changing provider state or other consequential external actions.

Never store credentials, authentication material or prohibited secret/source artefacts.

## Failure handling

If this entry point or a referenced note cannot be retrieved:
1. diagnose available repository access;
2. search for the expected file/equivalent canonical source;
3. use an equivalent source only when its authority is clear; and
4. if current repository context cannot be accessed, state the limitation rather than pretending continuity.
