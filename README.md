# B2B outbound benchmarks (ReplyLead open data)

First-party datasets on B2B cold email outcomes, the mail providers that receive business email, and what outbound providers charge. Each dataset is published with its method on replylead.com; this repository mirrors the files so they are easy to cite and reuse.

| Dataset | Files in `data/` | Source page and method |
| --- | --- | --- |
| Cold email outcomes by recipient email provider: 327,273 contacted leads, 97 campaigns, reply, interested and bounce rates for Google Workspace, Microsoft 365 and security gateways, with within-campaign ratios | `cold-email-outcomes-by-recipient-email-provider-2026.csv`, `.json` | [Cold email reply rates by email provider](https://replylead.com/cold-email-reply-rates-by-email-provider.html) |
| B2B email provider census: receiving provider for about 10.2M domains in B2B contact data | `b2b-email-provider-share-20260719.csv`, `.json` | [Email providers across 10.2M domains](https://replylead.com/b2b-email-provider-market-share.html) |
| Cold email reply-rate benchmark: campaign-level reply rates across 429,763 sends | `cold-email-benchmark-summary-20260812.csv`, `.json`, `cold-email-programme-sensitivity.csv`, `.json` | [Cold email benchmarks](https://replylead.com/cold-email-benchmarks.html) |
| B2B lead generation prices, price history (2024-2026) and contract terms for 14 providers | `b2b-lead-generation-companies-published-pricing-2026-09.*`, `b2b-lead-generation-price-history-2024-2026.*`, `b2b-lead-generation-provider-terms-2026-09.*` | [B2B lead generation companies](https://replylead.com/best-b2b-lead-generation-companies.html) |
| In-house seller cost, US and Canada: BLS OEWS wages, BLS ECEC benefits share, ESDC Job Bank wages | `in-house-sales-cost-us-canada-2026.csv`, `.json` | [Sales outsourcing: in-house cost](https://replylead.com/sales-outsourcing.html#in-house-cost) |

Each source page states the definitions, denominators, confidence intervals and limitations. Read them before comparing these numbers with other benchmarks: most describe one operator's campaign book, not a market-wide sample.

## License and attribution

The compilations are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Credit "ReplyLead" and link to the source page.

- US wage and benefits figures come from the U.S. Bureau of Labor Statistics and are in the public domain.
- Canadian wage figures contain information licensed under the [Open Government Licence - Canada](https://open.canada.ca/en/open-government-licence-canada) (source: Employment and Social Development Canada, Job Bank wages).

## Citation

ReplyLead (2026). *B2B outbound benchmarks*. https://github.com/replylead/b2b-outbound-benchmarks. See `CITATION.cff` for machine-readable metadata.

## Updates

We plan to refresh the datasets quarterly on replylead.com and mirror each release here. Each file name carries its version date; the source page records what changed.
