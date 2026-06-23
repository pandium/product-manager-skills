# Integration PRD & Spec Writer

A Claude-compatible skill that helps product managers create complete, implementation-ready integration PRDs and technical specs for B2B SaaS integrations.

Product managers building integrations often start with scattered notes, one-off customer requests, and incomplete technical constraints. Pandium created this skill to help teams turn that ambiguity into a structured, decision-ready integration document.

## What it does

This skill helps you draft a structured integration document covering:

- Business context and objectives
- GTM and commercial strategy
- Integration architecture and data flow
- Supported data flows and field mappings
- System constraints and expectations
- Operability, monitoring, and error handling
- Non-functional requirements
- Lifecycle, versioning, assumptions, and risks

You can create a PRD, and integration specification document, or both of these combined into one document. 

## Who it is for

- Product Managers
- Technical Product Managers
- Integration Leads
- Solutions Architects
- Partner-facing product teams

## Best use cases

Use this skill when you need to:

- Create a new integration PRD from scratch
- Turn rough notes into a structured integration spec
- Align Product, Engineering, GTM, Support, and Partnerships on requirements
- Identify missing technical and operational details early
- Create a reusable template for integration planning

## Files

- `SKILL.md` — the full skill definition and instructions

## How to use

1. Download or copy the `SKILL.md` file.
2. Add it to your Claude Skills workflow or use it as a prompt template.
3. Start with a short description of the systems, entities, and flows you want to integrate.
4. Let the skill guide you through discovery and generate a structured PRD and/or spec.

## Example prompts

Here are some example ways to invoke the skill:

- **Create a new integration PRD**

  > Use the integration PRD skill. I want to design a HubSpot–NetSuite integration that syncs companies and invoices. Ask me whatever you need, then produce a complete integration specification document following your standard sections.

- **Refine an existing draft**

  > Here is a rough idea for a Zendesk–Jira integration. Use the integration PRD skill to turn this into a complete integration spec. Ask follow-up questions where details are missing, especially for data flows, field mappings, and error handling.

- **Focus on data flows**

  > Use the integration PRD skill, but concentrate only on Supported Data Flows and Field Mapping for a Salesforce–Snowflake integration. You can assume a standard GTM strategy and skip that section.

## Output structure

The skill is designed to generate a document with these sections:

1. Integration Project Overview / Business Context
2. GTM / Commercial Strategy
3. Integration Architecture / Data Flow Overview
4. Supported Data Flows / Field Mapping
5. System Constraints / Expectations
6. Operability, Monitoring / Error Handling
7. Non-Functional Requirements
8. Integration Lifecycle / Versioning
9. Dependencies, Assumptions / Risks
10. Out of Scope / Open Questions

Each section is written so that Product, Engineering, GTM, Support, and Partnerships teams can all understand and act on it.

## Why we published this

Most PM templates treat integrations like ordinary features. This skill is designed specifically for customer-facing B2B SaaS integrations, where architecture, partner constraints, data contracts, operations, and GTM all matter.

## About Pandium

Pandium is an embedded iPaaS designed to help SaaS companies launch customer-facing integrations faster by reducing the engineering burden around authentication, orchestration, deployment, monitoring, and ongoing maintenance.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
