[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Workflow](https://img.shields.io/badge/workflow-Research%20%E2%86%92%20SERP%20%E2%86%92%20Content-blue)](skills/programmatic-seo-writer.md)
[![Outputs](https://img.shields.io/badge/output-Metadata%20%7C%20Article%20%7C%20FAQ%20%7C%20GEO-orange)](skills/programmatic-seo-writer.md)

<!-- DAGENO_AGENT_NAV_START -->

**Dageno Agent Project Map / Dageno Agent 项目导航**

If this repo is useful, you may also want the adjacent Dageno Agent projects for GEO, SEO, AI visibility, and content operations.
如果这个仓库对你有帮助，也可以看看这些相邻的 Dageno Agent 项目，用于 GEO、SEO、AI 可见性和内容增长工作流。

| Stage / 阶段 | Project / 项目 | Use it for / 用途 |
| --- | --- | --- |
| Diagnose / 诊断 | [seo-geo-audit](https://github.com/dageno-agents/seo-geo-audit) | SEO + GEO audit workflows for brands and agencies / 面向品牌和服务商的 SEO + GEO 诊断工作流 |
| Topic + prompt generation / Topic + Prompt 生成 | [dageno-online-topic-prompt-generator](https://github.com/dageno-agents/dageno-online-topic-prompt-generator) | Generate Dageno-ready Topic clusters and high-intent monitoring prompts from a real domain / 基于真实网站生成可导入 Dageno 的 Topic 集群和高意图监控 Prompt |
| Content workflows / 内容生产 | [seo-geo-content-engine](https://github.com/dageno-agents/seo-geo-content-engine) | Full SEO/GEO content workflows / 完整 SEO/GEO 内容工作流 |
| Fanout writing / Fanout 写作 | [geo-content-writer](https://github.com/dageno-agents/geo-content-writer) | Turn Dageno fanout into briefs, drafts, and review contracts / 把 Dageno fanout 变成 brief、draft 和 review contract |
| Organic intelligence / 自然增长分析 | [organic-content-intelligence](https://github.com/dageno-agents/organic-content-intelligence) | Search demand, page funnels, intent coverage, and GEO visibility / 搜索需求、页面漏斗、意图覆盖和 GEO 可见性分析 |
| Site architecture / 站点架构 | [geo-site-architecture-audit](https://github.com/dageno-agents/geo-site-architecture-audit) | Audit site structure and turn it into GEO-ready content recommendations / 诊断网站结构并输出 GEO 内容与内链建议 |
| Brand AI performance / 品牌 AI 表现 | [brand-ai-performance-check](https://github.com/dageno-agents/brand-ai-performance-check) | Dense brand diagnostic reports from Dageno API or custom input / 基于 Dageno API 或自定义数据生成品牌 AI 诊断报告 |
| Automation / 自动化 | [n8n-nodes-dageno](https://github.com/dageno-agents/n8n-nodes-dageno) | Dageno API node for n8n automation / 用于 n8n 自动化的 Dageno API 节点 |
| API + MCP playbook / API 与 MCP | [dageno-mcp-growth-playbook](https://github.com/dageno-agents/dageno-mcp-growth-playbook) | GEO reporting, prompt gaps, citation intelligence, and growth execution / GEO 报告、Prompt Gap、引用分析和增长执行手册 |

More projects / 更多项目: [geo-visual-content-engine](https://github.com/dageno-agents/geo-visual-content-engine), [seo-outreach-skill](https://github.com/dageno-agents/seo-outreach-skill), [geo-pre-sale-report-private](https://github.com/dageno-agents/geo-pre-sale-report-private), [GEO-SEO](https://github.com/dageno-agents/GEO-SEO).

Explore all repos / 查看全部项目: [github.com/dageno-agents](https://github.com/dageno-agents) · Product / 产品: [Dageno](https://dageno.ai/?utm_source=github&utm_medium=social&utm_campaign=official)

<!-- DAGENO_AGENT_NAV_END -->

# SEO GEO Content Engine

![SEO GEO Content Engine Cover](assets/cover.svg)

> Turn keywords into search- and AI-ready content pipelines with automated research, SERP analysis, writing, and optimization.

**Positioning**

SEO GEO Content Engine is a content production system for teams that want more than one-off article generation.

It is designed to turn a target keyword into:

- validated search intent
- SERP-aware content structure
- publish-ready long-form content
- metadata and FAQ schema
- AI-friendly versions for answer engines

This project helps answer a practical growth question:

> How do you turn keyword opportunities into scalable content output without losing search quality or AI visibility?

**Outcome**

Instead of treating research, writing, metadata, and GEO optimization as separate tasks, this project organizes them into one repeatable pipeline.

## Best For

- SEO teams scaling content production without turning into generic AI writing
- SaaS and DTC teams building search-ready and AI-answer-ready content systems
- agencies that need one workflow for keyword research, SERP analysis, writing, and packaging
- operators who want publishable output instead of disconnected research notes

## Start With These Prompts

```text
write article: best llm observability tools
```

```text
create SEO content for ai seo tracking
```

```text
show available keywords
```

## External Access And Minimum Credentials

This skill may use:

- a keyword tracker such as Google Sheets
- a vetted search API such as SerpAPI for live SERP analysis

Recommended minimum setup:

- `GOOGLE_SHEETS_TRACKER_URL`: read-only or public keyword tracker
- `SERPAPI_API_KEY`: live search retrieval

If those are not available, the workflow should fall back to user-provided keyword lists, CSV exports, or pasted SERP data instead of assuming hidden access.

Access policy:

- external tracker access is optional, not required
- live SERP retrieval is optional, not required
- the workflow should not assume private-sheet access or direct scraping by default
- if integrations are missing, it should continue from user-provided inputs

**About Dageno.ai**

[Dageno.ai](https://dageno.ai) is an AI SEO platform for brands, SaaS teams, SEO operators, agencies, and AI-search growth teams that want to scale search- and AI-ready content production across both traditional search and answer engines.

## Why It Feels Different

Most AI writing tools start too late.

They generate articles before fully resolving:

- search intent
- SERP patterns
- content gaps
- metadata strategy
- AI-answer packaging

This project is built to start earlier and finish later:

- earlier with keyword and SERP analysis
- later with metadata, FAQ schema, and GEO-ready output

## What You Get

- one keyword-to-content workflow
- one reusable writing pipeline
- one structure for SEO and AI answer engines
- one output format that is ready for publishing or handoff

## Who This Is For

- Shopify and DTC brands building search and AI content at scale
- SaaS teams creating comparison, alternative, and educational content
- SEO and digital marketing operators who need repeatable production workflows
- agencies that manage programmatic content systems across multiple clients

## Pipeline

```mermaid
flowchart LR
    A["Keyword Input"] --> B["Keyword Expansion"]
    B --> C["SERP Analysis"]
    C --> D["Content Blueprint"]
    D --> E["Long-Form Draft"]
    E --> F["Metadata & FAQ Schema"]
    F --> G["GEO Version"]
    G --> H["Publish-Ready Package"]
```

## What The System Produces

For one keyword, the pipeline can produce:

- keyword framing and expansion
- search intent analysis
- SERP-derived content structure
- full article draft
- title and meta description
- FAQ block with schema-ready output
- GEO version designed for AI-driven discovery

## Example Prompts

```text
write article: best llm observability tools
```

```text
create SEO content for ai seo tracking
```

```text
force framework B: programmatic seo for saas
```

```text
show available keywords
```

## Example Output

```text
Keyword
- ai seo tracking

Search Intent
- Commercial investigation

SERP Pattern
- Tool roundups dominate
- Buyers want comparisons, pricing visibility, and workflow examples

Content Package
- Title: 12 AI SEO Tracking Tools for 2026
- Meta Description: Compare the best AI SEO tracking tools for rankings, AI visibility, and prompt coverage.
- H1/H2 outline
- Full article draft
- FAQ section
- FAQ schema
- GEO version optimized for answer extraction
```

## Why Teams Use It

### Traditional Content Workflow

- keyword research in one tool
- SERP review in another
- article writing somewhere else
- metadata added later
- GEO considerations often missing

### With Programmatic SEO

- research, writing, metadata, and GEO live in one pipeline
- output follows one consistent structure
- teams can scale production without losing quality controls

## Skill Entry Point

The core skill lives here:

- [`skills/programmatic-seo-writer.md`](skills/programmatic-seo-writer.md)

Use it when you want a repeatable SEO + GEO writing workflow rather than a generic text generator.

## Repo Structure

```text
seo-geo-content-engine/
├── README.md
├── LICENSE
├── assets/
│   └── cover.svg
└── skills/
    └── programmatic-seo-writer.md
```

## Recommended Use Cases

- build a scalable content backlog
- generate publish-ready SEO articles faster
- package content for both search and AI answers
- standardize content production across a team

## License

MIT
