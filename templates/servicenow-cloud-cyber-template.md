# Cloud/cyber review boilerplate

This template provides boilerplate text for a cloud/cyber review request. Paste the standard boilerplate below into the required cloud/cyber review ticket or the relevant section of your onboarding request, then supplement it with your agency-specific details.

If the cloud/cyber review requires a separate ticket, record the ticket number and status in your parent onboarding ticket.

---

## Part 1: Standard boilerplate

Paste or reference the following baseline information in the review request.

> **Service:** GitHub Enterprise (cloud) — an established SaaS platform. This review is expected to be routine.
>
> **Org admin model:** Each organization has at least two designated org admins who manage membership, teams, and settings.
>
> **Access control:** Access is managed through team-based permissions. Direct one-off repository permissions are discouraged.
>
> **Repository visibility:** Repository visibility is set in compliance with NYC GitHub policy. Agencies document whether repositories are public, private, or mixed.
>
> **SSO requirement:** SSO is required for all organizations in the ODA-managed enterprise. `[DECISION NEEDED: set required SSO integration deadline to 60 or 90 days after onboarding]`
>
> **Copilot / AI / MCP governance:** Copilot model availability, agent enablement, and MCP usage are governed per the policy described in the [Organization configuration](../docs/02-org-configuration.md) page. All Grok models are disabled enterprise-wide. MCP is treated as a privacy review item and enabled intentionally, not by default.

---

## Part 2: Agency-specific details to complete

Fill in the following fields to describe your agency's specific use case.

**Agency:**
[fill in]

**Business purpose:**
[fill in]

**Use case — how will the organization use GitHub?**
[fill in]

**Data sensitivity:**
- Expected data classification: [fill in]
- Sensitive, regulated, or restricted data expected in GitHub? [yes/no/details]
- Secrets or credentials stored in GitHub or managed elsewhere? [fill in]

**Existing org / repo migration:**
- Migrating an existing GitHub organization into the enterprise? [yes/no]
- Migrating existing repositories? [yes/no/details]

**External collaborators:**
- Outside collaborators or contractors expected? [yes/no/details]
- Approval and offboarding process for collaborators: [fill in]

**AI / agent / MCP usage:**
- Copilot requested? [yes/no]
- Coding agent, code review agent, or partner agents requested? [yes/no/details]
- MCP planned? [yes/no]
- If MCP is planned, what external systems will it connect to and what context may leave GitHub? [fill in]

**Cloud integrations:**
- GitHub Actions with cloud resources? [yes/no]
- Cloud credentials needed? [yes/no]
- Self-hosted runners? [yes/no]
- Other external integrations: [fill in]

**Anything unusual for review:**
[fill in]

---

## Review outcome

**Reviewer:**
[fill in]

**Decision:**
- Approved
- Approved with conditions
- Needs escalation
- Not approved

**Conditions / notes:**
[fill in]

**Review ticket number (if separate from parent):**
[fill in]
