# just-pre-commit

A [pre-commit](https://pre-commit.com/) hook that formats justfiles with `just --fmt`,
using the prebuilt [`rust-just`](https://pypi.org/project/rust-just/) wheels from PyPI.
Tags follow [just](https://github.com/casey/just) releases.

```yaml
repos:
  - repo: https://github.com/UnknownPlatypus/just-pre-commit
    rev: v1.59.0
    hooks:
      - id: just-fmt
```

Formats `justfile`, `.justfile` (any case) and `*.just` files.
