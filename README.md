# alienmind-www-vercel-legacy

The old Vercel address of the AlienMind site, `https://www-alienmind.vercel.app`, now only
sends visitors to `https://www.alienmind.eu`, keeping the path (for example
`/strdltn/index.html`).

- `index.html` redirects with JavaScript (`location.replace`), with a meta refresh to the home
  page when JavaScript is off.
- `vercel.json` serves `index.html` for every path, so old deep links redirect too.

Deployed by the Vercel project `www-alienmind` from `main`. The site itself lives in
[alienmind-www-public](https://github.com/alienmind/alienmind-www-public) and runs on
Scaleway. Delete this repo and the Vercel project once old links no longer matter.
