# Cloud and cyber approval workstream template

Use this template to give cloud/cyber reviewers a summary of the proposed setup.

Use the baseline-controls section to show whether the agency will adopt ODA's standard controls or is requesting an exception. Use the org-configuration workstream for the detailed implementation record.

Some fields may also appear in the parent request so this ticket can stand on its own if it is routed separately.

## Request details

**Agency:**
[fill in]

**Proposed org name:**
[fill in]

**Business purpose:**
[fill in]

## Review path

**Routine review expected?**
- Yes
- No
- Needs reviewer confirmation

**If not routine, what is driving deeper review?**
[fill in]

## Baseline controls for reviewer context

Indicate whether the agency plans to adopt these standard controls or is seeking an exception:
- team-based access
- at least two org admins
- protected branches or rulesets for active repositories
- pull request review requirements
- review of dormant users and stale access
- support and escalation path

**Baseline controls adopted?**
[yes/no/details]

**Any requested exceptions to standard controls?**
[fill in]

## Agency-specific use of GitHub

**Expected repositories:**
- Public
- Private
- Mixed

**Planned GitHub capabilities:**
- Source control
- Issues / project management
- Documentation
- Packages
- Actions / CI/CD
- Release workflows or deployments
- Other

**Data classification:**
[fill in]

**Sensitive, regulated, or restricted data expected in GitHub?**
[yes/no/details]

**Secrets or credentials expected in GitHub?**
[yes/no/details]

## Identity and access

**SSO expected or required?**
[yes/no/details]

**SSO may be a prerequisite for approval acknowledged?**
[yes/no]

**Org admins:**
[fill in]

**Outside collaborators expected?**
[yes/no/details]

**Offboarding / access removal method:**
[fill in]

**[DECISION NEEDED] Does Azure tenant membership affect this request?**
[fill in]

## Cloud and integration questions

**Existing Azure subscription?**
[yes/no/unknown]

**Cloud credentials needed for Actions or automation?**
[yes/no/details]

**Self-hosted runners planned?**
[yes/no/details]

**Other cloud or external integrations:**
[fill in]

## AI, Copilot, and MCP

**Copilot requested?**
[yes/no/details]

**Coding agent requested?**
[yes/no]

**Code review agent requested?**
[yes/no]

**Partner agents requested?**
[yes/no/details]

**MCP planned?**
[yes/no/details]

**If MCP is planned, should it be enabled only after privacy review?**
[yes/no]

**If MCP is planned, privacy risks and connected systems documented?**
[yes/no]

## Compensating controls

**Compensating controls for any exceptions or higher-risk use:**
[fill in]

## Decision

**Reviewer:**
[fill in]

**Decision:**
- Approved
- Approved with conditions
- Needs escalation
- Not approved

**Conditions / notes:**
[fill in]

## Definition of done

- [ ] Review path recorded
- [ ] Baseline controls and agency-specific choices documented
- [ ] Decision recorded
- [ ] Conditions and follow-up actions assigned
