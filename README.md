# Personal-Brain Framework

A user-controlled durable-memory framework for ChatGPT.

Personal-Brain is designed for people who want ChatGPT to work naturally across new conversations without depending on ChatGPT Memory. Your private GitHub repository becomes the durable context layer; live systems such as email, calendars, finance tools and booking providers remain the source of current operational truth.

The framework contains **no personal data**. It is an architecture and adoption protocol that ChatGPT can install into a new or existing private personal knowledge repository.

## What you do

### 1. Turn ChatGPT Memory off

Personal-Brain is designed so a fresh chat can recover continuity from your own repository. Memory is not required.

### 2. Add the root routing instructions

Open [CUSTOM-INSTRUCTIONS.md](CUSTOM-INSTRUCTIONS.md) and copy the Standard instructions into ChatGPT's custom instructions.

If you maintain separate personal and work knowledge repositories, use the Multi-brain variant instead and replace its placeholders.

### 3. Connect your private GitHub repository to ChatGPT

Use a private repository for your personal information. It may be empty or contain an existing vault/knowledge base.

Do **not** put your personal information in this public framework repository.

### 4. Start a new ChatGPT conversation

Paste this repository URL:

https://github.com/ReserveTMK/Personal-Brain-Framework

Then say:

> Install the Personal-Brain Framework into my connected personal repository. Preserve anything already there. Follow INSTALL.md from the framework and ask me only for decisions or access you genuinely need.

ChatGPT should read [INSTALL.md](INSTALL.md) and perform the adoption.

## After installation

Use ChatGPT normally.

You should not need to tell it to search the brain, remember something, choose a folder, update an index or maintain the knowledge system. The installed `CHATGPT.md` and operating rules make those agent responsibilities.

The intended loop is:

**conversation → route → relevant Personal-Brain context → live source when needed → work → durable delta reconciled back into Personal-Brain**

## Principles

- **Memory-off safe.** A new conversation may know nothing about you.
- **General questions stay general.** Your repository is not loaded merely because you are the user.
- **Durable meaning lives in your repository.** Decisions, preferences, plans, interpretation and continuity are inspectable and portable.
- **Live truth stays live.** Transactions, balances, email, calendars, bookings and provider terms remain in the systems that own them.
- **Reconcile, don't accumulate.** ChatGPT updates canonical context rather than dumping transcripts.
- **Adaptive structure.** The framework adopts your existing domains where sensible rather than forcing someone else's filing system.
- **Human agency.** ChatGPT manages knowledge-system mechanics; you make genuine personal decisions and approve consequential external actions.

## Existing vaults

You do not need to start over. The installer audits first, preserves existing content, identifies useful canonical notes and domains, then adds the minimum architecture needed for reliable retrieval and writing.

It must not bulk-delete, rename or reorganise your existing material simply to make it resemble another person's vault.

## Framework contents

- [INSTALL.md](INSTALL.md) — machine-facing adoption protocol.
- [CUSTOM-INSTRUCTIONS.md](CUSTOM-INSTRUCTIONS.md) — root ChatGPT routing instructions.
- [framework/CHATGPT.md](framework/CHATGPT.md) — installed ChatGPT entry point.
- [framework/Vault Operating Rules.md](framework/Vault%20Operating%20Rules.md) — autonomous memory governance.
- [framework/Personal Vault Maintenance.md](framework/Personal%20Vault%20Maintenance.md) — maintenance and structural quality.
- [framework/Tools and Connected Sources.md](framework/Tools%20and%20Connected%20Sources.md) — source-ownership template.
- [templates/](templates/) — adaptable home, domain, workspace and current-work templates.
- [checks/vault-content-check](checks/vault-content-check) — optional read-only structural checker.

## Privacy

The framework repository is public. Your Personal-Brain should normally be private.

Never store passwords, API keys, OAuth tokens, authentication caches, passport/licence source images, signatures or other secret authentication material in the brain. Keep sensitive source documents in the secure system that owns them and retain only the durable interpretation needed for continuity.
