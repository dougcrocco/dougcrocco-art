# dougcrocco.com

Static site. Everything it needs is in this repo — `index.html`, `works-data.js`,
`support.js`, `doc-page.js`, `contact.php`, the CV page, `press/`, `images/`,
`artwork/uploads/` (656 files), and the hero video + stills.

`window.IMG_BASE` is `''`, so artwork loads from `artwork/uploads/` locally. No external host.


## Press archive

### PDFs in this repo

| Piece | Path |
| --- | --- |
| Pacific Lines press release, 2005 | `press/pacific-lines-press-release-2005.pdf` |
| Palm Beach Post, Art Connections, 2008 | `press/palm-beach-post-art-connections-2008.pdf` |
| Gavlak / Palm Beach Post | `artwork/uploads/2014/07/Gavlak-Palm-Beach-Post.pdf` |
| Neonatural press release | `artwork/uploads/2014/10/neonatural-pr-pdf.pdf` |
| Big Pictures, Neighborhood News, 2015 | `press/big-pictures-neighborhood-news-2015.pdf` |
| WAHA newsletter, The Unassuming Art Scene in West Adams, 2017 | `press/waha-newsletter-march-2017.pdf` |
| Domino Magazine, 2016 | `press/domino-magazine-2016.pdf` (duplicate at `artwork/uploads/2016/06/Domino-MAg.pdf`) |
| The Come Up — Sade, press kit, 2026 | `press/the-come-up-sade-presskit.pdf` |

`pdf-archive.html` lists all of these; the Info section links to it beside Download CV.

### Press pages in this repo

`press/` holds 15 HTML pages: Big Pictures Neighborhood News, Cee Cee B-LA Connect,
Guccivuitton / ICA Miami, Happy Lion Gallery, Hollywood Dream Bubble (Hypebeast, press
release, review), LA Weekly West Adams Gallery Row, Neonatural press release, NYT
artist-run galleries, Pacific Lines press release, Palm Beach Post Art Connections,
Polaroid Black LA Weekly, Staring at the Sun review, WAHA West Adams art scene.

## Layout

    index.html          works-data.js    support.js    doc-page.js
    doug-crocco-cv.html pdf-archive.html  contact.php
    hero-v5.mp4         hero-poster.jpg  hero-still.jpg
    images/             59 portraits, venue marks, UI art
    press/              15 HTML pages + 8 PDFs
    artwork/            663 images in 27 folders — one per show, plus works/, news/, site/

## Notes

- Editing artwork data: `works-data.js`. Paths are repo-relative under `artwork/uploads/`.
- Keep at most three generations of `works-data-*.js` backups.
- The hero video honors `prefers-reduced-motion`: the poster holds and the video does not autoplay.
