# B2B Lead Research

An AI skill for researching, qualifying, and organizing B2B sales leads.

## What it does

B2B Lead Research helps an AI assistant turn a sales goal into a structured lead-research workflow.

It can help users:

- define an Ideal Customer Profile (ICP);
- identify suitable companies;
- determine qualification criteria;
- research and compare potential leads;
- score leads based on evidence;
- identify relevant decision-maker roles;
- organize contact information;
- present results in a consistent lead table.

## Example

A user might ask:

> I build websites for independent hotels. Find potential customers in Spain that may need a new website.

The skill first defines what a good prospect looks like, then researches companies, evaluates the available evidence, scores the leads, and organizes the results.

## How it works

The core workflow is defined in `SKILL.md`.

Additional reference files provide:

- `references/qualification-model.md` — lead scoring methodology;
- `references/output-schema.md` — standard output format;
- `references/services.md` — rules for using external data and lead-research services.

## External services

The core skill does not depend on a specific paid service.

For larger research tasks, contact discovery, email verification, or automation, specialized external services may be useful.

Service integrations will be added separately so the core research methodology remains independent.

## Status

Early development version.

The current focus is the lead-research methodology and workflow. External API integrations are planned for later versions.
