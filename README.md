# will.i.am — Famous People with Disabilities

A static, single-page site profiling will.i.am: musician, producer, tech entrepreneur, living with ADHD.
Adapted from a class presentation deck. By Walter Lee.

**Live:** https://walterdlee.github.io/william-site/

## Structure

Everything is one self-contained file — `index.html`. No build step, no dependencies, no framework.
Styles and the tab script are inline. Deploying means serving that file.

Content is organized into eight tabs:

| # | Tab | Source slide |
|---|-----|--------------|
| 01 | Reason for Fame | Key Element 1 |
| 02 | Background | Important Events |
| 03 | ADHD | Key Element 2 — Disability Experience |
| 04 | Identity | Disability & Identity |
| 05 | Character | Key Element 5 |
| 06 | Relationships | Key Element 4 |
| 07 | Reflection | Reflection & Connection |
| 08 | Sources | Citations + References |

Each tab is deep-linkable by hash (e.g. `#adhd`), and the tabs respond to Back/Forward.

## Local development

Open `index.html` directly, or run a live-reload server to see edits as you save:

```sh
npx live-server --port=5173
```

## Notes

- The masthead embeds the official williamVEVO upload of "#thatPOWER". It **autoplays muted**
  because browsers block autoplay with sound; this is not configurable.
- The Reflection tab is intentionally unwritten — the three prompts are rendered with
  "TO WRITE" markers to be filled in.
