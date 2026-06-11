# portfolio
Espen Klem's portfolio on work and hobby projects.

## Create new content

```console
hugo new content content/posts/post-name.md
```

Sorting is based on date. Set date in header of file.

Set `draft = false` to make the post show.

bigimg is set in header of file:

```toml
[[Params.bigimg]]
    src = "/portfolio/img/filnavn-01.png"
    desc = "Beskrivende tekst."
    position = "center top"
```

[Photoswipe gallery syntax](https://hugo-theme-beautifulhugo.netlify.app/post/2017-03-20-photoswipe-gallery-sample/).
