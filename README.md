# use-rusty-math

Example project importing [rusty-math](https://github.com/AndrewADev/rusty-math).

## Installation

Follow the [rusty-math installation instructions](https://github.com/AndrewADev/rusty-math#installation) to add it as a dependency, then:

```bash
uv sync
```

## Local development

To test against a local checkout of rusty-math before a release, temporarily point uv at the local path in `pyproject.toml`:

```toml
[tool.uv.sources]
rusty-math = { path = "../rusty-math" }
```

Then run `uv sync` to rebuild and reinstall from source. Revert to the release URL when done.
