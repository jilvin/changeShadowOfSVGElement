# changeShadowOfSVGElement

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/cbeffc458f55466582c5193ddd16c63b)](https://app.codacy.com/app/jilvin/changeShadowOfSVGElement?utm_source=github.com&utm_medium=referral&utm_content=jilvin/changeShadowOfSVGElement&utm_campaign=badger)

Change shadow of an SVG element dynamically depending on the set perspective point. 

## Usage
Download changeShadowOfSVGElement.js and link it to your webpage.

#### Syntax
changeShadowOfSVGElement(int x1, int y1, int z1, int z2, string element1Identifier, string element2Identifier);

x1, y1, z1 - coordinates of the light source.

z2 - plane of the screen.

element1Identifier - ID of the first SVG element(object).

element2Identifier - ID of the second SVG element(shadow).

#### See the index.html file included in the source to see the demo usage.
