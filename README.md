# Copilot Marketplace Playground

This repository is a small scaffold for a Copilot-style plugin marketplace.

## Layout

- `.github/plugin/marketplace.json` contains the marketplace catalog.
- `plugins/hello-default` is a mock plugin that uses the default `skills/<name>/SKILL.md` layout.
- `plugins/hello-custom` is a mock plugin that uses a custom skills path defined in its manifest.

## Included marketplace entries

1. `hello-default` - local plugin using default skill discovery.
2. `hello-custom` - local plugin using `./custom-skills`.
3. `awesome-copilot` - external plugin pinned to `github/awesome-copilot` at `320bb9558fac4cf9c7c07e03fcdd21fda5041c96` with `path` set to `plugins/awesome-copilot`.

## Notes

This playground follows the requested Copilot adaptation by using `.github/plugin/marketplace.json` for the marketplace catalog and `plugins/<name>/plugin.json` for local plugin manifests.
