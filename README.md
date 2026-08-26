# B2B Lead Research

An AI skill for researching, qualifying, and organizing B2B sales leads.

Tell the AI what you sell and who you want to reach. The skill helps define your ideal customer, identify promising prospects, find relevant decision-makers, qualify leads, and organize the results.

## What it can do

* Define an Ideal Customer Profile (ICP)
* Build lead qualification criteria
* Identify relevant companies and prospects
* Find appropriate decision-maker roles
* Research professional contact information
* Find and verify business emails
* Score and prioritize leads
* Produce structured lead lists

## Example

A user might ask:

> I build websites for independent hotels. Find potential customers in Spain that may need a new website.

The skill first determines what a good prospect looks like, identifies qualification signals, and prepares the research strategy.

It can then use live prospect data to identify and qualify relevant companies and decision-makers.

## Two operating modes

### Preview Mode

The skill can begin without an external account.

It can help:

* understand your offer;
* define your target market;
* build an ICP;
* identify qualification signals;
* determine the right decision-maker roles;
* demonstrate how leads will be evaluated;
* provide an illustrative research preview when reliable information is available.

### Connected Mode

For live prospect discovery, professional contact information, email finding, and email verification, the skill can connect to Snov.io.

New Snov.io users can start with a free account.

Once connected, the AI can use available Snov.io tools to perform live lead research without requiring the user to manually move data back and forth between services.

## Snov.io integration

Snov.io provides live B2B prospect and contact data used by the Connected Mode.

The integration is designed around Snov.io MCP where supported, allowing compatible AI clients to access Snov.io capabilities directly.

The skill is designed to work across different compatible AI environments rather than being tied to a single AI platform.

## How the skill is structured

The main workflow is defined in:

* `SKILL.md`

Supporting methodology is stored in:

* `references/qualification-model.md` — lead scoring methodology
* `references/output-schema.md` — standard result format
* `references/services.md` — Snov.io onboarding and integration workflow

## Lead quality

The goal is not simply to return the largest possible list.

The skill prioritizes:

* relevance;
* evidence of need;
* buying signals;
* reachability;
* data quality.

A smaller list of well-qualified prospects is preferred over a large list of weak leads.

## Status

Early public version.

Current development focuses on improving cross-platform Snov.io integration, onboarding, and live lead-research workflows.
