# Hugo Mermaid Module

[![Used By](https://img.shields.io/badge/dynamic/json?color=success&label=used+by&query=repositories_humanize&logo=hugo&style=flat-square&url=https://api.razonyang.com/v1/github/dependents/hugomods/mermaid)](https://github.com/hugomods/mermaid/network/dependents)
![Hugo Requirements](https://img.shields.io/badge/dynamic/json?color=important&label=requirements&query=requirements&logo=hugo&style=flat-square&url=https://api.razonyang.com/v1/hugo/modules/github.com/hugomods/mermaid)
[![License](https://img.shields.io/github/license/hugomods/mermaid?style=flat-square)](https://github.com/hugomods/mermaid/blob/main/LICENSE)
[![Version](https://img.shields.io/github/v/tag/hugomods/mermaid?label=version&style=flat-square)](https://github.com/hugomods/mermaid/tags)

## Installation

### 1. Import Module

```toml
[[module.imports]]
path = "github.com/hugomods/mermaid"
```

### 2. Import the JavaScript

> Skip this step if your theme supports [HugoPress](https://github.com/razonyang/hugopress).

```go
{{ partial "mermaid/assets/js" . }}
```

## Configuration

The site parameters as following.

| Parameter        |  Type  |              Default              | Description             |
| ---------------- | :----: | :-------------------------------: | ----------------------- |
| `mermaid.js_url` | String | Latest version from JS Delivr CDN | The Mermaid script URL. |
