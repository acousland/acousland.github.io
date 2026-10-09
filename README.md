# Aaron Cousland’s apps

Public app portfolio at **https://acousland.github.io/**.

A static HTML site hosted by GitHub Pages from the root of the `main` branch. No dependencies or build step.

## Update the page

Edit `index.html` for the collection, or an app’s `index.html` inside its folder, then push to `main`. GitHub Pages publishes the update automatically. The shared stylesheet and screenshot assets live in `assets/`.

The collection contains Mondrian, Screener, co-written, Marginal, Agora, and BoxerScope. Each card links to a dedicated detail page with features, requirements, getting-started instructions, and downloads. Mondrian and BoxerScope link to public release repositories while their source remains private. Screener links to the releases list because its current builds are prereleases.

Mondrian, co-written, Marginal, and Agora use demo screenshots. Screener uses a labelled illustration with its app icon; BoxerScope uses its app artwork.

To preview locally, run `python3 -m http.server 8000` in this directory and open http://localhost:8000.
