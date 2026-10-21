# Hi, I'm Leigh Rodney 👋

**AI Researcher & Founder at Globe Teck.** Performance and systems test engineer with 15+ years of measuring, stress-testing and debugging real systems. Lately I design and run multi-agent AI workflows with human-in-the-loop guardrails. I'm moving into AI safety and security, where finding failure modes before they matter is the whole job.

📍 United States · 🔗 [LinkedIn](https://www.linkedin.com/in/leigh-rodney-60328581/)

## The pivot
I spent 15+ years in performance, systems and system test engineering at SiriusXM, Regeneron, STRATUS and 4D Security Solutions. That work came down to empirical measurement, pushing systems until they break, and tracing the failure back to its root cause.

Since mid-2025 I've applied the same habits to AI. I built and operate a set of coordinated AI agents with scoped permissions and human approval gates on every high-impact action. Running agents in practice taught me that guardrails, permission scoping and incident handling matter as much as capability. I'm now aiming that test-engineering mindset at AI systems themselves.

## What I'm looking for
- AI safety and security research
- Red teaming
- Evaluation engineering
- AI ops and agent workflows
- Performance engineering

## Skills
- **Performance and systems test engineering (15+ yrs)**: load and stress testing, bottleneck analysis, capacity, repeatable test harnesses and metrics you can trust
- **LLM red-teaming and evals**: adversarial test cases, scoring, regression tracking
- **Multi-agent orchestration with guardrails**: agent-to-agent routing, scheduled routines, human-in-the-loop approvals and permission scoping
- **Reliability**: debugging, failure-mode analysis, incident handling
- **Python** (basic, actively learning)

## Projects
- [**llm-redteam-harness**](https://github.com/leighsrodney-prog/llm-redteam-harness): a small Python harness for LLM red-team and eval suites (injection, jailbreak, PII leak) with pluggable adapters and a CI gate.
- [**gemini-mcp-server**](https://github.com/leighsrodney-prog/gemini-mcp-server): a tiny Python MCP stdio server for Google Gemini with retries, backoff, model fallback and mocked tests.
- [**agent-email-safety**](https://github.com/leighsrodney-prog/agent-email-safety): a sanitized write-up on protecting email-reading AI agents from prompt injection and code-mail leakage.
- [**agent-inbox-watcher**](https://github.com/leighsrodney-prog/agent-inbox-watcher): watches a folder inbox of markdown notes and wakes a lead agent through a webhook, by urgency.
- [**agent-box-oom-guard**](https://github.com/leighsrodney-prog/agent-box-oom-guard): a priority-aware OOM guard for shared Linux boxes running several AI agents with browsers.
- [**agent-shell-secret-mask**](https://github.com/leighsrodney-prog/agent-shell-secret-mask): env/printenv wrappers that mask secret values in shared AI-agent shells, with a leak test.
- [**offload-job-runner**](https://github.com/leighsrodney-prog/offload-job-runner): offloads heavy jobs from memory-tight boxes to GitHub Actions: dispatch, wait, pull artifacts back.
- [**trust-store-audit**](https://github.com/leighsrodney-prog/trust-store-audit): audits Linux/macOS trust stores for distrusted root CAs by SHA-256, with safe removal, backup and undo.
- [**site-checker**](https://github.com/leighsrodney-prog/site-checker): a passive website checker (status, speed, TLS expiry, security headers, broken links) with JSON and HTML reports.
- [**encrypted-backup-rotation**](https://github.com/leighsrodney-prog/encrypted-backup-rotation): 3-tier encrypted rotation of cPanel-style full backups (host, local, cloud) that verifies before deleting.
- [**cpanel-spam-filter-sync**](https://github.com/leighsrodney-prog/cpanel-spam-filter-sync): syncs YAML spam rules into cPanel server-side email filters through the UAPI, with dry-run and mocked tests.

Built with AI coding assistance. I defined the requirements, ran the tests, and reviewed the changes.
