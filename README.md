# tomoyk3jp.github.io

Short URLs for bootstrapping a fresh machine — typed by hand, so they're kept short.

```bash
curl -fsSL tomoyk3jp.github.io/kde | bash   # Kubuntu / KDE desktop (or Hyper-V VM)
curl -fsSL tomoyk3jp.github.io/wsl | bash   # Ubuntu under WSL2 (CLI only)
```

Each file is a tiny stub that downloads the real bootstrap from its gist and runs it with the
terminal attached. Add flags with `| bash -s -- --run`.
