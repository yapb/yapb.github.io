# yapb.github.io

Landing page for [YaPB](https://github.com/yapb/yapb) - the Counter-Strike bot.

![Deploy](https://github.com/yapb/yapb.github.io/actions/workflows/deploy-pages.yml/badge.svg)

Live at [yapb.github.io](https://yapb.github.io/). Docs live at
[yapb.github.io/docs](https://yapb.github.io/docs/) (built from
[yapb/docs](https://github.com/yapb/docs), served as this org's project pages).

## Stack

- [Astro](https://astro.build) (static output, no JS framework)
- Vanilla CSS + JS, zero browser dependencies
- Live data from the GitHub API (releases, downloads, stars, forks)

## Develop

```sh
npm ci
npm run dev      # local dev server
npm run build    # static output in dist/
npm run preview  # preview the production build
```

## License

[The Unlicense](https://unlicense.org) - public domain.
