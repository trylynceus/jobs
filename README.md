# Lynceus — live job listings, straight from company careers pages

**258,358 open roles** at **7,892 companies**,
**45,192** of them remote. Read from each employer's own careers
page and job feed — never reposted from another board.

_Last updated: 2026-09-07 04:15 UTC_

Search it conversationally at **[trylynceus.com](https://trylynceus.com)** — describe
what you want in plain English and get the companies actually hiring for it.
In private beta; early access from the same page.

## Browse

- [Remote](boards/remote.md) — 45,192 roles
- [Berlin](boards/berlin.md) — 3,174 roles
- [London](boards/london.md) — 7,904 roles
- [Paris](boards/paris.md) — 2,229 roles
- [Amsterdam](boards/amsterdam.md) — 1,612 roles
- [Munich](boards/munich.md) — 1,624 roles
- [Madrid](boards/madrid.md) — 889 roles
- [Barcelona](boards/barcelona.md) — 981 roles
- [Dublin](boards/dublin.md) — 1,005 roles
- [Lisbon](boards/lisbon.md) — 491 roles
- [Zurich](boards/zurich.md) — 287 roles
- [Stockholm](boards/stockholm.md) — 485 roles
- [New York](boards/new-york.md) — 12,724 roles
- [San Francisco](boards/san-francisco.md) — 12,559 roles
- [Engineering](boards/engineering.md) — 60,058 roles
- [Data & AI](boards/data-ai.md) — 34,874 roles
- [Design](boards/design.md) — 12,602 roles
- [Product](boards/product.md) — 13,618 roles
- [Sales](boards/sales.md) — 22,124 roles
- [Marketing](boards/marketing.md) — 10,752 roles

## Data

| File | What it is |
| --- | --- |
| [`data/jobs.csv`](data/jobs.csv) | The 5,000 most recently posted roles |
| [`data/jobs.json`](data/jobs.json) | The same, as JSON |
| [`data/companies.csv`](data/companies.csv) | All 7,892 companies with open roles |

The data files carry the most recent slice rather than all 258,358
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
| Bjakcareer | 3,084 |
| BAYADA Home Health Care | 2,580 |
| SpaceX | 2,337 |
| Anduril Industries | 2,211 |
| Carvana | 1,752 |
| Openai | 1,457 |
| Upstream Rehabilitation | 1,201 |
| Veterinary Emergency Group (VEG) | 1,143 |
| ALO | 1,102 |
| Speechify | 1,099 |
| EquipmentShare | 997 |
| Databricks | 868 |
| Pavago | 816 |
| Fuku | 759 |
| Rentokil Initial | 750 |

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
