# PlushieMealWheel

A static lunch picker for GitHub Pages. The public page is `index.html` at the repository root.

## Preview

Open `index.html` directly in a browser.

Timing can be configured with URL parameters:

```text
index.html?imagePeriod=0.5&textPeriod=0.2&totalDuration=5
```

Values below `20` are treated as seconds. Larger values are treated as milliseconds, so `imagePeriod=500` also means 0.5 seconds.

## GitHub Pages

After uploading the project to GitHub, enable Pages from the repository root on the branch you publish.
