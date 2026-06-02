---
title: News for Truly Beyond Compare
url: https://plugins.jetbrains.com/plugin/29279-truly-beyond-compare
date: '2026-05-26'
author: ''
feed_url: https://plugins.jetbrains.com/rss
---
<h2>Truly Beyond Compare 2.2.1</h2>
<ul>
  <li>Improved: "Diff with Branch" search now uses IntelliJ's standard fuzzy matcher (MinusculeMatcher), so abbreviated inputs like <code>ori/allidfcsit</code> or <code>oriallidfsit</code> correctly match <code>origin/allmerge-idfc-sit</code>. Matching also feels consistent with Search Everywhere and Goto File.</li>
  <li>Improved: Filtered branches are now ranked by match quality, so the closest match appears at the top of each group instead of plain alphabetical order.</li>
  <li>New: Pin frequently-used branches to the top of the popup via right-click → "Pin to Top" / "Unpin". Pinned branches appear in a new "Pinned" group at the top of the tree, with a yellow star icon visible anywhere the branch is shown.</li>
  <li>New: "Recent" group now tracks the last 3 branches you actually picked in the popup (most recent first), replacing the prior behaviour of always showing only the current branch.</li>
  <li>New: <code>origin/allmerge</code> is pinned by default on first use of the plugin in a project. Unpin it at any time and the choice persists.</li>
  <li>Fix: Search highlights now render correctly for remote branches when the query targets the full ref (e.g. <code>ori/allidfsi</code> or <code>oriallidfcsit</code> against <code>origin/allmerge-idfc-sit</code>). Previously the row would appear in the filtered list but the matched characters would not be highlighted because the renderer only matched against the short branch name.</li>
</ul>
