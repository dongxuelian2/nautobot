# Nautobot Job Result wrapping regression screenshots

Screenshots from local Selenium regression tests for nautobot/nautobot#9684, using synthetic JobResult data.

Code commit: `f1771b948fecf3e2e7a97bd87895c2fec9dacd6d`.

- `before-token-1440.png`: original rendering, 400-character exception, 1440px viewport.
- `after-token-1440.png`: fixed rendering of the same exception and viewport.
- `after-token-375.png`: fixed rendering after a real HTMX poll, 375px viewport, navigation collapsed.

Images are kept on this separate branch to preserve the minimal code change in the pull request.
