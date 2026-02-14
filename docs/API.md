---
slug: /api
sidebar_position: 1
---

# API Reference

`booktabs` exports the following functions:

## `toprule`

`toprule(stroke: heavyrulewidth)`

Adds a horizontal table rule with a default `stroke` width of `0.08em`.

## `midrule`

`midrule(stroke: lightrulewidth)`

Adds a horizontal table rule with a default `stroke` width of `0.05em`.

## `bottomrule`

`bottomrule(stroke: heavyrulewidth)`

Adds a horizontal table rule with a default `stroke` width of `0.08em`.

## `cmidrule`

`cmidrule(y: auto, start: 0, end: none, stroke: cmidrulewidth)`

Adds a partial horizontal table rule with a default `stroke` width of `0.03em`.

- `y`: row position (same semantics as `table.hline`)
- `start`: start column (defaults to `0`)
- `end`: end column (defaults to `none`, i.e. to the last column)
- `stroke`: line width for the rule

## `booktabs-default-table-style`

`booktabs-default-table-style(doc)`

Applies a default style that disables all table borders (`#set table(stroke: none)`) so only explicit booktabs rules are shown.
