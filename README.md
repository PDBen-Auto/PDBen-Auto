# PDBen-Auto Agent Skills

Evidence-driven product research workflows for Amazon FBA teams, product managers, industrial designers, sourcing teams, and cross-border sellers.

This collection connects the work that is usually split across separate tools:

`market discovery -> multi-channel customer evidence -> design/IP risk -> product validation -> supplier and unit-economics decisions`

## Contact / 联系方式

For Skill customization, changes, or usage questions / 如需调整修改 Skill 或咨询使用方式，可添加地球号：`benliu2021`。

## Skills

| Skill | Use it for | Install |
| --- | --- | --- |
| [Amazon Review Intelligence](https://github.com/PDBen-Auto/amazon-review-intelligence-skill) | Collect written Amazon reviews, preserve evidence, export Excel/JSON, and turn VOC themes into product hypotheses. | `npx skills add PDBen-Auto/amazon-review-intelligence-skill --skill amazon-review-scraper` |
| [Multi-Channel Persona Research](https://github.com/PDBen-Auto/multi-channel-persona-research-skill) | Combine authorized reviews, communities, support, and behavior into evidence-traceable personas and A/B test plans across industries. | `npx skills add PDBen-Auto/multi-channel-persona-research-skill --skill multi-channel-persona-research` |
| [Amazon Product Research Agent Skills](https://github.com/PDBen-Auto/amazon-product-research-agent-skills) | Route market, customer, differentiation, supplier, and unit-economics work through one evidence contract. | `npx skills add PDBen-Auto/amazon-product-research-agent-skills --skill amazon-product-research-suite` |
| [SellerSprite Amazon Market Research BI](https://github.com/PDBen-Auto/sellersprite-amazon-market-research-bi-skill) | Expand keywords and competitor ASINs, filter relevant listings, deduplicate parent ASINs, and build auditable category BI. | `npx skills add PDBen-Auto/sellersprite-amazon-market-research-bi-skill --skill sellersprite-bi-market-research` |
| [Design Patent Search And Design Around](https://github.com/PDBen-Auto/design-patent-design-around-skill) | Pre-screen design-patent and industrial-design risk, explain drawing scope, and create structurally distinct redesign directions. | `npx skills add PDBen-Auto/design-patent-design-around-skill --skill design-patent-search-and-design-around` |
| [Patent Disclosure Drafting](https://github.com/PDBen-Auto/patent-disclosure-drafting-skill) | Turn product notes, drawings, and images into an evidence-labeled disclosure package for patent counsel review. | `npx skills add PDBen-Auto/patent-disclosure-drafting-skill --skill patent-disclosure-drafting` |
| [Amazon Product Decision Gateway](https://github.com/PDBen-Auto/amazon-product-decision-suite) | Validate a sanitized evidence bundle and hand it to a separately hosted private stage-gate decision engine. | `npx skills add PDBen-Auto/amazon-product-decision-suite --skill amazon-product-decision-gateway` |

## How the collection fits together

- **Discover the market:** SellerSprite BI establishes a reviewable market boundary before calculating competition or opportunity.
- **Understand customers:** Amazon Review Intelligence preserves original written reviews; Multi-Channel Persona Research combines authorized sources into behavioral segments, variant screening, and A/B test hypotheses.
- **Reduce design/IP risk:** Design Patent Search And Design Around turns public-record design rights into view-level risk notes and redesign work; Patent Disclosure Drafting organizes an invention or appearance concept for patent counsel review.
- **Make the investment decision:** Amazon Product Decision Gateway validates a cross-functional evidence bundle and, when configured, verifies a signed private-engine result.

## Shared standards

- Explicit `Inputs`, `Outputs`, dependencies, and stopping conditions.
- Evidence labels that distinguish observed facts, calculations, models, inferences, and assumptions.
- Synthetic public examples instead of customer, supplier, credential, or private account data.
- Self-contained local outputs where practical: JSON, CSV, Excel, and offline HTML.
- Public release provenance without hidden instructions, covert telemetry, or backdoors.

## Search terms

`Amazon product research`, `Amazon FBA product validation`, `Amazon review scraper`, `Amazon VOC`, `multi-channel persona research`, `behavioral segmentation`, `A/B test planning`, `SellerSprite market research`, `Amazon BI dashboard`, `ASIN research`, `competitor analysis`, `design patent search`, `design around`, `industrial design clearance`, `supplier sourcing`, `unit economics`, `go/no-go decision`, `Agent Skills`, `Codex Skills`, `亚马逊选品`, `亚马逊市场调研`, `用户画像`, `评论分析`, `外观专利检索`, `设计规避`。

## Boundaries

These repositories are source-available packages for inspection and evaluation. They do not grant permission to redistribute modified copies. Public-record patent workflows are not legal opinions; SellerSprite data is third-party estimation; Amazon review collection stops at CAPTCHA, Robot Check, sign-in walls, or account warnings; the Decision Gateway does not invent a private-engine result when the service is unavailable.
