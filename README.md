# Orthogonal Divinatory Matrix

An animated seven-scene artist's website documenting the development of a tarot-based poetic system. Uses the artist's original tarot illustrations.

## Preview locally

Open `index.html` in a browser, or for a local web server run `python -m http.server 8000` in this directory and visit http://localhost:8000.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload **the contents of this folder** (`index.html`, `styles.css`, `script.js`, `assets/`) to the repository root.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then save.
4. GitHub will display the published website URL when deployment completes.

## Editing

- Change colours in `styles.css`: `--lime`, `--pink`, `--black`.
- Change scene text and card/poem content in `script.js`.
- Card images are stored in `assets/` and referenced in `script.js`.
- The 24 readings here are permutations of the four suit groups (4!); they are **not** asserted to be 24 distinct Sudoku-valid grids. Scene 2 shows one valid 4×4 orthogonal-style matrix.
- The Major Arcana selection is a documented reconstruction, not a randomised live draw.

The site uses no third-party libraries and does not require a build step.
