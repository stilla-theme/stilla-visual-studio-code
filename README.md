# jakeisnt/stilla

> `Still` :: A quiet, introverted theme that stays out of your way.

## Maintenance

Theme colors are configured in `colors.js`. `theme.js` constains the Visual Studio code configuration using arbitraty colors, and `main.js` is a script that parameterizes the colors in `theme.js` with the colors.

Do not edit anything in `themes/` manually - this is autogenerated by `main.js`. Instead, make the tweaks to either `colors.js` or `theme.js`, then run `node main.js` to generate a new vscode theme configuration.
