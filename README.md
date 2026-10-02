# Open Language - German

The German coursebook from Open Language: grammar, concepts, writing and vocabulary articles from A1 to B2, each with listening examples.

## Layout

```
docs/<level>/<category>/    articles, one topic each
open-language.yml           workspace settings and the cast of voices
```

Levels are `a1` to `b2`. Categories are `grammar`, `concepts`, `writing` and `vocabulary`.

## Working on the content

Install with [uv](https://docs.astral.sh/uv/):

```
uv sync
```

Check everything the way CI does:

```
uv run ol check
```

That runs the article checks and a strict build of the site. Build and preview locally with `uv run ol docs`.

New articles start from a template. `uv run ol templates` lists them and `uv run ol templates grammar-article.md` prints one.

## Reporting a problem

Found a wrong example, a typo or a confusing explanation? [Open an issue](https://github.com/OpenLanguageStudio/german/issues).
