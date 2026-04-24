# effective-cloudflare

<!-- effect-solutions:start -->

## Effect Best Practices

**IMPORTANT:** Always consult effect-solutions before writing Effect code.

1. Run `effect-solutions list` to see available guides
2. Run `effect-solutions show <topic>...` for relevant patterns (supports multiple topics)
3. Search `~/.local/share/effect-solutions/effect` for real implementations

Topics: quick-start, project-setup, tsconfig, basics, services-and-layers, data-modeling, error-handling, config, testing, cli.

Never guess at Effect patterns - check the guide first.

<!-- effect-solutions:end -->

## Local Effect Source

The Effect repository is cloned to `~/.local/share/effect-solutions/effect` for reference.
Use this to explore APIs, find usage examples, and understand implementation
details when the documentation isn't enough.

## Tooling

- **Package manager:** bun (workspace at repo root; examples live under `examples/*`, shared packages under `packages/*`)
- **Version pinning:** Effect + TypeScript versions pinned via bun catalog in root `package.json`; workspace packages reference them as `"catalog:"`
- **Formatter:** `bun run fmt` (oxfmt) / `bun run fmt:check`
- **Linter:** `bun run lint` (oxlint) / `bun run lint:fix`
- **Type check:** `bun run typecheck` (tsc --noEmit, patched with Effect diagnostics)
- **All checks:** `bun run check`
