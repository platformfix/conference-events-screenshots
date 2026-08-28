# conference-events-screenshots

CI-generated screenshots of [`platformfix/conference-events`](https://github.com/platformfix/conference-events) event pages, published here so they can be linked inline in PR comments on that (private) repo.

This repo is public **on purpose**: `raw.githubusercontent.com` doesn't honour a github.com browser session for a private repo, so a plain image link in a PR comment 404s for every viewer. Hosting the images here, in a public repo, is what makes them actually render. There's no privacy cost to that — every image here is a screenshot of a page that's already publicly reachable at `conf.platformfix.com` (marked `noindex`, not access-restricted).

No source code lives here. The CI job that writes to this repo is defined in `platformfix/conference-events`'s `.github/workflows/ci.yml`.

Layout: `pr-<number>/<conferenceSlug>-<eventType>.png`, overwritten on every push to that PR.
