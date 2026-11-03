# afenc

A Rust project in the tbhb-dev organization.

## Getting started

```sh
mise install
uv sync
bazelisk run //:bazel_env
uv run tools/interim/install.sh
bazelisk test //...
```

`bazelisk test //...` runs every lint, audit, and test gate. The documentation is in [docs/](docs/index.md).
