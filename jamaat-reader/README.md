# Jamaat Reader

An Android app for jamaat (congregational prayer) times around Bahadurabad,
Tariq Road and adjoining areas in Karachi — read straight off BJNT's own
printed board, never calculated from a formula.

## Features

- **Countdown dial** — time to your preferred masjid's next jamaat, holding
  on a passed one until you mark it (prayed, alone, or missed) instead of
  silently moving on as if you'd prayed.
- **Nearby** — every masjid in an area, sorted by how reachable its jamaat
  still is (leave now, in its grace window, comfortable, already finished),
  by walking distance from your actual location when it's on.
- **Saved masjids** — a six-column week grid per masjid, including Jumma,
  flagging any time that isn't on today's board rather than showing it as
  current.
- **Streak** — a day-by-day record of which prayers you made.
- **Reminders** — a local notification before your primary masjid's jamaat,
  scoped to today's board only.
- **Dua search by meaning** — search "house dua" or "ghar ki dua" instead of
  needing the exact title.
- **The board photo**, one tap away from Home, so any time can be checked
  against its source.
- **In-app update check** against this repo's releases (see the [hub
  README](../README.md) for how that works).

## Never calculated, never guessed

Every jamaat time is read off BJNT's printed board — with one narrow,
documented exception: the Fajr/Zuhr/Asr/Maghrib/Isha header times, which are
genuinely computable from the sun and always have been. A time not verified
against today's board renders struck through and dated, never plain and
never silently carried over from yesterday. A masjid with no real
coordinate gets no walk time — nothing is estimated from a nearby pin.

## Privacy

No accounts, no analytics on prayer behaviour, nothing leaves the device —
except fetching today's board (a public JSON file BJNT's board is
transcribed into) and a manual version check against this repo's public
releases when you tap for one. Nothing about where you are, what you
prayed, or what you saved is ever sent anywhere.

## Installing

This isn't on the Play Store — download the latest `.apk` from the
[Releases page](../../releases) (tag prefix `masjid-v`), then install it
directly on an Android phone. You'll need to allow "install from this
source" the first time; Android always asks before installing, update or
not.

## Credit

Every time on the board comes from BJNT — this app just reads it and gets
it to your phone.

## License

[MIT](../LICENSE).
