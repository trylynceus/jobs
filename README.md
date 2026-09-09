# Lynceus — live job listings, straight from company careers pages

**257,834 open roles** at **7,900 companies**,
**45,062** of them remote. Read from each employer's own careers
page and job feed — never reposted from another board.

_Last updated: 2026-09-09 04:17 UTC_

Search it conversationally at **[trylynceus.com](https://trylynceus.com)** — describe
what you want in plain English and get the companies actually hiring for it.
In private beta; early access from the same page.

## Browse

- [Remote](boards/remote.md) — 45,062 roles
- [Berlin](boards/berlin.md) — 3,142 roles
- [London](boards/london.md) — 7,795 roles
- [Paris](boards/paris.md) — 2,277 roles
- [Amsterdam](boards/amsterdam.md) — 1,599 roles
- [Munich](boards/munich.md) — 1,601 roles
- [Madrid](boards/madrid.md) — 879 roles
- [Barcelona](boards/barcelona.md) — 956 roles
- [Dublin](boards/dublin.md) — 966 roles
- [Lisbon](boards/lisbon.md) — 487 roles
- [Zurich](boards/zurich.md) — 282 roles
- [Stockholm](boards/stockholm.md) — 480 roles
- [New York](boards/new-york.md) — 12,684 roles
- [San Francisco](boards/san-francisco.md) — 12,536 roles
- [Engineering](boards/engineering.md) — 59,716 roles
- [Data & AI](boards/data-ai.md) — 34,687 roles
- [Design](boards/design.md) — 12,601 roles
- [Product](boards/product.md) — 13,599 roles
- [Sales](boards/sales.md) — 22,143 roles
- [Marketing](boards/marketing.md) — 10,728 roles

## Data

| File | What it is |
| --- | --- |
| [`data/jobs.csv`](data/jobs.csv) | The 5,000 most recently posted roles |
| [`data/jobs.json`](data/jobs.json) | The same, as JSON |
| [`data/companies.csv`](data/companies.csv) | All 7,900 companies with open roles |

The data files carry the most recent slice rather than all 257,834
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
| Bjakcareer | 3,081 |
| BAYADA Home Health Care | 2,563 |
| SpaceX | 2,344 |
| Anduril Industries | 2,220 |
| Carvana | 1,752 |
| Openai | 1,455 |
| Upstream Rehabilitation | 1,197 |
| Veterinary Emergency Group (VEG) | 1,134 |
| ALO | 1,085 |
| EquipmentShare | 997 |
| Databricks | 870 |
| Pavago | 828 |
| Speechify | 824 |
| Fuku | 759 |
| Rentokil Initial | 746 |

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
