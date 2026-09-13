# crystalc225.github.io

Personal portfolio site, live at https://crystalc225.github.io once GitHub Pages is enabled.

Single static page, no build step, no framework - just `index.html`.

## Enable GitHub Pages

1. Go to this repo's **Settings -> Pages**.
2. Under "Build and deployment", set **Source** to `Deploy from a branch`.
3. Branch: `main`, folder: `/ (root)`. Save.
4. It'll be live at `https://crystalc225.github.io` in a minute or two.

## Before it's done, fill in

Search `index.html` for these and replace them:

- The Dishcovery **Live demo** link - it's a placeholder `href="#"` until you deploy Dishcovery (see that repo's README for a one-click Render deploy).
- Skills list - add/remove to match what's actually true for you.
- The dishcovery repo link is left out since that repo is private for now - add a "Source" link back in once/if you make it public.

## Adding another project

Copy this block from `index.html` (inside `#projects`, above the "More projects" note) and edit it:

```html
<div class="project">
  <h3>Project Name</h3>
  <p class="desc">One or two sentences on what it does and why you built it.</p>
  <p class="stack">Tech, used, here</p>
  <div class="links">
    <a href="https://your-demo-url" target="_blank" rel="noopener">Live demo</a>
    <a href="https://github.com/crystalc225/your-repo" target="_blank" rel="noopener">Source</a>
  </div>
</div>
```
