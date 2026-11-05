# Protonaut demo

This repository shows [Protonaut](https://github.com/Mahan-Imanian/protonaut) on real CI runs. The builds are small test programs from Protonaut's own fixtures, not real games.

- `main` holds a build that works, so its check passes.
- Open the [pull requests](https://github.com/Mahan-Imanian/protonaut-demo/pulls) to see a change that crashes under Proton. The check goes red and Protonaut posts the report as a comment.

The workflow is [.github/workflows/protonaut.yml](.github/workflows/protonaut.yml). Copy it to try this on your own game.
