less-source-map-chrome-bug
==========================


```bash
1. git clone https://github.com/dotnetwise/less-source-map-chrome-bug.git
2. cd less-source-map-chrome-bug
3. npm install less -g
4. npm install less_watch -g
5. less_watch --show-dependency --source-map --source-map-inline --generate-min-css --source=.
```
less_watch will wait in the console window and watch for your .less changes and generate `.css`, `.css.map`, `.min.css` and `.min.css.map` files.

```bash
1. launch index.html via http protocol, all good
2. launch index.html via file protocol, no source map is loaded
```

