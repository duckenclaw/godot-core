# Game Core (`core`)

Game-agnostic service layer (EventBus, SceneManager, AudioManager, SaveManager, Localization, Debug) as autoload singletons.

Part of the **[godot-game-kit](https://github.com/duckenclaw/godot-game-kit)** modular
template ecosystem — a set of reusable Godot 4 addons shared across FPS,
third-person, 2D sidescroller and top-down game templates.

## Install

**Git submodule (recommended)** — this repo is root-layout, so it drops straight
into a project's `addons/`:

```bash
git submodule add https://github.com/duckenclaw/godot-core addons/core
git submodule update --init
```

Then enable **Game Core** in *Project → Project Settings → Plugins*.

**Godot Asset Library** — an Asset-Library-compatible release (files wrapped under
`addons/core/`) is published per tagged version; search for "Game Core" in the
editor's AssetLib tab.

## Dependencies

none

## Versioning

Semantic versioning via git tags (`v1.0.0`). The Asset Library entry tracks tags.

## License

MIT — see [LICENSE](LICENSE).
