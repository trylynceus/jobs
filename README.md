# Lynceus — live job listings, straight from company careers pages

**242,595 open roles** at **8,411 companies**,
**40,198** of them remote. Read from each employer's own careers
page and job feed — never reposted from another board.

_Last updated: 2026-08-18 22:42 UTC_

Search it conversationally at **[trylynceus.com](https://trylynceus.com)** — describe
what you want in plain English and get the companies actually hiring for it.
In private beta; early access from the same page.

## Browse

- [Remote](boards/remote.md) — 40,198 roles
- [Berlin](boards/berlin.md) — 2,801 roles
- [London](boards/london.md) — 7,180 roles
- [Paris](boards/paris.md) — 2,219 roles
- [Amsterdam](boards/amsterdam.md) — 1,527 roles
- [Munich](boards/munich.md) — 1,536 roles
- [Madrid](boards/madrid.md) — 839 roles
- [Barcelona](boards/barcelona.md) — 884 roles
- [Dublin](boards/dublin.md) — 971 roles
- [Lisbon](boards/lisbon.md) — 505 roles
- [Zurich](boards/zurich.md) — 277 roles
- [Stockholm](boards/stockholm.md) — 441 roles
- [New York](boards/new-york.md) — 12,101 roles
- [San Francisco](boards/san-francisco.md) — 11,140 roles
- [Engineering](boards/engineering.md) — 55,556 roles
- [Data & AI](boards/data-ai.md) — 32,047 roles
- [Design](boards/design.md) — 12,129 roles
- [Product](boards/product.md) — 11,931 roles
- [Sales](boards/sales.md) — 21,105 roles
- [Marketing](boards/marketing.md) — 10,631 roles

## Data

| File | What it is |
| --- | --- |
| [`data/jobs.csv`](data/jobs.csv) | The 5,000 most recently posted roles |
| [`data/jobs.json`](data/jobs.json) | The same, as JSON |
| [`data/companies.csv`](data/companies.csv) | All 8,411 companies with open roles |

The data files carry the most recent slice rather than all 242,595
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
| BAYADA Home Health Care | 2,591 |
| Anduril Industries | 2,200 |
| SpaceX | 2,152 |
| Carvana | 1,757 |
| Bjakcareer | 1,392 |
| Speechify | 1,281 |
| Upstream Rehabilitation | 1,231 |
| Veterinary Emergency Group (VEG) | 1,107 |
| EquipmentShare | 1,003 |
| Fuku | 939 |
| Databricks | 808 |
| ALO | 780 |
| Rentokil Initial | 756 |
| Openai | 735 |
| Capco | 734 |

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
