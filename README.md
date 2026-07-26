# Startup School Clusters

A single-file, single-screen mobile site for unofficial attendee meetups at YC Startup School 2026 (Day 2, Chase Center SF). During today's breaks, attendees self-sort into 10 interest clusters, each mapped to a circle on a map of Thrive City Plaza. Tap a cluster for its subthemes and location, then use beacon mode — a fullscreen color card with the cluster name — to hold your phone up as the zone's sign. Everything is inline (CSS, JS, SVG map, favicon): zero external requests, so it loads in one round trip on stadium wifi and keeps working offline. Not official — just founders organizing founders.

## Deploy

Already deployed via GitHub Pages from `main` / root. To redeploy after edits:

```sh
git add -A && git commit -m "update" && git push
```

Pages serves `index.html` from the repo root — no build step. To host anywhere else, copy `index.html`; it also works opened directly as a local `file://`.
