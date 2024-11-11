# sources of larry868.sunraylabs.net website (v2)

Static site https://larry868.sunraylabs.net built with [Hugo](https://gohugo.io/) with [papermod theme](https://github.com/adityatelange/hugo-PaperMod).

To add a post:

```bash
# in english
hugo new --kind post hugo posts/newpost.md
# in french
hugo new --kind post hugo ../fr/posts/newpost.md

```

Published on github pageson every push, home in `./public/`

Need to build/rebuild before to push with:

```bash
hugo mod clean
rm -rf resources/ public/
hugo 
```

:link: [quick reference emojis](https://gohugo.io/quick-reference/emojis/)

## License

Copyright (C) 2022-2024 Larry868 - [licence](LICENSE.md).
