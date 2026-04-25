<p align="center">
  <img src="assets/readme-banner.svg" alt="Repo Onboarding Check banner" width="100%">
</p>

<h1 align="center">Repo Onboarding Check</h1>

<p align="center">检查新贡献者是否能从 README 找到安装、运行、测试、贡献和求助路径。</p>

<p align="center"><a href="README.md">English</a> · <a href="#quick-start">快速开始</a> · <a href="#checks">检查项</a> · <a href="#ci-usage">CI</a></p>

<p align="center">
  <img alt="Node.js" src="https://img.shields.io/badge/node-%3E%3D18-2563EB">
  <img alt="dependencies" src="https://img.shields.io/badge/dependencies-0-111827">
  <img alt="license" src="https://img.shields.io/badge/license-MIT-16A34A">
</p>

<p align="center">
  <img src="assets/cli-preview.svg" alt="Repo Onboarding Check CLI preview" width="88%">
</p>

## 为什么做这个

AI Agent 工具越来越多，但很多仓库缺少能在本地和 CI 里重复执行的小检查。这个工具保持零依赖、可镜像、可复制，适合学生、独立开发者和开源维护者使用。

## Quick Start

```bash
npx github:aolingge/repo-onboarding-check --path README.md
```

```bash
npx github:aolingge/repo-onboarding-check --path README.md --markdown > report.md
npx github:aolingge/repo-onboarding-check --path README.md --sarif > results.sarif
npx github:aolingge/repo-onboarding-check --path README.md --annotations
```

## Checks

| Check | What it looks for |
| --- | --- |
| install | Explains install/setup. |
| run | Explains how to run. |
| test | Explains tests. |
| contribute | Explains contribution/support. |

## CI Usage

See [docs/github-actions.md](docs/github-actions.md) and [docs/quality-gates.md](docs/quality-gates.md).

## Mirrors

- GitHub: https://github.com/aolingge/repo-onboarding-check
- Gitee: https://gitee.com/aolingge/repo-onboarding-check

## Contributing

Good first PRs: add checks, add fixtures, improve docs, or add GitHub Actions examples.

## License

MIT
