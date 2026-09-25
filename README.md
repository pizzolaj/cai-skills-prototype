# CAI Skills prototype

Replica of the shipped CAI 2.0 Skills experience, set up for Maze live website testing.

- `index.html`: the prototype. No query string opens the demo version with the task bar. `?task=<id>` opens a clean test version.
- `tasks.html`: researcher setup page with the study blocks, start URLs, expected Maze paths, and the moderated session guide.
- The Maze snippet is the first element in the `<head>` of `index.html`.

Version A tasks: `install`, `locked`, `invoke`. Version B tasks: `create`, `fix`, `recommend`.

Every screen change adds `&screen=<id>` to the URL with `history.pushState`, so Maze records it as a step. All data is sample data.
