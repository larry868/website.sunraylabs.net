# sources of sunraylabs.net website

https://www.sunraylabs.net

Static site build with [zazzy](https://github.com/larry868/zazzy)

Published on github pages, home in `/docs/`

Build with the .vscose task `build`:
    - clear /docs
    - set env var ZS_PUBDIR=docs
    - set env var ZS_HOSTURL=https://sunraylabs.net 
    - zazzy build

use [zazzy](https://github.com/larry868/zazzy) simple static site generator. zazzy need to be instaled first.

In dev mod, run task `watch` and liverserver.

## website structure

- `/.zazzy/` contains html templates
- `/css/` contains `sunraylabs.css` source 
- `/jd/` contains `switch.js` source and any other js sources that will be copies into `/docs/js`
- `/img/` contains images that will be copied into `/docs/img`
- `/lab/` contains all lab pages in markdonwn

`about.md` and `index.md` are defined at root level.

## License

Copyright (C) 2022-2024 Sunraylabs/Laurent_Lourenco - [licence](LICENSE.md).
