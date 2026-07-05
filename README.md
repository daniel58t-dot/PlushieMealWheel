# PlushieMealWheel

A static lunch picker for GitHub Pages. The public page is `index.html` at the repository root.

## Preview

Open `index.html` directly in a browser.

Timing can be configured with URL parameters:

```text
index.html?imagePeriod=0.5&textPeriod=0.2&totalDuration=5
```

Values below `20` are treated as seconds. Larger values are treated as milliseconds, so `imagePeriod=500` also means 0.5 seconds.

## Image Sets

The plushie artwork can be switched with the `set` URL parameter:

```text
index.html?set=plq
index.html?set=garden
index.html?set=caffeine
```

`set=plq` uses `images/PLQ/*.png` with the restaurant list and is the default. `set=garden` uses `images/garden/*.jpg` with the restaurant list. `set=caffeine` uses `images/PLQ/*.png` with a caffeine list: chagee, chi cha, koi, itea, luckin, alchemist, tomoro, huggs, yakun, toastbox, heytea, kopitiam, and oldteahut. Every caffeine item has 3x draw weight except alchemist and huggs.

Timing parameters can be combined with any set:

```text
index.html?set=garden&imagePeriod=0.5&textPeriod=0.2&totalDuration=5
```

## GitHub Pages

After uploading the project to GitHub, enable Pages from the repository root on the branch you publish.
