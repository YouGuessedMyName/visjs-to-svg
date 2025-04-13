# Visjs-to-svg
An example that shows how you can render vis.js networks to svg. It is based on (https://github.com/justinharrell/vis-svg) and (https://github.com/noamteyssier/pvsvg).
The way vis.js renders nodes somehow did not work properly when trying to export to svg. 
The solution a found was adding two lines to the draw function for every shape.
You can find these by going into `vis-network-9.1.9.js` and searching for `SVG-PATCH`.
