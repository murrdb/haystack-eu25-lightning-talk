# Our Model Took 10 ms. Redis Took 200.

Slides for the Haystack EU 2026 lightning talk, Berlin, 15 Sep 2026.

Built with [reveal.js](https://revealjs.com) 6.0.2, pulled from npm.

## Running

```bash
npm install
npm run dev      # dev server with hot reload
```

Press `s` for speaker notes (the full script lives there), `esc` for the slide overview, `f` for fullscreen.

## Building

```bash
npm run build    # static bundle in dist/
npm run preview  # serve the built bundle
```

`dist/` is self-contained and can be zipped or served from any static host. It needs an actual web
server though — ES modules don't load over `file://`, so use `npm run preview` rather than opening
`dist/index.html` directly.

## Links

- **murrdb**: [github.com/murrdb/murr](https://github.com/murrdb/murr)
- **benchmark**: [github.com/murrdb/murr-benchmark](https://github.com/murrdb/murr-benchmark)
