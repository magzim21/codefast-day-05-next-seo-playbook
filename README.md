# Codefast Day 05 · Next SEO Playbook

## Mission
- Automate SEO audits using Lighthouse, sitemap generation, and hreflang coverage for multi-locale sites.
- Provide a repeatable workflow for running audits locally, in CI, and via scheduled jobs.

## Implementation Checklist
1. Build a sitemap + alternate locale indexer that respects canonical logic and dynamic routes.
2. Automate Lighthouse runs across top URLs, storing JSON results and thresholds in repo.
3. Generate per-route SEO reports with detected regressions and actionable checklist.
4. Integrate Datadog RUM Web Vitals with SEO audit outputs to correlate performance and search ranking.

## Telemetry & QA
- Send Lighthouse and Core Web Vital summaries to Datadog dashboards.
- Validate structured data with schema.org testing utilities, adding unit tests for metadata builders.

## Deliverables
- README detailing audit commands, schedule suggestions, and interpreting results.
- Template issue for SEO regressions with pre-filled reproduction steps.
