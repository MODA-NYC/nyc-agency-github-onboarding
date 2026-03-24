# Organization configuration

This page covers the decisions that define how the GitHub organization will be set up, governed, and operated.

## What this workstream decides

This workstream confirms:
- what the organization is for
- who will administer it
- how access will be managed
- which paid features will be enabled
- how identity, SSO, and outside collaborators will be handled
- what expectations apply to organization admins after launch

## Information you should be ready to provide

Before this workstream is complete, your agency should be able to state:
- the proposed organization name and purpose
- the initial user population
- the expected repository types and visibility
- the initial team structure
- the two proposed organization admins
- the paid features requested at launch
- whether SSO is expected or required
- whether outside collaborators will be allowed

## Decisions you need to make

### 1. Organization purpose and scope

Document:
- what the organization is for
- which teams or programs will use it
- whether it supports one product, one program, or a broader agency practice
- whether repositories are expected to be public, private, or mixed

### 2. Organization name and description

Choose:
- a clear organization name that can remain stable over time
- a short description that explains the purpose of the org
- a repository naming pattern if your agency wants one

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

Confirm:
- whether SSO is required for the organization
- whether SSO is expected for cloud/cyber approval
- whether outside collaborators are allowed and, if so, under what conditions
- how user access will be removed when staff change roles or leave

> **Dependency:** SSO integration may be a prerequisite for cloud/cyber approval. Identify this early instead of waiting for the review to surface it.

> **[DECISION NEEDED]** Is membership in the hosted Azure tenant required in order to join the ODA-managed GitHub Enterprise environment?

### 7. Paid features to enable at launch

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
- the org name and purpose
- two approved org admins
- the membership and team model
- the repository defaults and baseline controls
- the paid features requested at launch
- the identity, SSO, outside-collaborator, and Copilot/MCP decisions

Use the [Org configuration template](../templates/servicenow-org-configuration-template.md) to submit this workstream.
