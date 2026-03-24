# Start here

Use this page before you open your onboarding request.

## What this process is for

This process is for NYC agencies that need an organization account in the ODA-managed GitHub Enterprise environment.

This onboarding guide complements, and does not replace, the [NYC Citywide GitHub Policy (current public copy)](https://beta.nyc/wp-content/uploads/2016/05/Citywide-GitHub-Policy.pdf). Agencies should still follow that policy's rules on allowable content, official account use, and administrator responsibilities.

The onboarding process has three workstreams:

1. **Organization configuration**
2. **Funding approval**
3. **Cloud/cyber approval**

These workstreams can usually run in parallel.

## Recommended ticket structure

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
- the proposed GitHub organization name
- what the organization will be used for
- whether repositories will be public, private, or mixed
- whether contractors or other outside collaborators will need access
- whether the request is for a new organization or an update to an existing one

### Users and paid features

Estimate:
- users at launch
- users in 12 months
- users in 36 months
- paid features needed at launch
- paid features that may be added later

### Azure and funding

Answer these questions early:
- Does the agency already have an Azure subscription?
- If not, does the agency need to create one for this onboarding?
- Is this an older onboarding that may need a subscription created retroactively?
- Which payment path fits the request: Pay-As-You-Go or Monetary Commit?

> **Important:** Agencies using the Azure pricing calculator will not see enterprise pricing. That is acceptable. It is better to submit a higher estimate than to underestimate the request.

### Identity, cloud, and cyber

Be ready to identify:
- whether SSO is expected or required
- whether GitHub Actions, cloud credentials, or self-hosted runners are planned
- whether sensitive or regulated data is expected in GitHub
- whether the request looks like a routine SaaS review or may need deeper cloud/cyber review

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

1. ODA checks the request for completeness.
2. The three workstreams begin.
3. Funding approval, cloud/cyber review, and org-configuration decisions move forward in parallel where possible.
4. After funding approval, the funding team creates a ticket for ODA.
5. If an Azure subscription needs to be connected to GitHub, ODA handles the internal connection steps and will contact the agency if anything additional is needed.
6. Once approvals are complete, ODA configures the organization and adds the approved organization admins.
7. The agency validates access and begins ongoing administration.

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
