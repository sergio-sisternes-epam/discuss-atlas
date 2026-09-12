---
type: document
title: "discuss-atlas"
created: 2026-08-30
description: "Dedicated Atlas store for the discuss skill. Git root is the OKF root."
origin: internal
sensitivity: public
---

# discuss-atlas

Dedicated Atlas store for the discuss skill.

This is a **mount-only knowledge store**, not an APM or skill package. Git root
**is** the OKF root (`SCHEMA.json`, `index.md`).

```text
atlas mount github.com/sergio-sisternes-epam/discuss-atlas --ref main
atlas resolve github.com/sergio-sisternes-epam/discuss-atlas
```

The default mount is
`.atlas/github.com/sergio-sisternes-epam/discuss-atlas`. Use the path printed by
`atlas resolve` as the compile and query root.

In this repository:

```text
atlas compile --root .
```

## License

Copyright (c) 2026 Sergio Sisternes. All rights reserved. The source is publicly
readable but is not open source; see [LICENSE](LICENSE).
