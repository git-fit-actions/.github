<div align="center">

### git-fit-actions

**Automation & CI infrastructure for [git-fit](https://github.com/Lax/git-fit)**

Fitness activity management for Git — aggregate workout data from Garmin, Strava, Apple Health, Keep, and more into a local SQLite database.

[![Gem Version](https://badge.fury.io/rb/git-fit.svg)](https://badge.fury.io/rb/git-fit)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

</div>

## Repositories

| Repo | Description |
|------|-------------|
| [git-fit](https://github.com/Lax/git-fit) | Core gem — CLI tool for fitness activity aggregation |
| `git-fit-actions/*` | Shared CI workflows, action templates, and automation |

## Getting Started

```bash
gem install git-fit
git fit init
git fit import apple_health
git fit export json
```

## License

MIT
