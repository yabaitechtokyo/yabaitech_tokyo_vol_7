# yabai2021W
![build](https://github.com/yabaitechtokyo/yabai2021W/workflows/build/badge.svg?branch=master)

## How to set up dependencies
Follow [*nix 向け SATySFi インストールバトル手引き 2020年10月版](https://qiita.com/na4zagin3/items/a6e025c17ef991a4c923) to set up SATySFi and Satyrographos in your dev environment.

``` bash
$ opam pin add yabai2021w.opam "file://${PWD}"
$ satyrographos install
```

Then you can build by
``` bash
$ satysfi main.saty
```
