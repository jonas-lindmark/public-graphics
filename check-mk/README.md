### Status icons

From https://iconduck.com/sets/elementary-icon-set

License GPL 3

Convert svg to png
```bash
npm install svgexport -g
ls *.svg | xargs -I{} svgexport {} {}.png 400:400
```
