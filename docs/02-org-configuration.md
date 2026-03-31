# Organization configuration
> **WARNING:** This repository is a DRAFT of forthcoming guidance on how to get onboarded onto the doitt-nyc citywide GitHub Enterprise instance. Please consult with ODA before taking the steps outlined below.

This page is the source of truth for how a GitHub organization will be set up, governed, and operated. It covers the decisions agencies need to make and the responsibilities org admins must carry after launch.

## What this workstream decides

This workstream confirms:
- what the organization is for
- who will administer it
- how access will be managed
- which paid features will be enabled
- how identity, SSO, and outside collaborators will be handled
- whether an existing GitHub organization or repositories need to be migrated into the enterprise
- what expectations apply to organization admins after launch

## Information you should be ready to provide

Before this workstream is complete, your agency should be able to state:
- the purpose of the organization
- the initial user population
- the expected repository types and visibility
- the initial team structure
- the two proposed organization admins
- the paid features requested at launch
- the SSO integration plan and timeline
- whether outside collaborators will be allowed
- whether an existing GitHub organization or existing repositories need to be migrated

## Decisions you need to make

### 1. Organization purpose and scope

Document:
- what the organization is for
- which teams or programs will use it
- whether it supports one product, one program, or a broader agency practice
- whether repositories are expected to be public, private, or mixed

### 2. Organization name and description

ODA standardizes organization naming to maintain consistency across the enterprise. You do not need to propose an org name. Instead, provide:
- a short description that explains the purpose of the org
- a repository naming pattern if your agency wants one

ODA will assign the organization name based on city naming conventions.

### 3. Organization admins

You must identify **at least two** organization admins.

Your org admins should be people who can:
- manage membership and teams
- approve or route access requests
- coordinate with ODA on setup and troubleshooting
- maintain continuity when staff changes

### 4. Membership and team structure

Decide:
- which users should be direct members
- which access should be managed through teams
- whether outside collaborators will be allowed
- who can approve new members and outside collaborators

Use teams where possible instead of one-off direct repository permissions.

### 5. Repository defaults and baseline controls

Set expectations for:
- repository visibility
- protected branches or rulesets for active repositories
- pull request review requirements
- required status checks, if applicable
- code ownership, labels, templates, and README standards
- how secrets and credentials will be handled

### 6. Identity and SSO

SSO is required for all organizations in the ODA-managed enterprise.

`[DECISION NEEDED: set required SSO integration deadline to 60 or 90 days after onboarding]`

Confirm:
- the SSO integration plan and timeline
- whether outside collaborators are allowed and, if so, under what conditions
- how user access will be removed when staff change roles or leave

> **Dependency:** SSO integration may be a prerequisite for cloud/cyber approval. Identify this early instead of waiting for the review to surface it.

> **[DECISION NEEDED]** Is membership in the hosted Azure tenant required in order to join the ODA-managed GitHub Enterprise environment?

### 7. Migration of existing organizations or repositories

If the agency has an existing GitHub organization or repositories outside the ODA-managed enterprise, document:
- the existing organization name and URL
- the number of repositories to migrate
- whether the migration involves active repositories with open pull requests, issues, or CI/CD workflows
- any dependencies or integrations that would be affected by migration
- the preferred migration timeline

ODA will coordinate the migration process. Agencies should not attempt to move organizations or repositories into the enterprise without ODA involvement.

### 8. Paid features to enable at launch

Only request paid features that the agency expects to use and is prepared to fund.

Common examples include:
- Copilot
- Advanced Security
- GitHub Actions beyond included allowances
- Codespaces
- other paid add-ons

If you are unsure whether to enable a paid feature at launch, document it as a future request instead of enabling it by default.

## Copilot, AI, and MCP policy

If your agency wants Copilot or other AI-assisted features, document that during onboarding.

### Copilot models

Current policy:
- organizations should balance cost and functionality based on budget and use case
- the default posture is to let organizations decide what models to make available to their users
- for NYC onboarding, orgs may choose among **Anthropic Claude, Google Gemini, and OpenAI GPT**
- preview models are currently allowed; org admins should use discretion before enabling them broadly
- **all Grok models are disabled everywhere** as an enterprise-level decision

### Copilot agents

Current policy:
- coding agent: let orgs decide
- code review agent: let orgs decide
- partner agents: allowed for orgs to install

Future control that may be added later:
- custom agents are not part of this MVP onboarding flow; in a later phase, ODA may define rulesets so only enterprise admins can edit custom-agent source code

### MCP (Model Context Protocol)

Current policy:
- orgs may request MCP based on their use case
- treat MCP as a privacy review item, not just a feature toggle
- if the org plans to use MCP, document what external systems it will connect to and what context may leave GitHub
- if MCP is requested, it should be enabled intentionally rather than assumed by default

Potential later control:
- ODA may move to a curated MCP URL whitelist in a future phase

### Copilot cost management

Before assigning Copilot seats, identify any user who already has a Copilot seat in another GitHub organization. This is a cost-optimization check and should be recorded during onboarding.

## What org admins are expected to do

Being an org admin is an ongoing responsibility, not just a setup role.

Org admins are expected to:
- disseminate ODA guidance to their users
- maintain organization settings over time
- be responsive to their users and to ODA
- notify ODA and identify a successor if they are leaving the city
- manage dormant users and remove access that is no longer needed

Your agency should not name an org admin unless that person is prepared to carry those responsibilities.

## When this workstream is done

This workstream is complete when the agency has documented:
- the org purpose
- two approved org admins
- the membership and team model
- the repository defaults and baseline controls
- the migration plan, if applicable
- the SSO integration plan and timeline
- the paid features requested at launch
- the Copilot/MCP decisions

Use the [Org configuration template](../templates/servicenow-org-configuration-template.md) to submit this workstream.
