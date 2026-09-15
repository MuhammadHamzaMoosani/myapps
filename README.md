# myapps

Releases hub for personal Android apps — not a place for source code. Each
app keeps its own repo (or stays local); this one exists purely so an
installed app can check for updates and so builds are easy to find and
download.

## How updates work

Each app ships with an in-app "Check for updates" button that queries this
repo's [Releases](../../releases) over the GitHub API. Because releases from
more than one app land here, tags are prefixed per app —
`<app>-v<version>` — and each app's checker only looks at its own prefix.
That also means GitHub's own "latest release" badge on this repo isn't
meaningful; check the per-app folder below or the Releases page's tags
instead.

Installing an update still goes through Android's own install confirmation —
nothing here installs itself silently.

## Apps

| Folder | Tag prefix | What it is |
|---|---|---|
| [`society-funds-manager/`](society-funds-manager/) | `funds-v` | Collections, expenses and member debts for a housing society treasurer. |
| `jamaat-reader/` | `masjid-v` | Coming soon. |

## License

[MIT](LICENSE).
