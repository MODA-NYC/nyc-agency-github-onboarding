# Funding approval

This page explains how to estimate cost, choose a payment path, and route the funding workstream.

## Goal

Before launch, the agency needs a funding decision that covers the GitHub organization and any paid features it plans to use.

## Questions to answer first

Before you build the funding request, confirm:
- number of users at launch, in 12 months, and in 36 months
- which paid features are needed
- whether the agency already has an Azure subscription
- if no Azure subscription exists, whether a new one must be created
- whether this is an older onboarding that may need a subscription created retroactively
- who owns the funding decision
- whether any requested Copilot users already have seats in another GitHub organization

## Step 1: Build the estimate

Use the Azure pricing calculator to estimate expected consumption.

Include the items your agency expects to pay for, such as:
- user counts
- Copilot seats
- Advanced Security
- Actions, Codespaces, or other paid usage if applicable

When using the calculator:
- you will **not** see enterprise pricing
- that is acceptable for approval purposes
- it is better to submit a higher estimate than to underestimate the request

Save the estimate output and the assumptions you used.

## Step 2: Choose a payment option

### Option A: Pay-As-You-Go (PayGo / Opex)

Use this option when the agency will pay for monthly usage as it occurs.

What this means:
- **no formal quote is required**
- the agency uses its estimated monthly consumption from the Azure pricing calculator
- the agency seeks **OMB funding approval** for the increased monthly spending

What to attach:
- the calculator estimate or a summary of the monthly estimate
- the assumptions behind the estimate
- the OMB approval or the documentation needed to route for OMB approval

### Option B: Monetary Commit (upfront)

Use this option when the agency wants to fund expected usage up front.

What this means:
- a **formal quote is required**
- the total amount should be based on **3 years of monthly estimated usage**
- the quote will show a **period of performance ending September 30, 2030**
- monetary commits are **use-it-or-lose-it**

> **Important:** Choose the Monetary Commit path only if the agency understands that unused committed funds are not preserved for later use.

What to attach:
- the formal quote
- the assumptions behind the 36-month estimate
- the selected payment option in the funding request

## Step 3: Route the request

### For PayGo

The funding request should clearly state:
- that PayGo is the selected payment option
- the estimated monthly consumption
- that no formal quote is required for this path
- the OMB approval status for the spending increase

### For Monetary Commit

Create the funding request with the formal quote attached and route it to the Strategic Sourcing team.

The request should clearly state:
- that Monetary Commit is the selected payment option
- the total amount requested
- that the estimate is based on 3 years of monthly usage
- that the agency understands the use-it-or-lose-it nature of the commit

## Step 4: Confirm Azure subscription status

The request must say whether an Azure subscription already exists.

If no Azure subscription exists:
- note whether the agency needs to create a new subscription
- note whether this is part of the backlog of agencies that may need to create subscriptions retroactively

Do not wait until the end of onboarding to surface this. Subscription status affects the path to launch.

## What happens after funding approval

After the funding workstream is approved:
1. Strategic Sourcing creates a ticket for ODA.
2. If the GitHub org needs to be connected to an Azure subscription, ODA may route the work to the Azure admin.
3. Temporary Azure admin permissions may be granted so the subscription connection can be completed.

## When this workstream is done

This workstream is complete when the agency has:
- documented the user and paid-feature assumptions
- selected a payment option
- attached the required estimate or quote for that option
- recorded the funding approval
- documented Azure subscription status and any follow-up needed

Use the [Funding approval template](../templates/servicenow-funding-template.md) to submit this workstream.
