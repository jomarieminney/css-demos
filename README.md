# css-demos
Things you really don't need JavaScript for.
Deployed at https://youdontneedjavascriptforthat.netlify.app/

1. Accordion — `<details name>`, `::details-content`, `interpolate-size`
2. Tabs — `<details>` + grid + subgrid, `:has()` quantity query
3. Modal — `<dialog>`, invoker commands, `@starting-style`, `allow-discrete`, `overlay`
4. Popover — `popover`, anchor positioning, `position-try-fallbacks`
5. Carousel — scroll snap, `scroll-state()` container query, `::scroll-marker`, `::scroll-button()`, `@property`
6. Light & dark — `light-dark()`, `color-scheme`, `prefers-color-scheme`, a radio read by `:root:has()`
7. Marquee — endless logo strip: `@keyframes`, `animation-play-state`, `mask-image`, invoker commands
8. Form — floating labels via `:placeholder-shown`, `:user-invalid`, `field-sizing`, `appearance: base-select`, a restyled range slider, `form:valid` swapping the submit button
9. Scroll-driven — `scroll()` and `view()` timelines, `animation-range`, a sticky sideways strip, an `@property` count-up
10. Filtered gallery — radios read by `:has()`, `[attr~=word]`, sorting with `order`, a live count with counters, subgrid, a replayed fade

Everything lives in one stylesheet, `css/main.css`, split into cascade layers (reset, theme, base, components, demo, utilities, prefs) with each demo under its own heading in the demo layer. Also shared: a `popover` site menu (hamburger to cross, no script), `@supports`-graded feature chips, container queries, cross-document view transitions.

Serve it over http rather than opening the files directly if running locally, or the view transitions between pages won't run.
