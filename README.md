# Conventional Changelog action

This action will bump version, tag commit and generate a changelog with conventional commits.

## Reason to fork
Centralize the type to header mapping like so:
```js
    const config = cc({
      "types": [
          {"type": "feat", "section": "🚀 Features"},
          {"type": "fix", "section": "🐛 Bug Fixes"},
          {"type": "perf", "section": "🏎️ Performance"},
      ]
    })
```
> [documentation](https://github.com/TriPSs/conventional-changelog-action/tree/v4)
