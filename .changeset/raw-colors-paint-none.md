---
"@shadcn/lint": patch
---

Accept `fill-none` and `stroke-none` in `no-raw-colors`. `none` is SVG's "paint nothing", not a color, and the rule already accepted it as `fill="none"`.
