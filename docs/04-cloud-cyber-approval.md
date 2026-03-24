# Cloud and cyber approval

This page explains what the agency should provide for the cloud/cyber workstream.

## Goal

The agency needs a clear cloud/cyber decision before launch.

For this service, the expected path should usually be a **routine review** because GitHub Enterprise is an established SaaS platform. Requests that add nonstandard infrastructure, exceptions, or higher-risk use cases may need deeper review.

## What the agency should provide

### 1. Service summary

Provide:
- agency and program name
- business purpose
- short description of how GitHub will be used

### 2. Scope of GitHub use

State whether the organization will use GitHub for:
- source control only
- issues or project tracking
- documentation
- packages
- GitHub Actions or CI/CD
- release workflows or deployments
- other integrations

### 3. Data and content

Document:
- the expected data classification
- whether sensitive, regulated, or restricted data is expected in GitHub
- whether secrets or credentials will be stored in GitHub or managed elsewhere
- whether logs, issues, pull requests, and workflow output could contain sensitive content

### 4. Identity and access

Document:
- whether SSO is expected or required
- who the org admins will be
- whether outside collaborators will be allowed
- how user access will be removed when staff leave or no longer need access

> **Dependency:** SSO integration may be a prerequisite for cloud/cyber approval. Raise it early.

> **[DECISION NEEDED]** Is membership in the hosted Azure tenant required in order to join the ODA-managed GitHub Enterprise environment?

### 5. Baseline controls

Document the controls the agency expects to use, such as:
- team-based access
- protected branches or rulesets
- pull request review requirements
- secret scanning or code scanning if applicable
- review of dormant users and stale access
- support and escalation path

### 6. Cloud integrations

Call out whether the organization plans to use:
- GitHub Actions with cloud resources
- cloud credentials
- self-hosted runners
- Azure subscription billing
- other external integrations

### 7. AI, Copilot, and MCP

If the agency plans to use AI-related features, say so in the review:
- whether Copilot is requested
- whether coding agent, code review agent, or partner agents will be enabled
- whether MCP is planned
- whether MCP should be enabled only after privacy review
- what privacy risks MCP may create based on the systems it connects to

## What will usually trigger deeper review

Expect deeper review if the request includes any of the following:
- self-hosted runners
- storage of sensitive, regulated, or restricted data in GitHub
- production deployments or nonstandard cloud integrations
- requested exceptions to standard controls
- unclear ownership or admin model
- unresolved SSO or identity dependencies
- MCP or other integrations that raise privacy concerns

## How the template is structured

The cloud/cyber template is meant to summarize the proposed control posture for reviewer context.

Use the **baseline controls** section to record whether the agency plans to adopt ODA's standard controls or is asking for an exception. Use the **agency-specific use** and **integration** sections to document what is unique about the agency's use case.

The detailed implementation record still lives in the org-configuration workstream.

## When this workstream is done

This workstream is complete when the agency has:
- submitted the review information
- recorded whether the request follows the routine path or needs escalation
- documented any conditions or required follow-up actions
- received a cloud/cyber decision

Use the [Cloud/cyber approval template](../templates/servicenow-cloud-cyber-template.md) to submit this workstream.
