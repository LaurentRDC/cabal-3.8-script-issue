# cabal-3.8-script-issue

This repository displays an issue when running scripts with `cabal run` in version 3.8

To reproduce the issue, run the following command:

```sh
cabal run -- scripts/MyScript.hs
```

With cabal 3.6.2.0, this works and outputs `someFunc`. With Cabal 3.8.1.0, the script does not compile.
