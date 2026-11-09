# Graph Report - Ocean-spa  (2026-11-09)

## Corpus Check
- 13 files · ~11,235 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 2 file(s) not represented in the graph (top: (none) 2)

## Summary
- 85 nodes · 73 edges · 13 communities (11 shown, 2 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `6985ef0e`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Ocean Spa
- .claude/CLAUDE.md
- .mcp.json
- Strix Cloud (managed, no local infra)
- penetration-testing-with-strix/SKILL.md
- ci-security-scanning-with-strix/SKILL.md
- Find security vulnerabilities in code
- Security-test an API
- Application security testing
- Fix Strix findings and verify
- Test against the OWASP Top 10
- Pentest a web application
- 0. Credits & top-ups

## God Nodes (most connected - your core abstractions)
1. `Strix Cloud (managed, no local infra)` - 11 edges
2. `Ocean Spa` - 8 edges
3. `Find security vulnerabilities in code` - 6 edges
4. `Security-test an API` - 5 edges
5. `Application security testing` - 5 edges
6. `Fix Strix findings and verify` - 5 edges
7. `Test against the OWASP Top 10` - 5 edges
8. `Pentest a web application` - 5 edges
9. `0. Credits & top-ups` - 4 edges
10. `Option A — Self-hosted OSS CLI in the runner` - 3 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Import Cycles
- None detected.

## Communities (13 total, 2 thin omitted)

### Community 0 - "Ocean Spa"
Cohesion: 0.22
Nodes (8): 21st.dev Magic (مكوّنات واجهات), Context7 (توثيق المكتبات), graphify, Ocean Spa, Strix (اختبار الأمان), المهارات المفضّلة للمشروع, قواعد استخدام المهارات (توفير التوكن), مهارات خاصة بالمشروع

### Community 3 - "Strix Cloud (managed, no local infra)"
Cohesion: 0.17
Nodes (11): 1. Register the target as an asset, 2. Launch a scan, 3. Wait for completion, 4. Read findings, 5. Export & report, 6. PR reviews, 7. Continuous testing (schedules & webhooks), Safety (+3 more)

### Community 4 - "penetration-testing-with-strix/SKILL.md"
Cohesion: 0.18
Nodes (10): Exit codes (headless), Option A — Open-source CLI (self-hosted), Option B — Managed cloud (no local infra), Prerequisites, Reading results, Reporting & next steps, Run a Strix pentest, Running a scan (+2 more)

### Community 5 - "ci-security-scanning-with-strix/SKILL.md"
Cohesion: 0.29
Nodes (6): GitHub Actions, Option A — Self-hosted OSS CLI in the runner, Option B — Managed platform (no runner infra), Optional: upload findings to GitHub code scanning, Other CI systems, Set up Strix in CI/CD

### Community 6 - "Find security vulnerabilities in code"
Cohesion: 0.29
Nodes (6): Complementary tooling, Find security vulnerabilities in code, Fix and verify, Read the results, Reviewing a pull request instead of the whole repo, Run it

### Community 7 - "Security-test an API"
Cohesion: 0.33
Nodes (5): 1. Gather what the agents need, 2. Run the scan, 3. Verify findings, 4. Fix, re-test, and keep it tested, Security-test an API

### Community 8 - "Application security testing"
Cohesion: 0.33
Nodes (5): 1. Map the assets, 2. Pick the right test per asset, 3. Consolidate into one plan, 4. Be honest about coverage, Application security testing

### Community 9 - "Fix Strix findings and verify"
Cohesion: 0.33
Nodes (5): 1. Triage, 2. Fix, 3. Verify by re-running Strix, 4. Report, Fix Strix findings and verify

### Community 10 - "Test against the OWASP Top 10"
Cohesion: 0.33
Nodes (5): Report honestly, Run it, Test against the OWASP Top 10, Then fix and re-test, What is and is not testable by an agent

### Community 11 - "Pentest a web application"
Cohesion: 0.33
Nodes (5): 1. Confirm authorization and scope, 2. Run the scan, 3. Review results, 4. Fix and verify, Pentest a web application

### Community 12 - "0. Credits & top-ups"
Cohesion: 0.50
Nodes (4): 0. Credits & top-ups, Handoffs a person must finish, Organization knowledge, Workspaces and account setup

## Knowledge Gaps
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Strix Cloud (managed, no local infra)` connect `Strix Cloud (managed, no local infra)` to `0. Credits & top-ups`?**
  _High betweenness centrality (0.028) - this node is a cross-community bridge._
- **Why does `0. Credits & top-ups` connect `0. Credits & top-ups` to `Strix Cloud (managed, no local infra)`?**
  _High betweenness centrality (0.011) - this node is a cross-community bridge._