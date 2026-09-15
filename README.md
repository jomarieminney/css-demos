# css-demos
Things you really don't need JavaScript for.

1. Accordion — `<details name>`, `::details-content`, `interpolate-size`
2. Tabs — `<details>` + grid + subgrid, `:has()` quantity query
3. Modal — `<dialog>`, invoker commands, `@starting-style`, `allow-discrete`, `overlay`
4. Popover — `popover`, anchor positioning, `position-try-fallbacks`
5. Carousel — `:has()` state, `sign()` / `abs()` maths, 3D transforms

Shared: cascade layers, `@supports`-graded feature chips, container queries, cross-document view transitions.

Serve it over http (e.g. `npx serve .`) rather than opening the files directly, or the view transitions between pages won't run.
