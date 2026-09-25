# university-cal

University deadlines and events, served as an Apple Calendar subscription.

## Subscribe (Apple Calendar)
Settings > Calendar > Accounts > Add Account > Other > Add Subscribed Calendar
URL: https://benjamintia.github.io/university-cal/university.ics

## Files
- `university.ics` — the canonical feed. Subscribe to this one.
- `university2.ics` — legacy mirror created in September 2026 to bypass a device cache that refused to refresh. It is kept byte-identical to the canonical feed so a device still pointed at it is never stranded. It will be retired once the phone is confirmed on the canonical URL.

## Updating
Edit `university.ics`, then copy it over `university2.ics`, commit, and push. GitHub Pages rebuilds in about a minute. Keep both files identical until the mirror is retired.
