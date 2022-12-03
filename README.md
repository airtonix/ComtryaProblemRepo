# ComtryaProblemRepo

Illustrates some issues with Comtrya

- if dependencies are not used to directly drive the order of execution, then manifest execution order is random

# Install

## From Web

you can just let the web install do its thing...

**linux**

```bash
curl -fsSL https://get.comtrya.dev | sh
comtrya -d https://github.com/airtonix/ComtryaProblemRepo apply
```

**macos**

```bash
curl -fsSL https://get.comtrya.dev | sh
comtrya -d https://github.com/airtonix/ComtryaProblemRepo apply
```

**windows**

```powershell
iwr "https://get.comtrya.dev/ps" -UseBasicParsing | iex
comtrya -d https://github.com/airtonix/ComtryaProblemRepo apply
```
