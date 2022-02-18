# Hugo Mermaid Module

## Installation

### 1. Import Module

```toml
[[module.imports]]
path = "github.com/razonyang/hugo-mod-mermaid"
```

## 2. Import the JavaScript

> Skip this step if your theme supports [HugoPress](https://github.com/razonyang/hugopress).

```go
{{ partial "mermaid/assets/js" . }}
```
