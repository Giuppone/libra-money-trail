# Notice

`dashboard.html` contains a modified version of NeoDash 2.4.11.

- Original project: https://github.com/neo4j-contrib/neodash
- Copyright 2023 Niels de Jong
- License: Apache License 2.0 (see `LICENSE-NeoDash.txt`)

The original project has no NOTICE file. This file was added for this site.

## Changes made in 2026 by Cristian Giuppone

- `src/export/StaticSnapshotDriver.ts` and `src/export/staticSnapshot.d.ts` are new. They answer queries from data stored in
  the page, so the dashboard works with no database.
- `src/application/ApplicationThunks.ts`, `src/dashboard/Dashboard.tsx`, `src/report/ReportQueryRunner.ts` and
  `src/config/StyleConfig.tsx` load that data and skip the connection steps.
- `src/dashboard/header/DashboardHeader.tsx` and `src/dashboard/header/DashboardTitle.tsx` hide the connection address, the
  account buttons and the settings button, and show a subtitle with links and the name of the case in the page title.
- `src/chart/graph/component/GraphChartTooltip.tsx`, `src/chart/markdown/MarkdownChart.tsx`,
  `src/chart/table/TableChart.tsx` and `src/chart/ChartUtils.ts` change tooltips, color squares in text and table pages.
- `src/dashboard/header/LibraSesion.tsx` and `src/dashboard/header/LibraAvisoDescarga.tsx` are new. They belong to another
  version of the dashboard and do nothing on this site.
- `webpack.config.js` builds a single file with no source maps. `Dockerfile` changes the build settings and lists the
  third-party licenses.

This site is not an official product of the NeoDash authors or of Neo4j, and they do not endorse it. Neo4j is a trademark of
its owner and is named only to describe where the software comes from.
