# Bodega One Code — Scoop Bucket

The clean Windows install path for [Bodega One Code](https://bodegaone.ai), the
local-first AI coding agent (TUI + headless). Scoop installs are not
SmartScreen-flagged.

```powershell
scoop bucket add bodega https://github.com/BodegaoneAI/scoop-bodega
scoop install bodega
```

Then:

```powershell
bodega doctor   # verify the install
bodega          # start the TUI
```

The manifest carries `checkver`/`autoupdate` against
[bodegaone-cli-releases](https://github.com/BodegaoneAI/bodegaone-cli-releases),
so `scoop update bodega` tracks new releases automatically.
