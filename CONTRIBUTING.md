# Contributing a Disclosure Template

## Submission

1. Pick the most appropriate folder structure (templates/[platform-context].md)
2. Copy an existing template as your starting point
3. Make sure your template covers: when to use, the actual language, what NOT to do, and why
4. Open a PR

## Required structure for a new template

```markdown
# [Platform / Context]: [Disclosure type]

## Use when
[1-2 sentences on the specific scenario]

## Templates
[The actual disclosure language for 2-4 common variants]

## What NOT to do
[Common mistakes specific to this context]

## Notes
[Optional: additional context, why this works, jurisdictional notes]
```

## Quality bar

- **Plain English.** A typical viewer/reader/listener should understand it without legal training.
- **Specific.** Name the relationship type (affiliate, sponsored, gifted, advisor). Vague disclosures don't comply.
- **Up front.** Templates should default to disclosure BEFORE the recommendation, not after.
- **Multiple variants.** Each template file should have at least 2-3 variants for common situations within that context.

## What gets rejected

- Templates that recommend `#sp` / `#partner` / `#collab` style hashtags as the primary disclosure
- Templates that put disclosure only at the end of content
- Templates that link to a separate disclosure page as the primary disclosure
- Templates with "engagement-optimized" language that obscures the disclosure
- Templates that don't cite a real platform or context
- Templates for disclosing things that aren't material connections (e.g. "I disclose I once met the founder at a conference" is not required)

## Jurisdictional contributions

Templates for non-US jurisdictions are welcome. Mark them clearly:

```markdown
# [Platform]: [Disclosure type] (UK / ASA-aligned)
```

Cite the relevant authority's guidance in the template's Notes section. Examples:
- US: FTC Endorsement Guides
- UK: ASA CAP Code, CMA guidance
- EU: UCPD (Unfair Commercial Practices Directive) member-state implementations
- Canada: Competition Act + Ad Standards Code
- Australia: AANA Code of Ethics + ACCC guidance

## What this collection is NOT

- **Not legal advice.** Submitted templates follow guidance as published; submitters do not provide legal review for specific situations.
- **Not a complete compliance solution.** Disclosure is one piece of a creator's compliance picture (taxes, contracts, IP, platform ToS).
- **Not a place for "stealth ad" language.** This collection exists to help creators DISCLOSE clearly, not to find phrasings that meet the letter while violating the spirit.

## Updating a template

If FTC (or equivalent authority) guidance evolves and a template needs updating, open a PR with the updated language and a citation to the new guidance.

PR title: `update template: [platform-context]`
