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

## HUGO shortcodes

### message shortcode


{{% message emoji="🧠" bg="#FFE4E1" %}}
This is a custom message for a concept
{{% /message %}}

{{% message emoji="✨" bg="#FDF5E6" %}}
This is a custom message for a tip
{{% /message %}}

{{% message emoji="📌" bg="#F4F4F8" %}}
This is a custom message for an example
{{% /message %}}

{{% message emoji="🎭" bg="#E3F2FD" %}}
This is a custom message for an anecdote
{{% /message %}}


## License

Copyright (C) 2022-2024 Larry868 - [licence](LICENSE.md).
