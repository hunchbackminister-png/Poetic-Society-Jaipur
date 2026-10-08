# Recovery notes

Recovered from HAR captures of the public Poetic Society Jaipur Emergent deployment.

The executable frontend is `static/js/bundle.js`. The recovered source-module boundaries are in `src-recovered/`. All seven image assets captured by the two HAR files are under `images/`.

For GitHub Pages, the image URL literals in the executable bundle were changed only from root-absolute `/images/...` to relative `./images/...`, because a GitHub project site is normally served under `/REPOSITORY/`. This does not change the image itself or its visual presentation.
