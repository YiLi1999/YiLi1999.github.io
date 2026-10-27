# Yi Li · Personal website

Live: https://YiLi1999.github.io

A small, build-free academic homepage with a separate Vibe Coding portfolio. Plain HTML and CSS; no framework, CDN, tracking, or runtime dependency.

## Pages

- `index.html`: short biography, research, selected papers, and featured projects.
- `publications.html`: journal articles with verified DOI links.
- `projects.html`: Vibe Coding projects and source links.
- `cv.html`: education, visits, selected awards, funding, and service.
- `research.html`, `talks.html`, `contact.html`: supporting pages with stable URLs.
- `style.css`: shared layout and responsive styles.
- `assets/`: curated public images.

## Preview

Run `python -m http.server 8088 --bind 127.0.0.1` from this folder, then visit http://127.0.0.1:8088.

## Updating projects

Add a project article in `projects.html` with a concise description, a real source/demo link, and a public image. The home page intentionally features only two projects; update those separately when needed. Never use local paths, internal services, API keys, or unpublished material as public project links.

## Content sources

Profile and CV facts were refreshed in October 2026 from the owner's August 2026 academic CV and supporting materials. Paper metadata and DOI links were checked against publisher pages. The 2026 erratum is linked alongside its original article. The website uses “Quantum information researcher” because a current job title was not specified in the materials.

The pixel bunny is from [Overleaf Bunny Helper](https://github.com/YiLi1999/overleaf-bunny-helper), MIT licensed; see `assets/bunny-LICENSE.txt`. Project preview panels are illustrative.

## Publish

Push the public website files to the `main` branch of `YiLi1999/YiLi1999.github.io`. GitHub Pages serves this directory. Supporting certificates and CV source documents remain local and are ignored by Git.
