# Rally Gear

Tired of needing to look away from the road to know what gear you're in?

This is a simplistic easy-to-read gear indicator for BeamNG, inspired by 7-segment gear indicators in older rallycars.

Currently supports manual transmission only.

![Rally Gear Screenshot](main.png)

Font, font-size, color and text-shadow are customizable within the below section of `app.js`:

```Javascript
    style.innerHTML = `
      @font-face {
        font-family: 'Seven';
        src: url('/ui/modules/apps/RallyGear/Seven Segment.ttf') format('truetype');
      }

      .gear-display {
        font-family: 'Seven';
        font-size: 6em;
        color: red;
        text-shadow: 5px 5px 0 black;
        /*font-weight: bold;*/
      }
    `;
```

A couple of .tff fonts are included, although any .tff should work.

A lot of the code is based off of the by default included SimpleGears app by Metalmuncher.
