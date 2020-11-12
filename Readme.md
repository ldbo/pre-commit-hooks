# Pre-commit hooks

[pre-commit](https://pre-commit.com) hooks:

- ``mypy``: run mypy static type check

To use, add this to you ``.pre-commit-config.yaml``:

```yaml
- repo: https://github.com/ldbo/pre-commit-hooks
  rev: master
  hooks:
    - ...
```
