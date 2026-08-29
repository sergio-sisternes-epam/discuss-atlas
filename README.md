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

This is a **knowledge store**, not a skill package. Git root **is** the OKF root (`SCHEMA.json`, `index.md`).

```text
atlas auth login --host github.com
atlas mount github.com/sergio-sisternes-epam/discuss-atlas --ref main --target references/atlas
```

Mount path = compile/query root: `references/atlas`

In this repository:

```text
atlas compile --root .
```

## APM

```text
apm install sergio-sisternes-epam/discuss-atlas
```

Store package depends on `sergio-sisternes-epam/okf` and `sergio-sisternes-epam/atlas`.
