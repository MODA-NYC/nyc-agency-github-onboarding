# Org configuration workstream template

Use this template to document the org-specific setup decisions for the request.

Some fields may also appear in the parent request so this ticket can stand on its own if it is routed separately.

## Request details

**Agency:**
[fill in]

**Purpose statement:**
[fill in]

> ODA standardizes organization naming. You do not need to propose an org name.

## Admins and ownership

**Business owner:**
[fill in]

**Technical owner:**
[fill in]

**Org admin #1:**
[fill in]

**Org admin #2:**
[fill in]

## Org admin responsibility acknowledgment

The full list of org-admin responsibilities is described in [Organization configuration](../docs/02-org-configuration.md).

**The proposed org admins have reviewed and accept those ongoing responsibilities:**
[yes/no]

## Existing org / repository migration

**Does the agency need to migrate an existing GitHub organization into the enterprise?**
- Yes
- No

**If yes, existing org name / URL:**
[fill in]

**Does the agency need to migrate existing repositories into the enterprise?**
- Yes
- No

**If yes, approximate number of repositories and any migration concerns:**
[fill in]

## Access and team model

**Expected users:**
[fill in]

**Will access be managed through teams?**
[yes/no/details]

**Will outside collaborators be allowed?**
[yes/no/details]

**Approval path for outside collaborators:**
[fill in]

**Dormant user review process:**
[fill in]

## Repository model and baseline controls

**Expected repository visibility:**
- Public
- Private
- Mixed

**Repository naming convention, if any:**
[fill in]

**Default repository settings / rulesets / branch protection:**
[fill in]

**Review, template, label, and README standards:**
[fill in]

## Identity and SSO

SSO is required for all organizations.

**SSO integration plan and timeline:**
[fill in]

`[DECISION NEEDED: set required SSO integration deadline to 60 or 90 days after onboarding]`

**Other identity dependencies:**
[fill in]

**[DECISION NEEDED] Does Azure tenant membership affect this request?**
[fill in]

## Copilot, AI, and MCP choices

Copilot, AI, and MCP policy is described in [Organization configuration](../docs/02-org-configuration.md). Document your agency's choices below.

### Copilot models

**Will the org use Copilot?**
[yes/no]

**If yes, which NYC-approved model providers should be available?**
- Anthropic Claude
- Google Gemini
- OpenAI GPT

**Preview models allowed?**
[yes/no]

**Note:** All Grok models are disabled enterprise-wide and cannot be enabled at the org level.

### Copilot agents

**Coding agent enabled?**
[yes/no]

**Code review agent enabled?**
[yes/no]

**Partner agents enabled?**
[yes/no/details]

**Any planned future use of custom agents?**
[yes/no/details]

### MCP

**MCP requested?**
[yes/no]

**If yes, should MCP be enabled after privacy review?**
[yes/no/details]

**If yes, privacy risks and external systems documented?**
[yes/no/details]

**Any users already assigned Copilot seats in another GitHub org?**
[yes/no/details]

## Support model

**Agency support contact:**
[fill in]

**Escalation path to ODA:**
[fill in]

## Definition of done

- [ ] Org purpose documented
- [ ] Two org admins approved
- [ ] Org admin responsibilities acknowledged (see [Organization configuration](../docs/02-org-configuration.md))
- [ ] Existing org / repo migration plan documented, if applicable
- [ ] Access and team model documented
- [ ] Repository defaults documented
- [ ] SSO plan and timeline documented
- [ ] Copilot / AI / MCP choices documented
