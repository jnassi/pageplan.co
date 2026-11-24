# pageplan.co

The website for [Page Plan](https://pageplan.co), the reading planner for iPhone and iPad.
Plain HTML and one stylesheet, served by GitHub Pages; push to `main` and it's live in a minute.

- `/` home (from `page-plan/Marketing/landing-page.md`), `/help/`, `/privacy/`, `/app` (short link to the
  App Store), `404.html`.
- Analytics: GoatCounter (`pageplan.goatcounter.com`), no cookies. Clicks on links with
  `data-goatcounter-click` are counted as events.
- App Store links carry `ct=` campaign tags (`site`, `link`) for App Store Connect's analytics.
- DNS (Hover): apex A records to GitHub Pages, `www` CNAME to `jnassi.github.io`. Email (Titan MX) and
  the Bluesky `_atproto` TXT record live there too; don't remove them.
