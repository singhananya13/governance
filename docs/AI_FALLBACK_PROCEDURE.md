# AI Fallback Procedure

**Document Owner:** Repository Administrator

**Version:** 1.0

**Approval Date:** 26-Jun-2026

**Review Date:** 26-Jun-2027

## Purpose

This procedure defines how software development activities continue if approved AI tools (e.g., GitHub Copilot, ChatGPT) become unavailable or cannot be used.

## Trigger Conditions

The fallback procedure shall be activated when:

* AI service outage or degraded performance
* AI service access revoked
* Organization policy temporarily prohibits AI usage
* Security incident affecting AI tools
* Confidentiality concerns requiring manual processing

## Manual Process by SDLC Activity

| SDLC Activity | AI-Assisted Process         | Manual Fallback                                 |
| ------------- | --------------------------- | ----------------------------------------------- |
| Requirements  | AI drafting                 | Business analyst manually prepares requirements |
| Design        | AI documentation assistance | Architect prepares design documents manually    |
| Coding        | Copilot suggestions         | Developers write code without AI assistance     |
| Code Review   | AI-assisted review          | Human peer review required                      |
| Testing       | AI-generated tests          | Test cases written manually                     |
| Documentation | AI-generated drafts         | Documentation authored manually                 |

## Responsible Personnel

* Repository Administrator
* Project Maintainer
* Assigned Code Reviewer

## Fallback Testing Cadence

Fallback procedures shall be tested quarterly.

## Escalation

If manual fallback cannot be completed within project timelines, the Repository Administrator shall notify project stakeholders and approve an alternate recovery plan.
