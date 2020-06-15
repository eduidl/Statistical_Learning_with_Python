## 注意

- `python-igraph` はインストールが難しいので，https://github.com/igraph/python-igraph を見て依存パッケージとかをインストールしておくこと．
- `cairocffi` も必要だが，poetryで追加するとpoetryが破壊されるので，pipで入れること．ないとpython-igraphの描画で失敗する．

```terminal
$ poetry shell
$ pip install cairocffi
```

（真面目にやるなら脱依存したい）
