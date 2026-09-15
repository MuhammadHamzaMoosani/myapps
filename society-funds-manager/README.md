# Society Funds Manager

An Android app for a housing society treasurer to run monthly maintenance
collections, track expenses, and manage member debts — without an account,
a server, or a spreadsheet.

## Features

- **Monthly collection round** — a checklist per house, one tap to mark
  collected, long-press for a partial or custom amount, and backdating a
  collection into any past month if it arrives late.
- **Member debts** — a fronted expense the society owes a house is tracked
  as a debt and repaid automatically through reduced monthly maintenance,
  never mixed up with the house owing the society.
- **Ledger** — every income and expense entry, searchable, browsable by
  month or by a custom date range, exportable to Excel/CSV.
- **Recurring expenses** — salaries, utilities and the like, with a due day
  and a "mark given" flow, plus a daily reminder while one's overdue.
- **Bill scanning** — reads a photocopied bill via Gemini and pre-fills the
  amount, vendor and category (an API key you provide; nothing is sent
  without one).
- **Spending report** — an on-demand Gemini summary of the month's
  category totals (never vendor-level detail).
- **WhatsApp / email reminders** for unpaid houses, formatted for sharing.
- **In-app update check** against this repo's releases (see the [hub
  README](../README.md) for how that works).

## Privacy

Everything lives on the phone — no accounts, no analytics, nothing synced.
The only outbound calls are: Gemini (only if you add a key, and only the
image/aggregated totals you send), and a version check against this repo's
public releases.

## Installing

This isn't on the Play Store — download the latest `.apk` from the
[Releases page](../../releases) (tag prefix `funds-v`), then install it
directly on an Android phone. You'll need to allow "install from this
source" the first time; Android always asks before installing, update or
not.

## License

[MIT](../LICENSE).
