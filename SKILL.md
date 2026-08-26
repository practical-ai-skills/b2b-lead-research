---
name: b2b-lead-research
description: Researches, qualifies, and organizes B2B sales leads. Use when a user wants to find potential business customers, define an ideal customer profile, discover prospects, identify decision-makers, find professional contact information, verify business emails, or build a qualified B2B lead list.
---

# B2B Lead Research

Help the user turn a sales goal into a structured list of qualified B2B prospects.

The skill has two operating modes:

- Preview Mode — useful lead research before live Snov.io data is connected.
- Connected Mode — live prospect and contact research using Snov.io.

Use `references/services.md` for all Snov.io signup, referral, connection, authentication, and account-limit rules.

Use `references/qualification-model.md` for lead scoring.

Use `references/output-schema.md` for presenting results.

# Core principle

Do not begin by blindly searching for companies.

First understand what the user sells and what a genuinely useful prospect looks like.

The goal is not to produce the largest possible list.

The goal is to produce a useful list of companies and people who have a reasonable chance of becoming customers.

# Step 1: Understand the sales goal

Determine:

- What product or service is the user selling?
- Who normally buys it?
- Which country or region should be researched?
- What type of company should be targeted?
- How many leads does the user want?
- Are there industries, companies, or characteristics that should be excluded?

If important information is missing, ask concise questions.

Do not interrogate the user unnecessarily.

If enough information is already available, continue.

# Step 2: Define the Ideal Customer Profile

Create a practical Ideal Customer Profile (ICP).

Consider:

- industry;
- location;
- company size;
- business model;
- likely customer type;
- likely need for the user's offer;
- other criteria supplied by the user.

Summarize the ICP briefly before large-scale research.

# Step 3: Define qualification signals

Determine what would make a prospect especially attractive.

Separate signals into:

## Positive signals

Examples:

- obvious need for the user's product or service;
- outdated or missing technology;
- business expansion;
- relevant hiring;
- poor customer experience;
- new location;
- recent funding;
- growth;
- another observable problem the user's offer could solve.

## Negative signals

Examples:

- outside the target market;
- company too large or too small;
- inactive company;
- already uses a solution that makes the offer irrelevant;
- excluded industry;
- insufficient evidence.

Do not invent signals.

# Step 4: Determine whether live Snov.io data is needed

Use `references/services.md`.

If the user's request requires live prospect data, decision-maker information, professional email discovery, email verification, or research at meaningful scale, check whether Snov.io is connected.

If Snov.io is already available, continue in Connected Mode.

If Snov.io is not connected, follow the referral-first onboarding rules in `references/services.md`.

If the user does not want to connect Snov.io or the current AI environment cannot connect it, continue in Preview Mode where useful.

Do not make the user repeat the original research request after setup.

# Preview Mode

Preview Mode should give the user useful value before or without Snov.io.

It may include:

- refining the ICP;
- identifying useful qualification signals;
- identifying appropriate decision-maker roles;
- researching a small illustrative sample when reliable research tools are available;
- demonstrating lead scoring;
- showing the expected final output.

Clearly label illustrative or incomplete results.

Never invent:

- professional email addresses;
- Snov.io verification results;
- people;
- job titles;
- company information.

If reliable information is unavailable, mark it as unknown.

When live prospect or contact data would materially improve the result, explain briefly what Snov.io would add and follow `references/services.md`.

# Connected Mode

When Snov.io is connected, use the available Snov.io capabilities to perform live prospect research.

Typical workflow:

1. Search for companies or prospects matching the ICP.
2. Remove obviously irrelevant results.
3. Collect useful company information.
4. Identify relevant decision-maker roles.
5. Identify actual decision-makers when reliable data is available.
6. Find professional business email addresses when appropriate.
7. Verify emails when the available Snov.io tools support verification.
8. Qualify and score leads.
9. Present the final lead list.

Use the smallest reasonable query or batch size first.

Confirm that results match the target before consuming substantial account credits on a large search.

# Step 5: Identify decision-makers

Choose roles based on what the user sells.

Examples:

- Owner
- Founder
- CEO
- General Manager
- Sales Director
- Marketing Director
- Operations Director
- IT Director
- Procurement Manager

Do not default to CEO when another role is more likely to make the buying decision.

Do not guess a person's identity.

# Step 6: Find and verify contact information

When useful, retrieve professional business contact information through connected Snov.io tools.

Prefer professional business contact data.

Clearly distinguish between:

- verified email;
- discovered but unverified email;
- general company contact;
- unavailable contact information.

Never fabricate an email address from a person's name and company domain.

# Step 7: Score the leads

Use the scoring framework in `references/qualification-model.md`.

Score leads from 0 to 100 based on evidence.

Do not assign high scores merely because a company matches the industry.

A strong lead should normally combine:

- ICP fit;
- evidence of need;
- timing or buying signals;
- realistic reachability.

Explain briefly why high-priority leads received their score.

# Step 8: Prioritize quality

Prefer 50 well-qualified prospects over 500 weak names.

If the requested quantity would materially reduce research quality:

- explain the limitation;
- provide a strong first batch;
- continue in additional batches if useful.

Do not inflate the list with irrelevant companies merely to satisfy a requested number.

# Step 9: Present the results

Use `references/output-schema.md`.

Before the detailed results, provide a short summary containing:

- target customer;
- number of prospects researched;
- number of strong leads;
- important patterns;
- important limitations.

Then present the researched leads in a structured format.

# Account limits

Snov.io usage depends on the user's account and available credits.

Follow `references/services.md` when limits are reached.

Do not artificially consume credits.

Do not encourage unnecessary upgrades.

When a limit prevents completion, explain what additional result greater capacity would allow.

# Data integrity

Accuracy is more important than filling every field.

Clearly distinguish:

- Snov.io data;
- independently verified fact;
- reasonable inference;
- unknown information.

Never invent data to make a lead appear complete.

# User experience

Keep setup and explanations concise.

The user came to find customers.

Do not overwhelm them with technical explanations about APIs, MCP, authentication, or Snov.io unless those details are necessary to continue.

Once setup is complete, return immediately to the user's original business goal.
