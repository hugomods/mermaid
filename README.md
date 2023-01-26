# Hugo Mermaid Module

[![Used By](https://img.shields.io/badge/dynamic/json?color=success&label=used+by&query=repositories_humanize&logo=hugo&style=flat-square&url=https://api.razonyang.com/v1/github/dependents/razonyang/hugo-mod-mermaid)](https://github.com/razonyang/hugo-mod-mermaid/network/dependents)
![Hugo Requirements](https://img.shields.io/badge/dynamic/json?color=important&label=requirements&query=requirements&logo=hugo&style=flat-square&url=https://api.razonyang.com/v1/hugo/modules/github.com/razonyang/hugo-mod-mermaid)
[![License](https://img.shields.io/github/license/razonyang/hugo-mod-mermaid?style=flat-square)](https://github.com/razonyang/hugo-mod-mermaid/blob/main/LICENSE)
[![Version](https://img.shields.io/github/v/tag/razonyang/hugo-mod-mermaid?label=version&style=flat-square)](https://github.com/razonyang/hugo-mod-mermaid/tags)

## Installation

### 1. Import Module

```toml
[[module.imports]]
path = "github.com/razonyang/hugo-mod-mermaid"
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
