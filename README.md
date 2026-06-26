# AI Systems Engineering - Lesson Interactives (Sprints 1 to 6)

87 self-contained, interactive HTML visuals, one per lesson concept, built to the TripleTen V0 Interactive Visuals Guide:
Suisse Intl fonts, the platform palette (#1A1A1A / #F2F1EE / #1878DC etc.), the 4px grid and height-based radii,
the wiggling interactive-hint header, the standard shadow, and responsive down to ~325px.

## How to use
- Open any .html in a browser. Each file is standalone and works on its own (fonts load from the Suisse CDN).
- Naming: <chapter>.<lesson>-<concept>.html  (e.g. 1.1.03-sync-vs-async.html), so they sort by sprint.
- See MANIFEST.tsv for the chapter, interaction type, and size of each.

## To publish to the platform (per the design guide)
1. Paste the file into V0 (or host it) and publish (one project = one interactive).
2. Swap the placeholder emoji / inline-SVG icons for Untitled UI icons from the Foundation library.
3. Add the PostHog analytics snippet at publish time.
4. Embed as an iframe in the lesson, and ask the devs to allow-list the published link.

## Coverage
- 87 of 92 lessons have an interactive.
- 5 lessons are pure project briefs and intentionally have none:
  1.3.06, 3.3.05, 4.3.06, 5.3.05, 6.3.05 (the sprint-project pages).

## Note on dynamic vs static
Almost every lesson received a dynamic interactive. A few are flowchart-style concepts
(e.g. component map, repo map, platform roadmap) that could instead be simpler STATIC on-brand
designs if you prefer - those can be converted on request.
