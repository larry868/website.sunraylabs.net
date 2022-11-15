# sources of sunraylab.net website

https://sunraylab.net

Static site build with [zazzy](https://github.com/lolorenzo777/zazzy)

Published on github pages, home in `/docs/`

Build with the .vscose task `build`:
    - clear /docs
    - set env var ZS_PUBDIR=docs
    - set env var ZS_HOSTURL=https://sunraylab.net 
    - zazzy build

use [zazzy](https://github.com/lolorenzo777/zazzy) simple static site generator. zazzy need to be instaled first.

In dev mod, run task `watch` and liverserver.

## website structure

- `/.zazzy/` contains html templates
- `/css/` contains `sunraylab.css` source 
- `/jd/` contains `switch.js` source and any other js sources that will be copies into `/docs/js`
- `/img/` contains images that will be copied into `/docs/img`
- `/lab/` contains all lab pages in markdonwn

`about.md` and `index.md` are defined at root level.

## License

Copyright (C) 2022 Sunraylab/Laurent_Lourenco - [licence](LICENSE.md).
