# pysta-glslEditor dev-memo
> [Pythonista](http://omz-software.com/pythonista/) glslEditor


## 遊び方 🎮
`runScript.py` をPythonista で実行😊


# 📝 2020/01/04
(クローン)リポジトリ作成

## やること
- 以前作成の状態を思い出す
- 当面は、コアの`glslEditor.js` を読むかなぁ🤓

### Editor 側
- 使わない機能の排除
- ソースコードの見通しを良くする
- 記載するコード を外に出す
	- glsl の拡張子って何にすればええんやろ🤔
	- Pythonista 側から見やすい方がええか
- Vim 操作add on 使う？
	- キー の擬似呼び出し探さないと
- 吐出し画と、エディット画面を同期させない


### Pythonista 側
- toolbar 挿す
- 諸々の`WKWebView` の確認
- font 呼び出し & 変更
	- `source code pro` かなぁ？
- なるべくスクリプトファイル一つは無理か🙃
- ブラウザの本来のリンク機能を消す
- スワイプで、undo/redo
- ステータスバー消す？


## やらかした？かも😂
- iSH でのbranch は、`gh-pages`
- Pythonista のbranch は、`master`


Pythonista 上で、気がつかずに`master` でpush 😩
- iPhone
  - branch `pysta-pome` を、作成
  - Pythonista 上で、`master` を`pysta-pome` にmerge

- GitHub
  - clone 直後のdefault branch は`gh-pages`
  - default を`pysta-pome` へ

- iPhone
  - 再度Pythonista 側をpush
  - iSH をpull
  - なんか、Pythonista とiSH のリポジトリのズレが
  - とりま、Pythonista 側を消して再度clone

多分これでええか？🥺作業が全く進まん、、、、😤

やらかしてたら、ごめんなさい🙇‍♂️


そもそも、iSH の連携必要性🤔...🤗

