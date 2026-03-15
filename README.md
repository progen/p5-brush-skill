# p5-brush skill

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skill that generates generative art using [p5.brush](https://github.com/acamposuribe/p5.brush) by [@acamposuribe](https://github.com/acamposuribe).

Describe what you want — "a stormy ocean in watercolor", "cross-hatched botanical sketch" — and get a standalone HTML file with natural, hand-drawn-style artwork.

## What it does

- Wraps the p5.brush v2 API (pencils, charcoal, markers, watercolor fills, hatch patterns, vector fields)
- Generates self-contained HTML files using CDN-hosted libraries — no local setup needed
- Handles all the WEBGL boilerplate, coordinate translation, and seed management

## Install

Copy or symlink this folder into your Claude Code skills directory:

```bash
# Option 1: symlink
ln -s /path/to/p5-brush-skill ~/.claude/skills/p5-brush

# Option 2: copy
cp -r /path/to/p5-brush-skill ~/.claude/skills/p5-brush
```

## Usage

In Claude Code:

```
/p5-brush a field of wildflowers in charcoal on cream paper
```

```
/p5-brush abstract watercolor circles with heavy bleed, dark background
```

```
/p5-brush cross-hatched portrait grid in the style of the author's Happy Grid example
```

## Credits

- **p5.brush** by [Alejandro Campos (@acamposuribe)](https://github.com/acamposuribe/p5.brush) — MIT License
- Built on [p5.js](https://p5js.org/)

## License

MIT
