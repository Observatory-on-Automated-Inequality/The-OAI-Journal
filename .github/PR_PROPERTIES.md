# Custom properties for pull requests

Every pull request in this repository declares these properties, in the pull request body, using the template in `pull_request_template.md`. The desk reads them before the text: a pull request with missing properties is sent back to be completed.

| Property | Values | Notes |
|---|---|---|
| Type | Investigation / Working paper / Synthesis / Exhibit / Correction / House | House means repository upkeep: documents, templates, structure. |
| Research line | Substrate Ledger / Sociology of Agent Communities / Sousveillance and Human Autonomy / Enclosure of the Agent Web / None | None is only for House pull requests. |
| Author | Name, and kind: Human or Agent | The byline the piece will carry. The author answers for the piece. |
| Language | English / French | The language the piece is written in. |
| Status | Draft / Ready for review | Drafts are visible work in progress; the desk reviews only Ready. |
| Evidence complete | Yes / Partial / No | Yes means every figure is published, dated, and sourced with a link a reader can check. Partial means some figures are sourced and the rest are named in the piece as still to be sourced. |
| Exhibits | A count, or None | Exhibits are numbered in the piece: Exhibit 01, Exhibit 02, and so on. |
| Private data | Confirmed none / Flagged for the desk | Never include private personal data. If evidence contains any, flag it and wait for the desk before pushing more. |
| Priority | Low / Normal / Urgent | Urgent is for corrections to published pieces and time-sensitive evidence. |
| Review effort | Low / Medium / High | Your honest estimate of the work the desk must do: Low, a short read; Medium, sources to check; High, exhibits and figures to verify. |

These properties follow the same spirit as the organization's issue fields (Type, Priority, Effort): small, declared up front, and read before anything else.

## Colors

Where a surface allows colors (labels, project fields, the journal's own pages), the properties use the design system's palette only: Ink Black #0A0A0A, Signal Red #E30613, Graphite #4A4A4A, Pale Grey #E8E8E8.

- Priority: Urgent #E30613, Normal #4A4A4A, Low #E8E8E8.
- Evidence complete: Yes #0A0A0A, Partial #4A4A4A, No #E30613.
- Status: Draft #E8E8E8, Ready for review #0A0A0A.
- Private data: Confirmed none #E8E8E8, Flagged for the desk #E30613.
- Type: Correction #E30613, every other type #0A0A0A.
- Research line, Author kind, Language, Review effort: #0A0A0A for all values.

Red stays reserved, as everywhere in the Observatory's system: it marks what blocks, what corrects, and what must be decided.
