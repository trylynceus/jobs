# Lynceus — live job listings, straight from company careers pages

**243,996 open roles** at **6,407 companies**,
**41,634** of them remote. Read from each employer's own careers
page and job feed — never reposted from another board.

_Last updated: 2026-09-22 04:20 UTC_

Search it conversationally at **[trylynceus.com](https://trylynceus.com)** — describe
what you want in plain English and get the companies actually hiring for it.
In private beta; early access from the same page.

## Browse

- [Remote](boards/remote.md) — 41,634 roles
- [Berlin](boards/berlin.md) — 2,701 roles
- [London](boards/london.md) — 7,299 roles
- [Paris](boards/paris.md) — 2,417 roles
- [Amsterdam](boards/amsterdam.md) — 1,499 roles
- [Munich](boards/munich.md) — 1,441 roles
- [Madrid](boards/madrid.md) — 814 roles
- [Barcelona](boards/barcelona.md) — 884 roles
- [Dublin](boards/dublin.md) — 972 roles
- [Lisbon](boards/lisbon.md) — 486 roles
- [Zurich](boards/zurich.md) — 229 roles
- [Stockholm](boards/stockholm.md) — 422 roles
- [New York](boards/new-york.md) — 12,230 roles
- [San Francisco](boards/san-francisco.md) — 12,058 roles
- [Engineering](boards/engineering.md) — 56,713 roles
- [Data & AI](boards/data-ai.md) — 33,069 roles
- [Design](boards/design.md) — 11,847 roles
- [Product](boards/product.md) — 12,794 roles
- [Sales](boards/sales.md) — 20,977 roles
- [Marketing](boards/marketing.md) — 9,944 roles

## Data

| File | What it is |
| --- | --- |
| [`data/jobs.csv`](data/jobs.csv) | The 5,000 most recently posted roles |
| [`data/jobs.json`](data/jobs.json) | The same, as JSON |
| [`data/companies.csv`](data/companies.csv) | All 6,407 companies with open roles |

The data files carry the most recent slice rather than all 243,996
roles. The full set is ~38MB, which GitHub will not render and which would add a
new multi-megabyte blob to this repository every day.

**The complete index is on Hugging Face:**
[Lynceus/jobs](https://huggingface.co/datasets/Lynceus/jobs) — every open role, with a
browsable table and `load_dataset` support. The live search is at
[trylynceus.com](https://trylynceus.com).

## Biggest hirers right now

Ranked purely by open-role count, so volume employers lead it. The
[boards above](#browse) are the better entry point if you want a particular
kind of work.

| Company | Open roles |
| --- | --- |
| Bjakcareer | 3,047 |
| BAYADA Home Health Care | 2,565 |
| SpaceX | 2,524 |
| Anduril Industries | 2,376 |
| Carvana | 1,739 |
| Openai | 1,429 |
| Upstream Rehabilitation | 1,168 |
| Veterinary Emergency Group (VEG) | 1,148 |
| ALO | 1,055 |
| EquipmentShare | 1,006 |
| Databricks | 879 |
| Pavago | 842 |
| Fuku | 761 |
| Weekday AI | 730 |
| Capco | 726 |

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
