# DRAFT! - NYC agency GitHub onboarding

> **WARNING:** This repository is a DRAFT of forthcoming guidance on how to get onboarded onto the doitt-nyc citywide GitHub Enterprise instance. Please consult with ODA before taking the steps outlined below.

This repository explains how an NYC agency requests and onboards an organization in the ODA-managed GitHub Enterprise environment.

This MVP focuses on the information an agency needs to submit now so onboarding can start without a separate orientation call.

This onboarding guide complements, and does not replace, the [NYC Citywide GitHub Policy (current public copy)](https://beta.nyc/wp-content/uploads/2016/05/Citywide-GitHub-Policy.pdf). NYC intends to update the older DoITT GitHub policy to reflect the current enterprise environment.

Onboarding requests are tracked through the Citywide Service Desk / ServiceNow process. `[DECISION NEEDED: add ServiceNow link]`

## Start here

- [Start here](docs/01-start-here.md)
- [Organization configuration](docs/02-org-configuration.md)
- [Funding approval](docs/03-funding-approval.md)
- [Cloud and cyber approval](docs/04-cloud-cyber-approval.md)
- [Onboarding checklist](docs/onboarding-checklist.md)

## ServiceNow templates

- [Parent request template](templates/servicenow-parent-request-template.md)
- [Funding approval template](templates/servicenow-funding-template.md)
- [Cloud/cyber approval template](templates/servicenow-cloud-cyber-template.md)
- [Org configuration template](templates/servicenow-org-configuration-template.md)

Some fields intentionally repeat across the workstream templates so each ticket can stand on its own if it is routed to a different team in ServiceNow.

## The three onboarding workstreams

Onboarding has three workstreams that can run in parallel:

1. **Configure the GitHub organization**
2. **Get funding approval**
3. **Get cloud/cyber approval**

Recommended model:
- open **one parent ServiceNow request**
- track the three workstreams as linked tasks or child tickets
- attach the estimate, approval materials, and configuration decisions to the parent request

If your agency needs to use separate tickets, link them together and name one agency point of contact.

## What to gather before you open a request

Before you submit, collect:

- agency name, business owner, technical owner, and primary requestor
- short purpose statement for the organization
- two proposed organization admins
- estimated number of users and paid features for the chosen funding path
- whether any users already have Visual Studio licenses tied to the same email address as their GitHub Enterprise accounts (these users do not need an additional GitHub Enterprise license)
- paid features requested, including whether Copilot is needed
- whether the agency already has an Azure subscription (ODA / Cloud Services can help identify an existing subscription and the Azure point of contact on file)
- whether the agency needs to migrate an existing GitHub organization or existing repositories into the enterprise
- whether outside collaborators or contractors will need access
- data sensitivity and any cloud/cyber concerns

> SSO is required for all organizations. `[DECISION NEEDED: set required SSO integration deadline to 60 or 90 days after onboarding]`

## About items marked `[DECISION NEEDED]`

A few process questions are still open. In this repo, those are marked as `[DECISION NEEDED]`.

Do not assume an answer for those items. Raise them in your intake ticket so ODA can route them for a policy decision.
