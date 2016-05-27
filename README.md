# plugins-snippets-etc
often use plugins, snippets, etc.

上書きはBKUP取ってから！

## Plug-ins
~/Library/Application Support/Developer/Shared/Xcode/Plug-ins

## Snippets
~/Library/Developer/Xcode/UserData/CodeSnippets

## FontsAndColors

~/Library/Developer/Xcode/UserData/FontAndColorThemes

## Key Bindings

※権限制限あるので要変更
/Applications/Xcode.app/Contents/Frameworks/IDEKit.framework/Versions/A/Resources
NS

## Xcode Shortcut

| コマンド | 説明 |
| ---- | ---- |
| **ファイル操作** | __ |
| ⌘ + shit + o | ファイル検索 |
| ⌘ + ctrl + ↑/↓ | .m/.h切替 |
| ⌘ + ctrl + ←/→ | 履歴移動 |
| ⌘ + 0 | 左サイドメニュ開閉 |
| ⌘ + alt + 0 | 右サイドメニュ開閉 |
| ⌘ + 1~8 | 左サイドメニュタブ切替 |
| ⌘ + f | ファイル内検索 |
| ⌘ + alt + f | ファイル内置換 |
| ⌘ + shift + j | 今開いているファイルのリストのカーソル移動 |
| ⌘ + shift + f | プロジェクト内ファイル検索 |
| ⌘ + ⌥ + j | ファイル一覧フィルター |
| ⌘ + shift + y | デバッグエリア開閉 |
| ctrl + 1 | (project navigatorで)呼び出し元検索 |
| **実行** | __ |
| ⌘ + r | 実行 |
| ⌘ + b | ビルド |
| ⌘ + . | 中止 |
| ⌘ + shift + k | クリーン |
| ⌘ + i | ビルド後instruments起動 |
| ⌘ + shift + b | 静的解析 |

## その他要調査

### よくある問題点

* **コード、ドキュメントのバージョン管理**

* **テストが手動**

* **コードレビュがない（コーディング規約がないゆえに）**

* **コーディング規約がない**

* **レビュー指摘をコメントできない**

* **レビュー単位が大きすぎてレビュに時間かかる**
→ Gitじゃなくても細かくタスク切ればよい

* **テスト仕様書がない**

* **テストコードがない**

* **テストが自動化されていない**

* **テストコードを書く時間が確保されていない**

* **テストコードの自動生成**



* 作業管理
→ Excelもしくはスプレッドシートイナズマ線ガントチャートで良いと思う（それを何で管理するか？）
[gitにExcelファイルあげちゃった。](http://gendosu.jp/archives/2786)

### 管理方法（SVN→Git）

* [SVNからgitへの移行](http://qiita.com/youcune/items/143e46aa1ee079f5a57c)

* 移行による恩恵
	* ブランチ活用（リリース用ブランチ、機能テスト用ブランチ、 etc.）
* 移行する場合に気にすること
	* SVN履歴の引継
	* フロー（移行前、移行期間、移行後）
	* Gitlab構築
	・ソースコメント


### ドキュメント管理

*

### テスト

* [設計書をSphinx, Git, SourceTreeで管理する](http://bacchus.ivory.ne.jp/vodka/doc/sphinx-git.html)
* [テスト手法勉強会](https://blog.yohei.org/ios-android-mobile-testing/)
* [アプリ開発効率化の鍵は「テストの自動化」](http://careerhack.en-japan.com/report/detail/547)

