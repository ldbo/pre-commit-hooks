# Pre-commit hooks

[pre-commit](https://pre-commit.com) hooks:

- ``mypy``: run [mypy](http://mypy-lang.org) static type check
- ``lint-markdown``: use
  [markdownlint](https://github.com/DavidAnson/markdownlint) to try to format
  Markdown files in place

To use, add this to you ``.pre-commit-config.yaml``:

```yaml
- repo: https://github.com/ldbo/pre-commit-hooks
  rev: master
  hooks:
    - ...
```
