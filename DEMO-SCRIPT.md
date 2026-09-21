# Pulse demo script — McGrane Precast

## Start and stop

1. Double-click **Start Demo.command**. Chrome opens at **http://pulse.localhost:8080**.
2. Close that Terminal window when you're done. That stops the demo.

The first time, macOS may ask whether Terminal can access your Downloads folder: click **Allow**.
No internet needed; React and the fonts are bundled in `vendor/`.

## The business in one paragraph

McGrane Precast: 62 staff, €14.2M a year, €1.18M a month, 340 active customers, 38 product lines,
74 enquiries a month. One plant at Kingscourt, six lorries, three forklift drivers, and an office
in Navan 55 minutes up the road. Quotations are priced by a five-engineer team in Pune. No CRM,
no stock system. Donna Kavanagh runs sales.

## The five screens, in order

| Pain | Where to show it |
|---|---|
| No CRM at all, nothing tracks an enquiry to a delivery | **Pipeline › Enquiries** — 74 rows, one per enquiry, with the door it came in |
| "We're so focused on today's enquiries we miss last month's" | **Pipeline › Follow-ups** — 43 never answered, worth €610,000, 19 of them over 30 days |
| No idea how much is lost or whether it's on price | **Pipeline › Win/Loss** — 31 quotes, 9 won, 14 lost, 11 of those on price |
| The office doesn't know what's in the yard | **Records › Yard Stock** — 412 units on 38 lines, 6 oversold, €78,400 |
| Dispatch is blind | **Work › Loading** — 26 loads, who loaded each one, 54 minutes on average |

**Records › Production** is the sixth: nine beds at Kingscourt, planned against cast, replacing the
notebook on the plant manager's desk.

## Questions Helios answers

Type these on Home, or click the matching suggestion. The wording can change; Helios listens for the key words.

| Ask | Helios shows | Key words it listens for |
|---|---|---|
| Which enquiries were never followed up? | 43 of 74, €610,000, 19 over thirty days | enquiry, cold, follow-up, untouched, missed |
| Why are we losing quotes? | 31 quotes, 9 won, 14 lost, 11 on price | lost, win, quote, price, discount |
| What is standing in the yard? | 412 units, 38 lines, six oversold | yard, stock, units, count, oversold |
| How long are loads taking? | 26 loads, 54 minutes, forklift idle 41% | load, lorry, dispatch, forklift, minutes |
| Why did the EMS Planner sync fail? | Expired token; two bed schedules queued, nothing lost | sync, EMS, planner, token, failed |
| Draft the follow-ups | A write tool: drafts them and waits for your yes | draft, send, chase, write |

Anything else gets: "Everything I reach goes through a registered tool with a declared permission, and none of them covers that question yet." It then offers buttons for the questions above, so click one and carry on.

## Watch out for

- **Draft the follow-ups:** stop at the **NEEDS YOUR YES** card, which is the point to make. Clicking **Confirm and send** or **Edit draft** makes Helios draft the same nineteen mails again.
- **Stay in dark mode.** Light mode works, but the demo was composed against graphite.
- **The numbers are the rows.** Every badge on a table is the length of the list under it, and every euro figure is the sum of those rows. If someone asks "where does 43 come from", scroll the Follow-ups page and count.
- **Old link:** `localhost:8080/Pulse%20v4%20Glass.dc.html` no longer works. Use http://pulse.localhost:8080.
