# Lynceus — live job listings, straight from company careers pages

**201,883 open roles** at **7,791 companies**,
**32,540** of them remote. Read from each employer's own careers
page and job feed — never reposted from another board.

_Last updated: 2026-08-15 15:39 UTC_

Search it conversationally at **[app.trylynceus.com](https://app.trylynceus.com)** — describe
what you want in plain English and get the companies actually hiring for it.

## Browse

- [Remote](boards/remote.md) — 32,540 roles
- [Berlin](boards/berlin.md) — 2,509 roles
- [London](boards/london.md) — 5,828 roles
- [Paris](boards/paris.md) — 1,949 roles
- [Amsterdam](boards/amsterdam.md) — 1,445 roles
- [Munich](boards/munich.md) — 1,282 roles
- [Madrid](boards/madrid.md) — 794 roles
- [Barcelona](boards/barcelona.md) — 754 roles
- [Dublin](boards/dublin.md) — 867 roles
- [Lisbon](boards/lisbon.md) — 354 roles
- [Zurich](boards/zurich.md) — 231 roles
- [Stockholm](boards/stockholm.md) — 295 roles
- [New York](boards/new-york.md) — 9,857 roles
- [San Francisco](boards/san-francisco.md) — 8,292 roles
- [Engineering](boards/engineering.md) — 44,788 roles
- [Data & AI](boards/data-ai.md) — 28,029 roles
- [Design](boards/design.md) — 10,006 roles
- [Product](boards/product.md) — 9,947 roles
- [Sales](boards/sales.md) — 17,134 roles
- [Marketing](boards/marketing.md) — 8,406 roles

## Data

| File | What it is |
| --- | --- |
| [`data/jobs.csv`](data/jobs.csv) | The 5,000 most recently posted roles |
| [`data/jobs.json`](data/jobs.json) | The same, as JSON |
| [`data/companies.csv`](data/companies.csv) | All 7,791 companies with open roles |

The data files carry the most recent slice rather than all 201,883
roles. The full set is ~38MB, which GitHub will not render and which would add a
new multi-megabyte blob to this repository every day. The complete, live corpus
is at [app.trylynceus.com](https://app.trylynceus.com).

## Biggest hirers right now

Ranked purely by open-role count, so volume employers lead it. The
[boards above](#browse) are the better entry point if you want a particular
kind of work.

| Company | Open roles |
| --- | --- |
| [BAYADA Home Health Care](https://job-boards.greenhouse.io/bayada) | 2,591 |
| [Anduril Industries](https://job-boards.greenhouse.io/andurilindustries) | 2,200 |
| [SpaceX](https://job-boards.greenhouse.io/spacex) | 2,152 |
| [Carvana](https://job-boards.greenhouse.io/carvana) | 1,757 |
| [Bjakcareer](https://jobs.ashbyhq.com/bjakcareer) | 1,361 |
| [Speechify](https://job-boards.greenhouse.io/speechify) | 1,281 |
| [Upstream Rehabilitation](https://job-boards.greenhouse.io/urpt) | 1,231 |
| [Veterinary Emergency Group (VEG)](https://job-boards.greenhouse.io/veterinaryemergencygroupst) | 1,107 |
| [EquipmentShare](https://job-boards.greenhouse.io/equipmentsharecom) | 1,003 |
| [Doctolib](https://careers.doctolib.fr/jobs) | 973 |
| [Openai](https://jobs.ashbyhq.com/openai) | 954 |
| [Clera](https://jobs.ashbyhq.com/Clera) | 856 |
| [Meridial](https://job-boards.greenhouse.io/agency) | 821 |
| [Databricks](https://job-boards.greenhouse.io/databricks) | 808 |
| [ALO](https://job-boards.greenhouse.io/aloyoga) | 767 |

## How this is built

Every role here was read from the company's own careers page or public job
feed, and each row links to the original posting — apply there, not here. The
`Last updated` stamp at the top is when this data was actually generated.

Listings are dropped when they disappear from the source, so nothing in this
repository is a role that has already been filled. Recruiters, staffing
agencies and job-board aggregators are excluded: every entry is an employer
hiring for itself.

Job descriptions are deliberately not included. They are the employer's own
words and belong to them; the link goes to the source instead.

## Using it

The compiled dataset (this repository's selection and arrangement) is offered
under [CC BY 4.0](LICENSE) — use it, build on it, please credit Lynceus.
Individual listings are facts about public job ads and remain the property of
the companies posting them.

Corrections and removals: open an issue, or email us. If you are an employer
and would rather not appear here, say so and you will be removed the same day.
