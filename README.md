# lolay/scoop-bucket

[Scoop](https://scoop.sh) bucket for [lolay](https://github.com/lolay) tools on Windows.

## Install

```powershell
scoop bucket add lolay https://github.com/lolay/scoop-bucket
scoop install lolay/triage
```

## Manifests

| Package | Description |
|---------|-------------|
| [`triage`](bucket/triage.json) | The environment doctor — declarative prerequisite checks ([lolay/triage](https://github.com/lolay/triage)) |

## Updating manifests

Manifests are updated automatically by the `lolay/triage` release workflow via
`scripts/publish-scoop.sh`. Maintainers do not need to update them by hand.
