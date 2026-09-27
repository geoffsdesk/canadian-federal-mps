# Canadian Federal MPs: public record, lobbying contacts and ethics declarations

Generated 2026-09-27T23:01:42.900Z by SENTINEL. Public records about sitting Members of the House of Commons in their public role only. Nothing about private life. Every record carries its source.

**Licence:** Compiled dataset: CC BY 4.0. Underlying records remain subject to their sources: Open Government Licence - Canada (Parliament, Commissioner of Lobbying), CC0 (Wikidata), openparliament.ca terms.

| File | Tier | Model-derived fields |
|---|---|---|
| mps.json | DOCUMENTED | - |
| mps.csv | DOCUMENTED | - |
| social_accounts.csv | DOCUMENTED | - |
| committees.csv | DOCUMENTED | - |
| ethics_declarations.json | DOCUMENTED | - |
| ethics_declarations.csv | DOCUMENTED | - |
| lobbying_contacts.csv | DOCUMENTED | sector, kind |
| organisations.csv | DOCUMENTED | sector, kind, sector_confidence |
| votes.csv | DOCUMENTED | policy_area |
| correlations.json | DOCUMENTED | - |

Counts: mps 337 | social_accounts 423 | committee_seats 462 | ethics_declarations 3247 | lobbying_mp_org_pairs 37626 | lobbying_communications 71653 | organisations 3923 | votes 201 | correlations 123 | hypotheses 0

## Sources

- **House of Commons - Members open data**: roster, roles, committees, associations. https://www.ourcommons.ca/Members/en/search/XML
- **Represent (Open North)**: official photos, positions. https://represent.opennorth.ca/
- **Wikidata**: public social media accounts (CC0). https://www.wikidata.org/
- **openparliament.ca**: recorded votes, sponsored bills. https://openparliament.ca/
- **Office of the Conflict of Interest and Ethics Commissioner - public registry**: disclosure summaries, gifts, sponsored travel, recusals, reports. https://www.ethicscanada.ca/en/public-registry
- **Office of the Commissioner of Lobbying - Monthly Communication Reports**: registered communications with MPs (2008-07-14 to 2026-09-10). https://open.canada.ca/data/en/dataset/a34eb330-7136-4f5e-9f5f-3ba41df58b06
- **Jev (typesafe.ai)**: MODEL-DERIVED fields only: organisation sector/kind, vote policy_area. https://typesafe.ai/

## Read this before using correlations or hypotheses

A correlation is two documented records naming the same organisation for the same MP (for example a declared interest and a registered lobbying contact). It is a cross-reference, not a finding: a declared bank account plus that bank lobbying Parliament is the ordinary case.

not included in this build
