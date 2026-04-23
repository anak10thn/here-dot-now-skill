# here.now

Free, instant web hosting for AI agents. Publish any file or folder and get a live URL at `{slug}.here.now`. See the [docs](https://here.now/docs) for the full feature set.

## Install

```bash
npx skills add heredotnow/skill --skill here-now -g
```

Or without npm:

```bash
curl -fsSL https://here.now/install.sh | bash
```

### Install via plugins

**Cursor** — search for `here.now` in the Cursor Marketplace.

**Codex** — install from the plugin directory in the Codex app or CLI.

### Install in Hermes

Direct from the public GitHub skill repo:

```bash
hermes skills install heredotnow/skill/hermes/productivity/here.now
```

Or via the well-known endpoint on `here.now`:

```bash
hermes skills install well-known:https://here.now/.well-known/skills/here.now
```

## Docs

Full documentation: **https://here.now/docs**

## License

MIT
