# Agent Atlas

An interactive, responsive visual guide to how coding agents work. Explore six stages, play a timed walkthrough, and inspect illustrative prompts, tool calls, and feedback. Codex and Claude Code share the conceptual flow; examples are simulations, not live agent executions or exact product internals.

## Develop

Requires Node.js 20.19+ or 22.12+.

```sh
npm ci
npm run dev
```

## Production

```sh
npm run build
npm run preview
```

The app runs entirely in the browser and needs no API keys. Google Fonts are optional; system font fallbacks are included.
