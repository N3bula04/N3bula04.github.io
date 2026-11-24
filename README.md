# Jeremy's personal site

A static site: plain HTML and CSS, with no build step, no JavaScript and no tracking. It's served by GitHub Pages from `N3bula04.github.io`.

The homepage features Domain Brand Alert (with a fictional Northwind Bakery demo screenshot) and the OSINT Pivot Tool. A recruiter-readable copy of the tool's offline fictional demo report is at `samples/pivot-tool-report.html`.

Preview locally from the repo root (this folder), not from a parent directory:

```bash
python3 -m http.server 8767 --bind 127.0.0.1
# then open http://127.0.0.1:8767/
```
