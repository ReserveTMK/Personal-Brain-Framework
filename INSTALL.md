# Install / adopt Personal-Brain

## Instruction to ChatGPT

You are adopting the Personal-Brain Framework into the user's connected **private personal repository**.

This public framework is a specification and template source. Never write the user's personal information into this public repository.

Your goal is not to make their repository look exactly like another person's. Your goal is to install the same durable-memory operating architecture while preserving and adapting their existing knowledge.

## Before writing

1. Identify the target private repository. If it is not clear or not writable, ask the user.
2. Audit its root, existing agent instructions, indexes/navigation, major folders, metadata conventions, current-work mechanisms and obvious live-system references.
3. Determine whether this is:
   - a fresh/empty Personal-Brain;
   - an existing personal knowledge repository needing adoption; or
   - already substantially compatible.
4. Read the files in this framework under `framework/`, `templates/` and `checks/`.
5. Map the user's existing life domains. Do not assume the example domain names in this framework are exhaustive or mandatory.
6. Identify conflicts that could cause data loss, misleading source ownership or competing agent doctrine.

Do not bulk-delete, rename or reorganise existing personal material merely for aesthetic consistency. Preserve unrelated content and history.

## Install the operating layer

The target repository should end with these capabilities:

### Root doorway

Create or reconcile `_HOME.md` so it maps the person's actual domains and points to:
- `CHATGPT.md`;
- `Vault Operating Rules.md`;
- `_WORK.md` when current-work tracking is useful;
- Operations/maintenance guidance;
- Inbox/Archive only if those concepts are useful in this repository.

### ChatGPT entry point

Install/adapt `framework/CHATGPT.md` as root `CHATGPT.md`.

Replace placeholders and generic language only where the target repository establishes the correct person/repository context. Preserve the behavioural contract:
- Instant-first;
- Memory-off safe;
- proportionate retrieval;
- autonomous read/write;
- source ownership;
- live-source gate;
- revalidation;
- reconciliation/compaction;
- Work compatibility;
- optional repository clients rather than mandatory Codex.

### Operating rules

Install/adapt `framework/Vault Operating Rules.md`.

Do not weaken:
- the read, live-source, write, revalidation and compaction gates;
- the distinction between durable interpretation and volatile live records;
- standing authority for ordinary scoped Personal-Brain context capture;
- external-action approval boundaries;
- secret/authentication boundaries.

### Domain doorways

For each meaningful existing domain, ensure there is a clear index/doorway. Prefer the repository's existing index naming convention when it is coherent; otherwise use `_index.md`.

A domain doorway should tell a future memoryless ChatGPT, where useful:
- what belongs there;
- strongest canonical notes/sub-workspaces;
- which live sources own volatile truth;
- useful read order;
- write-back routing when ownership could be ambiguous.

Do not create empty domains simply because a template exists.

### Complex workspaces

A topic deserves a nested workspace only when it has several durable artefacts, sustained follow-up, multiple source files or enough moving parts that a single note is no longer a good doorway.

Keep the workspace inside the domain that owns it. Use `templates/Workspace Index.md` as guidance, not a rigid form.

### Current work

Use/adapt `_WORK.md` when the person's ongoing matters benefit from a cross-domain live view. It should link to canonical notes rather than duplicate their content.

Use vault-wide `status` for note authority and optional `stage` for current-work lifecycle. Keep domain-specific states in separate fields.

### Live systems

Create/adapt `Operations/Tools and Connected Sources.md` from the framework template.

Discover the person's actual systems from their repository and conversation. Do not assume they use PocketSmith, Gmail, Google Calendar or any example provider.

For each relevant system define:
- what truth it owns;
- what Personal-Brain should retain;
- when it must be rechecked;
- what should not be copied into the brain.

Do not claim a connector is available until the current ChatGPT environment establishes that it is.

### Maintenance

Install/adapt `Operations/Personal Vault Maintenance.md`.

If executable repository scripts are appropriate, install `checks/vault-content-check` as `bin/vault-content-check` and adapt exemptions/index conventions to the target structure. If scripts are not useful in that environment, retain the maintenance checks as documented criteria instead.

## Existing-content reconciliation

Do not try to rewrite the entire vault in one adoption unless necessary.

Prioritise:
1. competing or obsolete agent instructions;
2. root navigation;
3. domain indexes;
4. current active matters;
5. source-ownership ambiguity;
6. obvious duplicate canonical notes;
7. metadata/lifecycle conflicts that impair retrieval.

Leave lower-value historical cleanup as explicit follow-up rather than manufacturing certainty.

## Validation

Before declaring adoption complete, test the resulting architecture against realistic memoryless-chat questions drawn from the person's actual content.

At minimum verify:
- a general self-contained question would not require Personal-Brain;
- an ongoing personal matter routes through the correct domain;
- a durable preference/decision can be recovered;
- a volatile fact routes to its owning live source rather than a stale cached value;
- a new durable decision has a clear canonical write-back location;
- current-work navigation reaches active matters without loading the whole repository.

Run structural checks when available. Report warnings separately from blocking errors.

## Completion report

Tell the user:
- what operating files were installed or reconciled;
- which existing domains were adopted;
- which live-source relationships were identified;
- any important unresolved ambiguity;
- whether the repository is ready for a fresh Memory-off ChatGPT conversation.

Do not make the user learn the vault machinery in order to use it.
