# Publication boundary

This repository and deployed website are public. The private Project Sol repository, private conversations, connected sources, and personal data are not.

## Default rule: private unless already public

Material does not become public merely because Sol can access it, infer it, remember it, or find it in a private source.

Sol may autonomously improve presentation, structure, accessibility, diagrams, corrections, and follow-ups **only using information already deliberately published in this repository/site**.

Information crossing from private context into this public repository for the first time requires Fiona's explicit approval.

## Never publish autonomously

Do not publish or infer:
- home/street address, precise location, routine location patterns, phone numbers, personal email addresses, account identifiers, credentials, tokens, secrets, private URLs, or device identifiers;
- health/medical information, diagnoses, medications, mental-health information, sexuality, finances, legal matters, or other sensitive personal information;
- private relationship/family information or identifying information about third parties;
- private conversations, memories, connected-account content, private files, private repository contents, internal prompts, or unpublished project/client/work information;
- screenshots, logs, stack traces, terminal output, EXIF/location metadata, filenames, paths, usernames, email addresses, notifications, or UI captures unless they have been specifically reviewed for public release;
- hidden/private source material merely because a public-safe summary could be derived from it.

Do not turn sensitive facts into supposedly anonymous anecdotes without approval. Redaction is not automatically sufficient if context could re-identify a person or source.

## Public-safe sources

Content may be used without renewed approval when it is already intentionally public in this repository/site, or when Fiona explicitly approves a specific item for publication.

Public information about Project Sol should still be checked for accidental secrets, personal data, or private implementation details before publication.

## Screenshots and graphics

Real screenshots are preferred when documenting evidence, but every screenshot must be cleared for publication before commit. Check visible text, notifications, status bars, usernames, repository visibility, file paths, browser tabs, account details, and embedded metadata.

Generated illustrations and diagrams must be labelled/presented as illustrations, never as documentary evidence. Do not generate fake screenshots to imply a feature exists.

## Automated publishing

Automation may prepare branches and pull requests from public-safe material. It must not use private Project Sol content as a source for new public facts without explicit approval.

Until a stronger automated privacy review exists, changes that introduce new factual content should remain reviewable before deployment. Pure presentation/accessibility fixes to already-public content may be eligible for automatic deployment later.

## Incident rule

If potentially private or sensitive material is committed publicly, treat publication as exposure even if quickly reverted: remove it from the live site, rotate any exposed secrets, assess whether repository history also needs remediation, and record the incident privately.

## Principle

**Access is not publication permission. Inference is not publication permission.**
