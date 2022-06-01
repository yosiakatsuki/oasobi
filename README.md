# oasobi
ブロックテーマ勉強用のお遊びリポジトリ


## 勉強記録

### 2022/06/01
- theme.json追加
  - ブロック設定で色や文字、余白等の設定を使えるように`appearanceTools`を追加
  - settings.layout追加。コンテンツ本文の幅、ワイド幅等を設定できるようにした
- テンプレートをブロックで作成
- ヘッダーはsettings.layout.wideSizeになるように
  - ルートレベルのグループブロックではalign指定ができなかった
  - ルートのグループで「デフォルトレイアウトの継承」をON
  - その中のグループでalign指定ができるようになる

### 2022/05/30
- `parts`フォルダ内にheader.html,footer.html追加
- テンプレート・パーツ関連のドキュメント
  - https://developer.wordpress.org/themes/block-themes/templates-and-template-parts/
- header.htmlに直接HTMLを記述してみた
  - サイトエディター側でブロックのエラーになった。
  - ブロックとして認識される方法で書いてあげる必要がある
- theme.jsonにtemplatePartsを追加し、作成したパーツの名前が表示されるようにした

### 2022/05/27
- テーマとして認識される最低限度のファイルを追加した
  - style.css
  - templates/index.html
- リポジトリ作る
  - 名前はテキトー
  - https://github.com/yosiakatsuki/oasobi
- Twitterで記録つけ始める
  - https://twitter.com/yosiakatsuki/status/1529985621015810048
  - #yosiakatsukiのブロックテーマ勉強記録🦖
- ドキュメント読み始める
  - https://developer.wordpress.org/themes/block-themes/
- 何も知らないテイではじめから勉強開始
