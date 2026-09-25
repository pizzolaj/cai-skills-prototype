# CAI Skills prototype

Clickable prototype of CAI 2.0 Skills, set up for Maze live website testing.

- `index.html`: the prototype. With no query string it opens the demo version with the flow bar. With `?task=<id>` it opens a clean test version for Maze.
- `tasks.html`: researcher setup page with the start URL, suggested prompt, and expected Maze path for each task.
- The Maze snippet is the first element in the `<head>` of `index.html`.

Task ids: `library`, `browse`, `create`, `invoke`, `chatcreate`, `recommend`.

Every screen change adds `&screen=<id>` to the URL with `history.pushState`, so Maze records it as a step. All data is sample data.
