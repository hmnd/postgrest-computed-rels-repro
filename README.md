# Postgrest Computed Relationships Bug

> [!IMPORTANT]
> Includes failing test for a computed relationship
> whose name differs from the foreign table

## Repro

- Install deps with `pnpm install`
- Run type test `pnpm test`
- Switch to the [`broken`](https://github.com/hmnd/postgrest-computed-rels-repro/tree/broken) branch and repeat
