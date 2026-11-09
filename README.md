# Explore the System Log: interactive walkthrough

A short, top-level walkthrough of the System Log page (Logs) in MomentusMAX. A screen sits on the left and short, large-print notes sit on the right, in the same layout as the Today's Focus, Opportunity page, Calendar, Tasks, and Performance walkthroughs.

## What learners do

- Start on an overview and select a numbered area on the screen, or use Next and Back.
- On Filters, select Date range, Severity, Type, Direction, or Category to see where each one is.
- On Search and sort, and on Log entries, select a label to zoom to that part of the screen.

Steps: Overview, Filters, Active filters, Search and sort, Log entries.

In every step, selecting a label outlines only that part of the screen.

## Repo contents

| Path | Purpose |
| --- | --- |
| `index.html` | The walkthrough. Screens, scripts, and styles are inlined. The only external request is Google Fonts, which falls back to system fonts |
| `.nojekyll` | Tells GitHub Pages to serve the file as is |
| `.gitignore` | Standard ignores |

## Run locally

Open `index.html` in a browser.

## Publish with GitHub Pages

1. Push to `main`.
2. In the repo, go to Settings > Pages, choose Deploy from a branch, then `main` and `/ (root)`.
3. The page is served at `https://<user>.github.io/<repo>/`. Suggested repo name: `MAX-logs-nav`.

## Embed in Genially or 360Learning

The page is responsive. Give it as much room as you can, ideally a full slide.

```html
<iframe src="https://<user>.github.io/<repo>/" title="Explore the System Log Walkthrough" width="100%" height="100%" style="border:0;width:100%;height:100%;" allowfullscreen loading="lazy"></iframe>
```

Test in Genially's Preview or published view. Embeds can look blank in the editor.

## How it was built

The two screens are renders of two saved snapshots of the System Log page: the list with filters applied, and the filter panel open. The left navigation bar is not included. The top bar is kept. Nothing was redrawn.

To change notes, edit the `STEPS` array in `index.html`. To change a screen, use a new approved capture. Do not edit the embedded images.

## Sources for the notes

| Step | Source |
| --- | --- |
| Filters | Labels in the filter panel: Date Range, Severity, Type, Communication Direction, Category |
| Active filters | Labels on the captured screen, including the remove button on each chip and Clear all |
| Search and sort | Labels on the captured screen. "Switch between problems only and all activity" is the control's own label |
| Log entries | Labels on the captured screen. What the severity icon means is inferred and needs Product to confirm |

## Before you publish

- Product to confirm the inferred explanations: what the severity icon means, and that the sort menu offers an oldest-first option (only Newest first is shown).
- The demo data shows 25 identical entries, "CRM Background Sync Failed", with account numbers. They are shown as captured. Recapture with a mix of entries for a stronger walkthrough.
- Product or Security must confirm the demo data is mock.
- This file contains captures of the MomentusMAX interface and is Momentus internal training content. Keep the repo private unless Momentus approves public sharing. No license is granted. All rights reserved by Momentus Technologies.
