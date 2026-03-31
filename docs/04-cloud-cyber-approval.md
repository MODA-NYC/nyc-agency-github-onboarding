# Cloud and cyber approval
> **WARNING:** This repository is a DRAFT of forthcoming guidance on how to get onboarded onto the doitt-nyc citywide GitHub Enterprise instance. Please consult with ODA before taking the steps outlined below.

This page explains the cloud/cyber review process for agencies onboarding to the ODA-managed GitHub Enterprise environment.

## Goal

The agency needs a clear cloud/cyber decision before launch.

## What to expect

GitHub Enterprise is an established SaaS platform. The cloud/cyber review for this service is expected to be a **routine review** in most cases.

Agencies may need to paste standard boilerplate into the relevant cloud/cyber review request and then add agency-specific details about their use case. The boilerplate is available in the [cloud/cyber review boilerplate template](../templates/servicenow-cloud-cyber-template.md).

Requests that add nonstandard infrastructure, exceptions, or higher-risk use cases may need deeper review.

## Standard baseline vs. agency-specific details

### Standard baseline (provided or expected by ODA)

The following controls and governance points apply to all organizations in the ODA-managed enterprise. This baseline information should be included in the review request:

- **Org admin model:** at least two designated org admins per organization
- **Access control:** team-based access management
- **Repository visibility:** compliant with NYC GitHub policy; agencies document whether repos are public, private, or mixed
- **SSO requirement:** SSO is required for all organizations `[DECISION NEEDED: set required SSO integration deadline to 60 or 90 days after onboarding]`
- **Copilot / AI / MCP governance:** managed per the policy described in [Organization configuration](02-org-configuration.md), including model restrictions and privacy review requirements for MCP

### Agency-specific details (the agency must provide)

Each agency should add the following information to the review request:

- **Use case:** what the organization will be used for
- **Data sensitivity:** expected data classification and whether sensitive, regulated, or restricted data will be stored in GitHub
- **Existing org / repo migration:** whether an existing GitHub organization or repositories are being migrated into the enterprise
- **External collaborators:** whether outside collaborators or contractors will need access
- **AI / agent / MCP usage:** whether the agency plans to use Copilot, coding agents, code review agents, partner agents, or MCP, and any specific privacy considerations
- **Anything unusual:** self-hosted runners, cloud credentials, production deployments, or anything else the reviewer should know

## Tracking

The parent onboarding ticket is the tracker of record. If the cloud/cyber review requires a separate review ticket, the separate ticket number and status should be recorded in the parent onboarding ticket.

## SSO dependency

SSO may be a dependency for cloud/cyber approval or completion. Agencies should identify their SSO plan and timeline early in the process.

`[DECISION NEEDED: set required SSO integration deadline to 60 or 90 days after onboarding]`

> **[DECISION NEEDED]** Is membership in the hosted Azure tenant required in order to join the ODA-managed GitHub Enterprise environment?

## What will usually trigger deeper review

Expect deeper review if the request includes any of the following:
- self-hosted runners
- storage of sensitive, regulated, or restricted data in GitHub
- production deployments or nonstandard cloud integrations
- requested exceptions to standard controls
- unclear ownership or admin model
- unresolved SSO or identity dependencies
- MCP or other integrations that raise privacy concerns

## When this workstream is done

This workstream is complete when the agency has:
- submitted the review information (standard boilerplate plus agency-specific details)
- recorded whether the request follows the routine path or needs escalation
- documented any conditions or required follow-up actions
- received a cloud/cyber decision
- recorded the review ticket number in the parent onboarding ticket, if applicable

Use the [cloud/cyber review boilerplate template](../templates/servicenow-cloud-cyber-template.md) to prepare the review submission.
