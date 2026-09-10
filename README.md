# whisper.cpp

[中文版本](./README.cn.md)

Port of OpenAI's Whisper model in C/C++

![whisper.cpp](https://repo.x-cmd.io/whisper.cpp.svg)

## Install

```sh
x install whisper.cpp
```

## Code insight

Total: **488,672** lines of code across **870** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Cpp | 185,736 | 14,126 | 34,371 | 290 |
| CHeader | 110,720 | 17,712 | 20,397 | 200 |
| C | 67,801 | 5,777 | 13,709 | 115 |
| CppHeader | 31,922 | 5,610 | 5,823 | 76 |
| Cuda | 20,597 | 1,252 | 3,758 | 189 |

## OpenSSF Scorecard

Overall score: **5.1 / 10**

Lowest-scoring checks:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Fuzzing** (0/10) — project is not fuzzed

## Source

- **Upstream**: <https://github.com/ggerganov/whisper.cpp>
- **License**: MIT

## Release

- **Latest**: `b5127` (2026-08-20)
- **Last commit**: 2026-09-10
- **Assets in release**: 9

## Popularity

- **Stars**: 53,587 · **Forks**: 6,135 · **Open issues**: 1,975 · **Contributors**: 1,030

## Totals (cumulative)

- **Releases**: 41 · **Merged PRs**: 1057 · **Open PRs**: 175 · **Closed issues**: 1807 · **Open issues**: 168 · **Commits**: 5130

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 3 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-12 | 4 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-12 | 7 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-14 | 10 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-15 | 14 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-20 | 24 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [whisper-b4938-xcframework.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-b4938-xcframework.zip) | 51.1 MiB | `other` |
| [whisper-bin-ubuntu-arm64.tar.gz](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-bin-ubuntu-arm64.tar.gz) | 4.4 MiB | `native/linux/arm64` |
| [whisper-bin-ubuntu-x64.tar.gz](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-bin-ubuntu-x64.tar.gz) | 9.1 MiB | `native/unknown` |
| [whisper-bin-Win32.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-bin-Win32.zip) | 5.1 MiB | `native/win/x64` |
| [whisper-bin-x64.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-bin-x64.zip) | 8.0 MiB | `other` |
| [whisper-blas-bin-Win32.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-blas-bin-Win32.zip) | 11.8 MiB | `native/win/x64` |
| [whisper-blas-bin-x64.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-blas-bin-x64.zip) | 20.2 MiB | `other` |
| [whisper-cublas-11.8.0-bin-x64.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-cublas-11.8.0-bin-x64.zip) | 257.4 MiB | `other` |
| [whisper-cublas-12.4.0-bin-x64.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-cublas-12.4.0-bin-x64.zip) | 640.0 MiB | `other` |

## Distribution status

Reported by **68** distros on [repology.org](https://repology.org/project/whisper.cpp). **19** are ✅ on the latest upstream release, **37** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `1.9.3` | ✅ latest |
| Debian 14 | `1.9.3` | ✅ latest |
| Ubuntu 26.04 LTS | `1.8.3` | ⚠️ outdated |
| Arch | `1.9.3` | ✅ latest |
| Homebrew | `1.9.2` | ⚠️ outdated |
| Fedora rawhide | `1.9.3` | ✅ latest |
| Nix unstable | `1.9.2` | ⚠️ outdated |
| Alpine edge | `1.9.3` | ✅ latest |

## Improve this data

Install metadata for whisper.cpp lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `whisper.cpp` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/whisper.cpp.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T21:43:27Z._
