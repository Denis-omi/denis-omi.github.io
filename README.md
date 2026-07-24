# denis-omi.github.io

Personal GitHub Pages site for design sketches — static HTML/CSS page concepts with
AI-generated imagery.

## What's here

```
index.html                          landing page — links to every sketch collection
athlete-profile/                    collection: creator/athlete profile pages
  mma-damon-rivera.html
  kids-baseball-jake-morales.html
  college-baseball-ethan-whitfield.html
  pickleball-sandy-reyes.html
  snowboard-kai-sorensen.html
  assets/<page-slug>/*.png            generated images, one folder per page
  support.js                          shared script required by every page in this
                                       collection
```

## Profiles in `athlete-profile/`

| Page | Subject | Sport | Style | Notes |
|---|---|---|---|---|
| `mma-damon-rivera.html` | Damon "Blackout" Rivera, adult | MMA | Photoreal | UWF Lightweight Champion |
| `kids-baseball-jake-morales.html` | Jake "Slugger" Morales, age 11 | Youth baseball | **Illustrated** | Fictional child — cartoon art only, by design |
| `college-baseball-ethan-whitfield.html` | Ethan "Slugger" Whitfield, age 20 | College baseball | Photoreal | NCAA Division I, Riverside University Rockets |
| `pickleball-sandy-reyes.html` | Sandy "The Dink" Reyes, age 46 | Pickleball | Photoreal | Austin rec circuit |
| `snowboard-kai-sorensen.html` | Kai "Avalanche" Sorensen, age 24 | Snowboard | Photoreal | X-Games Big Air gold |

Jake Morales is the one deliberate exception to photoreal: he's a fictional minor, so
his page uses cartoon/illustrated imagery instead of AI-generated photoreal likeness —
not a stylistic choice, a hard rule. Ethan Whitfield exists specifically as an adult
college-baseball counterpart page after that same subject was originally sketched as a
kid.

## More collections are coming

Future work (teams, leagues, colleges, sports, etc.) will land as sibling top-level
folders next to `athlete-profile/` — each with its own `assets/` and pages — and get a
new section on `index.html`.

## How pages here get made

Pages and images are produced in a separate local workspace (not part of this repo)
using Claude Code plus an AI image-generation tool; finished HTML and images are copied
in here once reviewed. See that workspace's own README for the process, safety
checklist, and tooling — none of it (including any API credentials) lives in this
repo.

## Status

Local working copy. `git log` has a couple of prior commits; the index.html move to
repo root and the Ethan Whitfield swap are uncommitted as of this writing. Nothing has
been pushed to `origin` beyond the initial scaffold.
