# dist — prebuilt binaries

Prebuilt yap binaries for machines without Swift toolchains (e.g. mini).
Filenames carry version + architecture.

| File | Upstream tag | Built | Notes |
|---|---|---|---|
| `yap-1.2.1-arm64` | 1.2.1 (7c19dd3) | 2026-11-18, air (Apple Silicon, `swift build -c release`) | pristine upstream, no code changes; has `--word-timestamps` |

Install: `cp <file> /opt/homebrew/bin/yap && chmod +x /opt/homebrew/bin/yap`
Sanity check: `yap transcribe --help | grep word-timestamps`
