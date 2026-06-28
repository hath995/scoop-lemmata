# scoop-lemmata

A [Scoop](https://scoop.sh) bucket for **`lem`**, the verified package manager for Dafny.

## Install

```powershell
scoop bucket add lemmata https://github.com/hath995/scoop-lemmata
scoop install lem
lem doctor
```

`lem` is self-contained — it bundles a pinned Dafny + Z3, so you need neither the
.NET runtime nor a separate Dafny install, and your PATH is left untouched.

Release archives are hosted at
[hath995/lemmata-releases](https://github.com/hath995/lemmata-releases/releases).

> The shipped `lem.exe` is currently unsigned; Windows SmartScreen may warn on first run.
