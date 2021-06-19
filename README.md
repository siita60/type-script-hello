# これは？

WEB DB PRESS vol.117を参考にtypescriptを練習するプロジェクト（今更）

## 諸々使っているもの

- WEB DB PRESS vol.117
- gitignore.io 
    - refs: https://www.toptal.com/developers/gitignore
    - いい感じに.gitignoreを生成するAPI


# memos

## 基本

- tscでコンパイル->結果はdistにjsとして吐き出される
- 吐き出されたjsはjsなので（？）、nodeコマンドで実行できる`node dist/index.js`

## REPL

- ts-node
  - コンパイルして実行してくれる
  - 例えば`npx ts-node src/index.ts `　でindex.tsをコンパイルして実行までしてくれる。便利

## tsconfig

- 色々設定あるよって話
- すくなくとも`null`や`undefined`の代入をコンパイルで防げる`"strictNullChecks": true`はいれておくべき

## treeを作る

- 
