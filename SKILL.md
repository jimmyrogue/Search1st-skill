---
name: search-first
description: Research existing mature solutions before implementation. Use for new projects, features, architectures, UI systems, integrations, automations, or unfamiliar-domain work where the user may not know the established terminology, frameworks, libraries, standards, templates, scaffolds, native platform features, or reference implementations. Trigger especially when a request proposes building from scratch, asks how to start, lacks technical constraints, or would add substantial custom code. Do not use for trivial edits, exact user-specified changes, or tasks where the user forbids web research.
---

# Search First  

Find the established path before writing a new one. Reduce custom code by discovering what the domain already calls the problem and how mature projects solve it.

## Default Rule

Do not write implementation code, install dependencies, or generate scaffolding until completing the research brief below.

Inspect the current repository first. Reuse an existing local helper, dependency, component, convention, or platform feature when it already solves the problem.

Then search the internet for current solutions. If browsing is unavailable, state that limitation and pause implementation unless the user explicitly accepts an offline, memory-based approach.

Never expose private source code, credentials, customer data, or proprietary details in search queries.

## Workflow

### 1. Frame the capability

Translate the request into:

- the outcome the user needs;
- the domain terms experts would search for;
- the hard constraints from the repository and environment;
- the parts the user assumes must be custom but may already exist.

Search by capability and domain terminology, not only by the user's wording.

### 2. Discover established options

Look for, in this order:

1. Existing solutions already used in the repository.
2. Standard-library or native platform capabilities.
3. Official starters, templates, reference architectures, and generators.
4. Maintained frameworks, libraries, components, plugins, and services.
5. Proven open-source implementations that can be adapted legally.
6. Custom implementation only for the remaining gap.

Cover the categories that matter to the task, such as UI systems, code frameworks, protocols, data models, deployment patterns, integrations, and operational tooling.

Prefer primary sources: official documentation, specifications, source repositories, release notes, security advisories, and maintainer statements. Use independent comparisons or issue discussions to verify real-world limitations.

### 3. Verify candidates

Shortlist only viable candidates. Check:

- fit with the required behavior and platform;
- compatibility with the repository's language, versions, and architecture;
- maintenance activity, release recency, and deprecation status;
- license and commercial-use constraints;
- security posture and known advisories;
- adoption evidence and production maturity;
- integration, migration, lock-in, and operating costs;
- how much custom code the option actually removes.

Do not treat popularity, search ranking, or star count as sufficient evidence.

Reject a candidate when a hard constraint fails. Do not distort the user's requirement merely to justify using an existing tool.

### 4. Present the research brief

Before implementation, report:

- **Established approach:** How the field normally solves the problem.
- **Candidates:** Two to five credible options, or fewer when the ecosystem has a clear standard.
- **Recommendation:** The best fit and why it wins for this specific context.
- **Reuse plan:** What to adopt, what thin glue remains, and what will not be built.
- **Risks:** Compatibility, maintenance, license, security, cost, or lock-in concerns.
- **Sources:** Direct links to the evidence used.

Ask the user only when the choice materially changes product behavior, cost, licensing, data ownership, or long-term architecture and no safe default exists. Otherwise, choose the best-supported option and continue.

### 5. Implement the narrow gap

Start from the selected official scaffold, native feature, installed dependency, or maintained project. Follow its documented setup and repository conventions.

Write only the integration and product-specific behavior that the mature solution does not provide. Preserve required validation, security, accessibility, error handling, and tests.

If no candidate fits, state the exact unmet requirements and implement the smallest custom solution that covers them.

## Research Depth

Scale the search to the decision:

- Use a focused search for reversible, low-risk work.
- Use a deeper comparison for unfamiliar domains, foundational architecture, expensive services, security-sensitive systems, or hard-to-reverse choices.
- Stop when authoritative sources and an independent cross-check converge, remaining candidates fail known constraints, and more searching is unlikely to change the recommendation.

Do not turn research into delay. The goal is a better starting point, not an exhaustive catalog.

## Exceptions

Skip internet research for a typo, literal copy change, tiny style adjustment, or other exact local edit with no architectural choice. Still inspect the repository for the existing path.

Honor an explicit request not to browse. Clearly label any recommendation based only on local evidence or model knowledge.
