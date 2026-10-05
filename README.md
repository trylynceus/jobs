# Lynceus — live job listings, straight from company careers pages

**237,709 open roles** at **6,072 companies**,
**40,473** of them remote. Read from each employer's own careers
page and job feed — never reposted from another board.

_Last updated: 2026-10-05 04:16 UTC_

Search it conversationally at **[trylynceus.com](https://trylynceus.com)** — describe
what you want in plain English and get the companies actually hiring for it.
In private beta; early access from the same page.

## Browse

- [Remote](boards/remote.md) — 40,473 roles
- [Berlin](boards/berlin.md) — 2,439 roles
- [London](boards/london.md) — 7,212 roles
- [Paris](boards/paris.md) — 2,413 roles
- [Amsterdam](boards/amsterdam.md) — 1,384 roles
- [Munich](boards/munich.md) — 1,321 roles
- [Madrid](boards/madrid.md) — 787 roles
- [Barcelona](boards/barcelona.md) — 853 roles
- [Dublin](boards/dublin.md) — 918 roles
- [Lisbon](boards/lisbon.md) — 487 roles
- [Zurich](boards/zurich.md) — 219 roles
- [Stockholm](boards/stockholm.md) — 387 roles
- [New York](boards/new-york.md) — 12,070 roles
- [San Francisco](boards/san-francisco.md) — 11,863 roles
- [Engineering](boards/engineering.md) — 55,377 roles
- [Data & AI](boards/data-ai.md) — 32,570 roles
- [Design](boards/design.md) — 11,562 roles
- [Product](boards/product.md) — 12,505 roles
- [Sales](boards/sales.md) — 20,090 roles
- [Marketing](boards/marketing.md) — 9,683 roles

## Data

| File | What it is |
| --- | --- |
| [`data/jobs.csv`](data/jobs.csv) | The 5,000 most recently posted roles |
| [`data/jobs.json`](data/jobs.json) | The same, as JSON |
| [`data/companies.csv`](data/companies.csv) | All 6,072 companies with open roles |

The data files carry the most recent slice rather than all 237,709
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
| Bjakcareer | 3,048 |
| SpaceX | 2,646 |
| BAYADA Home Health Care | 2,491 |
| Anduril Industries | 2,431 |
| Carvana | 1,830 |
| Openai | 1,359 |
| Veterinary Emergency Group (VEG) | 1,157 |
| Upstream Rehabilitation | 1,153 |
| EquipmentShare | 1,025 |
| Pavago | 923 |
| Databricks | 885 |
| ALO | 830 |
| Weekday AI | 755 |
| Stripe | 716 |
| Capco | 711 |

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
