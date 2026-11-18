# Hi, I'm Moni Kumari

Senior software engineer in test, moving into **application security**.

For 7+ years I built test automation and backend features in Java and C# (.NET Core), with Kafka, RabbitMQ, Conductor and Jenkins. I'm now moving into application security and building a public portfolio: hands-on labs, a C# API with authorization flaws that are fixed and proven by tests, security scans in CI, and security tests for an AI agent. I write up what I learn.

**Looking for:** entry-level remote Application Security / Product Security roles.

## What I'm building

All projects use a fictional company, **Northstar Orders**, with synthetic data only.

| Repo | What it shows | Status |
| --- | --- | --- |
| [northstar-secure-saas-api](https://github.com/moni-kumari-sec/northstar-secure-saas-api) | Multi-tenant C# / ASP.NET Core API. Three planted authorization flaws (BOLA, BFLA, mass assignment), each fixed and proven with regression and bypass tests: 20 tests, 14 of them bypass tests. Semgrep and Trivy run in GitHub Actions, with a written triage of the results. | 3 findings done |
| [northstar-ai-agent-evals](https://github.com/moni-kumari-sec/northstar-ai-agent-evals) | Python harness that attacks a mock AI support agent: 21 cases covering prompt injection, cross-customer access, refund abuse and prompt leakage, scored by an independent judge. Four guards, measured one at a time. 39 tests. A comparison with a real model is planned. | First version done |
| [appsec-notes](https://github.com/moni-kumari-sec/appsec-notes) | Lab write-ups and finding reports (PortSwigger Web Security Academy, OWASP) | In progress |

## What I'm learning and practicing

- **Web and API security:** broken object-level and function-level authorization, mass assignment, injection, authentication and session flaws
- **AI agent security:** prompt injection, tool permissions, data leakage (OWASP Top 10 for LLM Applications)
- **Secure code review and threat modeling:** STRIDE, data-flow diagrams, line-level fixes
- **Tools:** Burp Suite, Semgrep, Trivy, OWASP ZAP, GitHub Actions
- **Languages:** C# and Java (daily use), Python and JavaScript (reading and scripting)
- **Testing background:** regression suites, flaky-test triage, release gates, failure analysis

## How I work

- Every finding has a failing test, a fix, and at least two bypass tests.
- Everything runs locally. No real systems, no real data, no employer code.
- Results are measured, and I say what I did not test.

## Contact

[LinkedIn](https://www.linkedin.com/in/monipandey/)
