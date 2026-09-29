# abwburns.com

GitHub Pages publishes this repository's `fqlx/site` branch at abwburns.com.
The personal website was copied unchanged from `fqlx/fqlx.github.io` commit
`0868730dc9a0bd77f0c1a62b2f1d7ff3c82c6b14`. Maintain the personal site here.

The `halo-ce-universal/` directory mirrors the generated site from the
`fqlx/halo-ce-universal` repository's `fqlx/pages-static` branch. When publishing
a Halo update, copy only that generated package into this directory, leaving
the personal website files and root CNAME intact. Game data is fetched from
the separate pinned data branch and is not stored in this repository.

The account site `fqlx/fqlx.github.io` has no custom domain, so the primary game
link can remain https://fqlx.github.io/halo-ce-universal/ without redirecting.
Both game links use the same runtime, with separate browser storage per domain.
