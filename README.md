# Taplo pre-commit hooks

[pre-commit](https://pre-commit.com) hooks for [taplo](https://taplo.tamasfe.dev).

> A versatile, feature-rich TOML toolkit.

## Usage

Using pre-commit's built-in Rust language support:

```yaml
repos:
  - repo: https://github.com/nikaro/taplo-pre-commit
    rev: main
    hooks:
      - id: taplo-lint
      - id: taplo-format
```

Using taplo's Docker image:

```yaml
repos:
  - repo: https://github.com/nikaro/taplo-pre-commit
    rev: main
    hooks:
      - id: taplo-lint-docker
      - id: taplo-format-docker
```
