# atcoder
AtCoderの作業環境です。

[online-judge-tools](https://github.com/online-judge-tools/oj/blob/master/docs/getting-started.ja.md)と[atcoder-cli](https://www.npmjs.com/package/atcoder-cli)をインストールしたDevContainer環境を提供します。

## MEMO
### ログイン
```
$ acc login
$ oj login https://beta.atcoder.jp/
```

### コンテストID
ABCやARC、AGCの場合 `(abc|arc|agc)\d+`  
特定コンテストはURLから確認

### ディレクトリ作成
```
acc new ${id}
```

### テスト
```
oj t -d ./tests/
```

### 提出
```
acc submit ${file}
```


## TODO
- taskを使った効率化
- デバッグ環境構築