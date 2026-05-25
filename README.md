# mwah-reports

Weekly recap dashboards for MWAH — **"What shipped on MWAH"**.

Each Monday morning, a scheduled Claude Code routine generates an HTML dashboard summarizing the prior week's user-facing changes across `mwah-crm` and `gimmemwah-website`, replaces the previous report in this repo, and posts a link to **#all-mwah** in Slack.

Only the latest week's report lives here at any time — the prior one is deleted on each run. Old links rot intentionally; this is a recap surface, not an archive.

## Where to find the current week's report

Look in this repo's root: `week-of-YYYY-MM-DD.html`.

Rendered preview (via raw.githack):
`https://raw.githack.com/The-Faucet-Boyz/mwah-reports/main/week-of-YYYY-MM-DD.html`

## Automation

Source routine: claude.ai trigger `trig_01KdoFWBCzvMpRjW6TQGfxBE` ("What shipped on MWAH (weekly)"), firing Monday 06:59 UTC.

Do not commit by hand. Manual edits to a published report are fine in an emergency but will be overwritten next Monday.
