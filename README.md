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

### Wrong via file protocol
![wrong](http://content.screencast.com/users/softer/folders/Jing/media/011b685f-841b-4d12-95c0-8f2d34c3b440/2013-10-22_1740.png)

### Correct via http protocol
![correct]http://content.screencast.com/users/softer/folders/Jing/media/864ec637-f16e-45e5-9970-d8565347f713/2013-10-22_1742.png)
