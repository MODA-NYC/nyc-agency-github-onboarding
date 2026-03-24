# Org configuration workstream template

Use this template to document the org-specific setup decisions for the request.

Some fields may also appear in the parent request so this ticket can stand on its own if it is routed separately.

## Request details

**Agency:**
[fill in]

**Proposed org name:**
[fill in]

**Purpose statement:**
[fill in]

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

See [Organization configuration](../docs/02-org-configuration.md) for the full list of org-admin responsibilities.

**The proposed org admins acknowledge those responsibilities:**
[yes/no]

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

**SSO expected or required?**
[yes/no/details]

**Other identity dependencies:**
[fill in]

**[DECISION NEEDED] Does Azure tenant membership affect this request?**
[fill in]

## Copilot, AI, and MCP choices

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

- [ ] Org name and purpose approved
- [ ] Two org admins approved
- [ ] Access and team model documented
- [ ] Repository defaults documented
- [ ] Identity and SSO choices documented
- [ ] Copilot / AI / MCP choices documented
- [ ] Org admin responsibilities acknowledged
