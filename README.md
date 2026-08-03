# oreuma.app

The public landing page and privacy policy for **Oreuma**, a local-first
bodyweight workout app.

Served by GitHub Pages at <https://oreuma.app>.

## This repo is a publishing target, not the source

Everything here is generated in the app's own (private) repository, under
`website/`, and pushed here to be served. **Edit it there, not here** — a
change made directly in this repo will be overwritten by the next publish.

`privacy.html` in particular is generated from the app's actual privacy
copy (`mobile/src/lib/legalContent.ts`), so that the policy on the website
and the policy inside the app cannot drift apart.

## Contents

| file | what it is |
| --- | --- |
| `index.html` | the landing page |
| `privacy.html` | the privacy policy |
| `screens/` | app screenshots used by the landing page |
| `CNAME` | the custom domain, read by GitHub Pages |
| `.nojekyll` | serve files as-is, skip Jekyll processing |
