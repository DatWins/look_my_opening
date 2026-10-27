---
title: "How the Trees Are Made"
header_menu_title: "How It Works"
navigation_menu_title: "How It Works"
weight: 9
header_menu: false
---
## From a study to a tree
Every position is a board, every branch is labeled with its move, and a green arrow shows the move just played. Open a tree, then scroll to zoom in and drag to move around.

Each tree starts as a PGN file with one line per chapter, the way Lichess exports a study. A script merges all the lines into one branching tree and draws a board for every position.

## Tools
- [lichess-study-visualiser](https://github.com/zavgorodnii/lichess-study-visualiser) draws the tree
- [Graphviz](https://graphviz.org/) lays out the branches
- [python-chess](https://github.com/niklasf/python-chess) draws the boards
- [Hugo flashcard shortcode](https://www.mrnice.dev/posts/hugo-flashcard-shortcode-for-study/) makes the test-yourself cards
