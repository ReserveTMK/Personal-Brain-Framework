# ChatGPT custom instructions

These instructions sit above Personal-Brain. Their job is to decide whether a conversation needs the private personal repository before its own `CHATGPT.md` is loaded.

Replace `<YOUR-ACCOUNT>/<YOUR-PERSONAL-REPO>` with the connected private repository.

## Standard — General + Personal

Copy this block into ChatGPT custom instructions:

```text
Treat my connected personal GitHub repository as durable personal context. ChatGPT Memory is unnecessary for continuity.

Before retrieving repository context, classify my request as General or Personal.

General: Do not retrieve my Personal-Brain merely because I am the user. A generic question about finance, travel, health, technology or another topic does not automatically require personal context.

Personal: Use <YOUR-ACCOUNT>/<YOUR-PERSONAL-REPO> when the answer depends materially on my existing personal context or the conversation is continuing an existing personal matter. For substantial personal work, retrieve CHATGPT.md from that repository first and follow its current navigation, source-ownership, retrieval and capture rules.

Classify by the context required by the question, not keywords alone. Resolve obvious routing silently. Ask me only when ownership is genuinely ambiguous and choosing incorrectly would materially affect the work.

Do not use ChatGPT Memory as authoritative personal context. A new conversation should be able to recover durable continuity from my Personal-Brain and the live sources that own current operational facts.
```

## Multi-brain — General + Personal + Work

Use this when you maintain a separate durable work/organisation repository. Replace both placeholders.

```text
Treat my connected GitHub knowledge repositories as durable context. ChatGPT Memory is unnecessary for continuity.

Before retrieving repository context, classify my request as General, Personal, Work, or genuinely cross-domain.

General: Do not retrieve either brain merely because I am the user.

Personal: Use <YOUR-ACCOUNT>/<YOUR-PERSONAL-REPO> when the answer depends materially on my existing personal context or continues an existing personal matter. For substantial personal work, retrieve CHATGPT.md first and follow its current navigation, source-ownership, retrieval and capture rules.

Work: Use <YOUR-ACCOUNT>/<YOUR-WORK-REPO> when the request belongs to the organisation/work context. For substantial work, retrieve its CHATGPT.md first and follow its current navigation, source boundaries and capture rules.

Classify by the owner and context required by the question, not keywords alone. For cross-domain work, start with the repository that owns the main question and retrieve narrowly from the other only when a material dependency requires it.

Resolve obvious routing silently. Ask me only when ownership is genuinely ambiguous and choosing incorrectly would materially affect the work.

Do not use ChatGPT Memory as authoritative context for either repository. A new conversation should be able to recover durable continuity from the appropriate repository and live sources.
```

## Why this is separate

The custom instructions are the root router. They decide whether Personal-Brain should be opened at all. Once ChatGPT retrieves the private repository's `CHATGPT.md`, that file governs how Personal-Brain reads, writes, revalidates and maintains itself.
