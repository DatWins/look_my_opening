---
title: "How the Trees Are Made"
header_menu_title: "How It Works"
navigation_menu_title: "How It Works"
weight: 2
header_menu: true
---
## From a study to a tree
Each tree starts as a PGN file with one line per chapter, the way Lichess exports a study. A script merges all the lines into one branching tree and draws a board for every position.

## Tools
- [lichess-study-visualiser](https://github.com/zavgorodnii/lichess-study-visualiser) draws the tree
- [Graphviz](https://graphviz.org/) lays out the branches
- [python-chess](https://github.com/niklasf/python-chess) draws the boards
