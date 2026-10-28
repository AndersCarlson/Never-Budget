# Never Budget

A brutalist envelope budget. Give every dollar an envelope before the month
starts, automate the savings and bills so they leave on payday, and spend
what is left.

Live: https://anderscarlson.github.io/Never-Budget/

## How it works

Income at the top, then three ledgers in the order the money actually moves:

1. **Savings** — leaves on payday, before anything else.
2. **Bills** — fixed and committed. Money coming back in goes in negative.
3. **Spending** — the envelopes. Log what you spend against each one.

The foot of the sheet holds the only number you have to watch: what is left,
with a per-day and per-week pace, the envelopes drawn as an elevation filled
to what has been spent, and the share of income each ledger takes.

**Automation** assumes bills leave on the 1st and savings and spending split
evenly over the 1st and the 15th, and tells you what has to be sitting in the
account on each of those dates.

## Notes

- Single file, no build step, no dependencies beyond Google Fonts.
- A month's figures are stored per month and persist in the browser.
- Tick the square on a line once the money has really moved.
- Drag the handle at the left of a row to reorder it.
- Export CSV downloads the month, or copies it to the clipboard where a
  download is not available.
