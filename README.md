# InsightfulPipe Skills for LinkedIn Ads

**7 free Claude skills for LinkedIn Ads: account audits, B2B lead generation, Lead Gen Form optimization and ABM pipeline reporting. Changes only after you confirm.**

Most of these skills also work from reports you export and paste in, with no account needed. Skills that need numbers read them live from your accounts when the InsightfulPipe MCP is connected.

Part of the free [InsightfulPipe marketing skills library](https://github.com/Insightful-Pipe/marketing-skills). Skills with a **Page** link have a page with a sample run at [insightfulpipe.com](https://insightfulpipe.com/marketing-claude-skills/linkedin-ads); newer ones get theirs soon.

## Install

### Claude Code

```
/plugin marketplace add Insightful-Pipe/linkedin-skills
/plugin install insightfulpipe-linkedin-ads@insightfulpipe-linkedin-ads
```

### Any agent: Claude Code, Codex, Cursor and others

```
npx skills add Insightful-Pipe/linkedin-skills
```

Add `--skill linkedin-ads-auditor` to install one skill.

### Claude.ai and Claude Desktop

Download a skill's ZIP from its page on insightfulpipe.com (the **Page** links below), or zip its folder from `skills/` if it has no page yet, then in Claude open **Customize > Skills**, choose **+ Create skill > Upload a skill** and pick the ZIP. Skills need code execution turned on.

## Skills (7)

| Skill | What it does | |
|---|---|---|
| [LinkedIn Abm Reporting](skills/linkedin-abm-reporting/) | Builds a LinkedIn Ads ABM report showing target account coverage, buying committee reach by seniority, matched audience and retargeting results, and a monthly funnel to… | [Page](https://insightfulpipe.com/marketing-claude-skills/linkedin-ads/linkedin-abm-reporting) |
| [LinkedIn Ad Copy Writer](skills/linkedin-ad-copy-writer/) | Writes LinkedIn ad copy from the account's lowest cost per lead ads, with character counts, for intro text, headlines, document, carousel, event, Message Ads and… |  |
| [LinkedIn Ads Auditor](skills/linkedin-ads-auditor/) | Audits a LinkedIn Ads account across tracking, structure, Audience Network, targeting, frequency, bidding, formats and lead quality, ranking fixes by spend at stake. | [Page](https://insightfulpipe.com/marketing-claude-skills/linkedin-ads/linkedin-ads-auditor) |
| [LinkedIn Ads B2B Optimizer](skills/linkedin-ads-b2b-optimizer/) | Optimizes LinkedIn Ads for B2B by finding which seniorities, job titles, company sizes and industries earn qualified leads, then fixes bids, budgets, weak ads and… | [Page](https://insightfulpipe.com/marketing-claude-skills/linkedin-ads/linkedin-ads-b2b-optimizer) |
| [LinkedIn Ads Campaign Builder](skills/linkedin-ads-campaign-builder/) | Builds a new LinkedIn Ads campaign or three-stage funnel from a brief, with objective, targeting, suggested bid pricing, intro text and headlines, a pre-flight check… | [Page](https://insightfulpipe.com/marketing-claude-skills/linkedin-ads/linkedin-ads-campaign-builder) |
| [LinkedIn Lead Gen Optimizer](skills/linkedin-lead-gen-optimizer/) | Reviews LinkedIn Lead Gen Forms for form design, open to completion drop-off, cost per lead by campaign and audience, and lead quality from work email share or CRM… | [Page](https://insightfulpipe.com/marketing-claude-skills/linkedin-ads/linkedin-lead-gen-optimizer) |
| [LinkedIn Thought Leader Ads Planner](skills/linkedin-thought-leader-ads-planner/) | Plans LinkedIn Thought Leader Ads by ranking founder, employee and creator posts against each author's usual engagement rate, then drafts the bid, budget per post and a… | [Page](https://insightfulpipe.com/marketing-claude-skills/linkedin-ads/linkedin-thought-leader-ads-planner) |

## Live data (optional)

Skills that read account data use the [InsightfulPipe MCP server](https://insightfulpipe.com/mcp-servers) when it's connected. Without it, each skill tells you which exports to paste in and works from those.

## What this plugin runs and sends

The plugin contains skills only: Markdown instructions (`SKILL.md`, `HOW_TO_USE.md`) and sample input and output files. It adds no hooks, commands or MCP servers, runs no code on your machine and sends no data anywhere by itself. When you have the InsightfulPipe MCP connected, Claude uses it to read your accounts, and makes a change only after you confirm it. The `scripts/` and `.github/` folders keep this repository in sync with insightfulpipe.com and are not part of what the plugin does.

## License

MIT. See [LICENSE](LICENSE).
