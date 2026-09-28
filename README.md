# tomcoolpxl's Scoop bucket

[![Tests](https://github.com/tomcoolpxl/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/tomcoolpxl/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/tomcoolpxl/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/tomcoolpxl/scoop-bucket/actions/workflows/excavator.yml)

A [Scoop](https://scoop.sh) bucket. Everything in it installs as a normal user, without
admin.

```pwsh
scoop bucket add tomcoolpxl https://github.com/tomcoolpxl/scoop-bucket
scoop install cash
```

| App | What it is |
| --- | --- |
| [cash](https://github.com/tomcoolpxl/cash) | Cool Again Shell: a Bash-language shell for Windows, with its Unix tools built in. Adds a Windows Terminal profile on install. |

The manifests follow each app's GitHub releases: the Excavator workflow checks every four
hours and updates them.
