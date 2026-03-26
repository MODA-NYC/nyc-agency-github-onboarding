# Start here

Use this page before you open your onboarding request.

## What this process is for

This process is for NYC agencies that need an organization account in the ODA-managed GitHub Enterprise environment.

This onboarding guide complements, and does not replace, the [NYC Citywide GitHub Policy (current public copy)](https://beta.nyc/wp-content/uploads/2016/05/Citywide-GitHub-Policy.pdf). Agencies in this enterprise remain subject to NYC's existing GitHub policy framework. NYC intends to update the older DoITT GitHub policy to reflect the current enterprise environment.

The onboarding process has three workstreams:

1. **Organization configuration**
2. **Funding approval**
3. **Cloud/cyber approval**

These workstreams can usually run in parallel.

## Creating an onboarding ticket

NYC uses the Citywide Service Desk / ServiceNow to track onboarding requests and their progress across workstreams. Each onboarding request should be opened as a ServiceNow ticket so that funding, cloud/cyber review, and org configuration are tracked in one place.

`[DECISION NEEDED: add ServiceNow link]`

`[DECISION NEEDED: confirm whether all agencies have access to Citywide Service Desk / ServiceNow and define the fallback path if not]`

Preferred model:
- open **one parent ServiceNow request**
- create or link three workstream tasks beneath it
- attach all supporting documents to the parent request

Alternative model:
- open **three separate tickets**
- link them to one another
- identify one agency point of contact who will track the full onboarding effort

Some questions repeat across the workstream templates on purpose so each ticket can be routed and reviewed on its own.

## Questions to answer before you submit

### Agency and ownership

Be ready to provide:
- agency name
- program or business unit
- business owner
- technical owner
- primary requestor
- two proposed organization admins

### Scope of use

Be ready to describe:
- what the organization will be used for
- whether repositories will be public, private, or mixed
- whether contractors or other outside collaborators will need access
- whether the agency needs to migrate an existing GitHub organization or existing repositories into the enterprise
- whether this is a new onboarding or an update to an existing organization

> ODA standardizes organization naming. You do not need to propose an org name.

### Users and paid features

Estimate:
- the number of users for the funding path you plan to choose (see [Funding approval](03-funding-approval.md))
- paid features needed at launch
- paid features that may be added later
- if pursuing a Monetary Commit, include multi-year growth estimates to support the 3-year commitment

> **Visual Studio license note:** Users who already have Visual Studio licenses tied to the same email address as their GitHub Enterprise accounts do not need an additional GitHub Enterprise license. Account for this when estimating seat counts.

### Azure and funding

Answer these questions early:
- Does the agency already have an Azure subscription?
- Which payment path fits the request: Pay-As-You-Go or Monetary Commit?

> ODA / Cloud Services can help identify whether the agency already has an Azure subscription and, if so, provide the Azure point of contact on file. Raise this in your intake request if you are unsure.

> **Important:** Agencies using the Azure pricing calculator will not see enterprise pricing. That is acceptable. It is better to submit a higher estimate than to underestimate the request.

### Identity, cloud, and cyber

Be ready to identify:
- SSO plan and timeline — SSO is required for all organizations
- whether GitHub Actions, cloud credentials, or self-hosted runners are planned
- whether sensitive or regulated data is expected in GitHub
- whether the request looks like a routine SaaS review or may need deeper cloud/cyber review

`[DECISION NEEDED: set required SSO integration deadline to 60 or 90 days after onboarding]`

> **[DECISION NEEDED]** Is membership in the hosted Azure tenant required in order to join the ODA-managed GitHub Enterprise environment? Raise this question in intake if it affects your request.

## What to submit

At minimum, submit:
- one parent request or three linked requests
- the org configuration details
- the funding details
- the cloud/cyber details
- the estimate or quote, if one is required for your payment path

Use the templates in the `templates/` folder to structure the request.

## What happens after you submit

1. **ODA reviews the request and confirms the workstreams.** ODA checks the request for completeness and identifies what each workstream needs to proceed.
2. **Funding approval proceeds based on the agency's chosen payment option.** For Pay-As-You-Go, the agency submits a pricing calculator estimate for OMB approval. For Monetary Commit, a formal quote is obtained through Microsoft and submitted for approval.
3. **Cloud/cyber review proceeds using the standard GitHub Enterprise baseline plus any agency-specific use case details.** Most requests follow a routine review path. Requests with nonstandard infrastructure or higher-risk use cases may need deeper review.
4. **ODA finalizes org setup and any Azure subscription connection work.** If an Azure subscription needs to be connected to GitHub, ODA coordinates this internally.
5. **The agency designates org admins and completes required post-onboarding tasks such as SSO.** The agency validates access and begins ongoing administration per the responsibilities described in [Organization configuration](02-org-configuration.md).

## What a complete onboarding should produce

A completed onboarding should leave the agency with:
- an approved request record
- a funding decision and billing path
- a cloud/cyber decision
- a configured GitHub organization
- two named organization admins
- a documented record of the major setup decisions

## Next step

Continue to [Organization configuration](02-org-configuration.md).
