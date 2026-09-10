# kubeshark

[中文版本](./README.cn.md)

eBPF-powered network observability for Kubernetes. Indexes L4/L7 traffic with full K8s context, decrypts TLS without keys. Queryable by AI agents via MCP and humans via dashboard.

![kubeshark](https://repo.x-cmd.io/kubeshark.svg)

## Install

```sh
x install kubeshark
```

## Code insight

Total: **12,971** lines of code across **112** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 7,784 | 514 | 1,392 | 62 |
| Yaml | 4,451 | 120 | 128 | 47 |
| Makefile | 341 | 8 | 54 | 1 |
| Json | 178 | 0 | 0 | 1 |
| Pan | 121 | 0 | 15 | 1 |

## Source

- **Upstream**: <https://github.com/kubeshark/kubeshark>
- **Homepage**: <https://kubeshark.com>
- **License**: Apache-2.0

## Release

- **Latest**: `v53.4.0` (2026-08-13)
- **Last commit**: 2026-09-09
- **Assets in release**: 22

## Popularity

- **Stars**: 12,075 · **Forks**: 547 · **Open issues**: 387 · **Contributors**: 46

## Totals (cumulative)

- **Releases**: 467 · **Merged PRs**: 1345 · **Open PRs**: 8 · **Closed issues**: 247 · **Open issues**: 140 · **Commits**: 2245

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 1 | 4 | 5 | 1 | 0 | 2 |
| last60d | 2026-07-12 | 1 | 7 | 6 | 2 | 1 | 9 |
| 90d | 2026-06-12 | 1 | 10 | 7 | 3 | 2 | 11 |
| last180d | 2026-03-14 | 6 | 43 | 8 | 13 | 12 | 45 |
| 360d | 2025-09-15 | 13 | 103 | 8 | 20 | 18 | 110 |
| last720d | 2024-09-20 | 36 | 202 | 8 | 52 | 26 | 284 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [kubeshark-mcp_darwin_amd64.mcpb](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark-mcp_darwin_amd64.mcpb) | 60.7 MiB | `native/darwin/x64` |
| [kubeshark-mcp_darwin_amd64.mcpb.sha256](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark-mcp_darwin_amd64.mcpb.sha256) | 98 B | `native/darwin/x64` |
| [kubeshark-mcp_darwin_arm64.mcpb](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark-mcp_darwin_arm64.mcpb) | 57.5 MiB | `native/darwin/arm64` |
| [kubeshark-mcp_darwin_arm64.mcpb.sha256](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark-mcp_darwin_arm64.mcpb.sha256) | 98 B | `native/darwin/arm64` |
| [kubeshark-mcp_linux_amd64.mcpb](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark-mcp_linux_amd64.mcpb) | 59.3 MiB | `native/linux/x64` |
| [kubeshark-mcp_linux_amd64.mcpb.sha256](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark-mcp_linux_amd64.mcpb.sha256) | 97 B | `native/linux/x64` |
| [kubeshark-mcp_linux_arm64.mcpb](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark-mcp_linux_arm64.mcpb) | 55.8 MiB | `native/linux/arm64` |
| [kubeshark-mcp_linux_arm64.mcpb.sha256](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark-mcp_linux_arm64.mcpb.sha256) | 97 B | `native/linux/arm64` |
| [kubeshark-mcp_windows_amd64.mcpb](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark-mcp_windows_amd64.mcpb) | 60.7 MiB | `native/win/x64` |
| [kubeshark-mcp_windows_amd64.mcpb.sha256](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark-mcp_windows_amd64.mcpb.sha256) | 99 B | `native/win/x64` |
| [kubeshark.exe](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark.exe) | 60.7 MiB | `other` |
| [kubeshark.exe.sha256](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark.exe.sha256) | 80 B | `other` |
| [kubeshark_darwin_amd64](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark_darwin_amd64) | 60.7 MiB | `native/darwin/x64` |
| [kubeshark_darwin_amd64.sha256](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark_darwin_amd64.sha256) | 89 B | `native/darwin/x64` |
| [kubeshark_darwin_arm64](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark_darwin_arm64) | 57.5 MiB | `native/darwin/arm64` |
| [kubeshark_darwin_arm64.sha256](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark_darwin_arm64.sha256) | 89 B | `native/darwin/arm64` |
| [kubeshark_linux_amd64](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark_linux_amd64) | 59.3 MiB | `native/linux/x64` |
| [kubeshark_linux_amd64.sha256](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark_linux_amd64.sha256) | 88 B | `native/linux/x64` |
| [kubeshark_linux_arm64](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark_linux_arm64) | 55.8 MiB | `native/linux/arm64` |
| [kubeshark_linux_arm64.sha256](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/kubeshark_linux_arm64.sha256) | 88 B | `native/linux/arm64` |
| [README.md](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/README.md) | 993 B | `other` |
| [version.txt](https://github.com/kubeshark/kubeshark/releases/download/v53.4.0/version.txt) | 8 B | `other` |

## Distribution status

Reported by **12** distros on [repology.org](https://repology.org/project/kubeshark). **3** are ✅ on the latest upstream release, **7** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `53.4.0` | ✅ latest |
| Nix unstable | `53.4.0` | ✅ latest |

## Improve this data

Install metadata for kubeshark lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `kubeshark` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/kubeshark.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T22:19:33Z._
