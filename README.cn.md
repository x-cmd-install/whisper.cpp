# whisper.cpp

[English version](./README.md)

Port of OpenAI's Whisper model in C/C++

![whisper.cpp](https://repo.x-cmd.io/whisper.cpp.svg?lang=zh)

## 安装

```sh
x install whisper.cpp
```

## 代码洞察

合计: **488,672** 行代码（覆盖前 5 种语言、共 **870** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Cpp | 185,736 | 14,126 | 34,371 | 290 |
| CHeader | 110,720 | 17,712 | 20,397 | 200 |
| C | 67,801 | 5,777 | 13,709 | 115 |
| CppHeader | 31,922 | 5,610 | 5,823 | 76 |
| Cuda | 20,597 | 1,252 | 3,758 | 189 |

## OpenSSF Scorecard 评分

总评分: **5.1 / 10**

评分最低的几项:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Fuzzing** (0/10) — project is not fuzzed

## 源代码

- **上游仓库**: <https://github.com/ggerganov/whisper.cpp>
- **许可证**: MIT

## 发布

- **最新版本**: `b5127` (2026-08-20)
- **最近提交**: 2026-09-10
- **Release 含资产**: 9 个

## 流行度

- **Star**: 53,588 · **Fork**: 6,135 · **开放 issue**: 1,975 · **贡献者**: 1,030

## 累计统计

- **发布数**: 41 · **已合并 PR**: 1057 · **开放 PR**: 175 · **已关闭 issue**: 1807 · **开放 issue**: 168 · **提交数**: 5130

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 3 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-12 | 4 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-12 | 7 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-14 | 10 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-15 | 14 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-20 | 24 | 0 | 0 | 0 | 0 | 0 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [whisper-b4938-xcframework.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-b4938-xcframework.zip) | 51.1 MiB | `other` |
| [whisper-bin-ubuntu-arm64.tar.gz](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-bin-ubuntu-arm64.tar.gz) | 4.4 MiB | `native/linux/arm64` |
| [whisper-bin-ubuntu-x64.tar.gz](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-bin-ubuntu-x64.tar.gz) | 9.1 MiB | `native/unknown` |
| [whisper-bin-Win32.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-bin-Win32.zip) | 5.1 MiB | `native/win/x64` |
| [whisper-bin-x64.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-bin-x64.zip) | 8.0 MiB | `other` |
| [whisper-blas-bin-Win32.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-blas-bin-Win32.zip) | 11.8 MiB | `native/win/x64` |
| [whisper-blas-bin-x64.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-blas-bin-x64.zip) | 20.2 MiB | `other` |
| [whisper-cublas-11.8.0-bin-x64.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-cublas-11.8.0-bin-x64.zip) | 257.4 MiB | `other` |
| [whisper-cublas-12.4.0-bin-x64.zip](https://github.com/ggerganov/whisper.cpp/releases/download/b4938/whisper-cublas-12.4.0-bin-x64.zip) | 640.0 MiB | `other` |

## 发行版状态

在 [repology.org](https://repology.org/project/whisper.cpp) 上共有 **68** 个发行版报告此项目。**19** 个 ✅ 已是最新上游版本，**37** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `1.9.3` | ✅ latest |
| Debian 14 | `1.9.3` | ✅ latest |
| Ubuntu 26.04 LTS | `1.8.3` | ⚠️ outdated |
| Arch | `1.9.3` | ✅ latest |
| Homebrew | `1.9.2` | ⚠️ outdated |
| Fedora rawhide | `1.9.3` | ✅ latest |
| Nix unstable | `1.9.2` | ⚠️ outdated |
| Alpine edge | `1.9.3` | ✅ latest |

## 改进这些数据

whisper.cpp 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `whisper.cpp` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/whisper.cpp.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T22:07:23Z._
