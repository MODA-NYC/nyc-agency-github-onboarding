# Funding approval
> **WARNING:** This repository is a DRAFT of forthcoming guidance on how to get onboarded onto the doitt-nyc citywide GitHub Enterprise instance. Please consult with ODA before taking the steps outlined below.

This page explains how to estimate cost, choose a payment path, and route the funding workstream.

## Goal

Before launch, the agency needs a funding decision that covers the GitHub organization and any paid features it plans to use.

## Funding workflow at a glance

1. Confirm whether the agency already has an Azure subscription.
2. If needed, work with ODA / Cloud Services to identify an existing subscription and the Azure point of contact on file.
3. Estimate GitHub seats and paid features.
4. Account for users who already have Visual Studio licenses tied to the same email address as their GitHub Enterprise accounts — these users do not need an additional GitHub Enterprise license.
5. Choose Pay-As-You-Go or Monetary Commit.
6. If Pay-As-You-Go: no formal quote is required. Use the Azure pricing calculator estimate for OMB approval of the spending increase.
7. If Monetary Commit: obtain a formal quote through Microsoft based on 3 years of estimated usage and submit it for approval.
8. After approval, ODA handles the Azure subscription connection steps.

## Step 1: Confirm Azure subscription status

Before building the estimate, confirm:
- whether the agency already has an Azure subscription
- the subscription name or ID, if known

> ODA / Cloud Services can help identify whether the agency already has an Azure subscription and, if so, provide the Azure point of contact on file. Raise this in your intake request if you are unsure.

If the agency is moving an existing GitHub organization or an earlier onboarding into the ODA-managed enterprise, ODA may need to create or connect an Azure subscription after the fact. Note this in your request.

## Step 2: Build the estimate

Estimate the number of users and paid features the agency expects to use.

Include the items your agency expects to pay for, such as:
- user counts
- Copilot seats
- Advanced Security
- Actions, Codespaces, or other paid usage if applicable

> **Visual Studio license note:** Users who already have Visual Studio licenses tied to the same email address as their GitHub Enterprise accounts do not need an additional GitHub Enterprise license. Account for this when estimating seat counts.

Use the Azure pricing calculator to build the estimate.

When using the calculator:
- you will **not** see enterprise pricing
- that is acceptable for approval purposes
- it is better to submit a higher estimate than to underestimate the request

Save the estimate output and the assumptions you used.

## Step 3: Choose a payment option

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
- a **formal quote is required**, obtained through Microsoft
- the total amount should be based on **3 years of estimated monthly usage**, including multi-year growth estimates
- the quote will show a **period of performance ending September 30, 2030**
- monetary commits are **use-it-or-lose-it**

> **Important:** Choose the Monetary Commit path only if the agency understands that unused committed funds are not preserved for later use.

What to attach:
- the formal quote from Microsoft
- the assumptions behind the 3-year estimate
- the selected payment option in the funding request

## Step 4: Route the request

### For Pay-As-You-Go

The funding request should clearly state:
- that Pay-As-You-Go is the selected payment option
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

## What happens after funding approval

After the funding workstream is approved:
1. The approval is routed to ODA.
2. If the GitHub org needs to be connected to an Azure subscription, ODA coordinates the connection steps internally.
3. ODA will contact the agency if anything additional is needed to complete the subscription connection.

## When this workstream is done

This workstream is complete when the agency has:
- confirmed Azure subscription status
- documented the user and paid-feature assumptions, including the Visual Studio license check
- selected a payment option
- attached the required estimate or quote for that option
- recorded the funding approval
- documented any Azure subscription follow-up needed

Use the [Funding approval template](../templates/servicenow-funding-template.md) to submit this workstream.
