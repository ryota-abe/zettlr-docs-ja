# 5分で分かるZettlr

アプリケーションのダウンロードとインストールは済みましたね。時計を用意して時間を計る準備はできましたか？それでは、5分間スタート！

## 1. ディレクトリとファイルを開く

ディレクトリやファイルを開きたい場合は、アプリケーションのウィンドウに対してドラッグ＆ドロップすれば、自動的に開かれます。また、`Cmd/Ctrl+O`を押下することでディレクトリを選択するダイアログを開くことができます。

![open.png](img/open.png)

## 2. ファイルやディレクトリを作成する

ディレクトリを開いたら、次はファイルが必要です。`Cmd/Ctrl+N`を押下すると新規ファイルを作成します。ファイル名を入力し、`Return`を押下して、エディタを選択します。ディレクトリを追加したいなら`Cmd/Ctrl+Shift+N`を押下すれば作成できます。

![create.png](img/create.png)

> Markdownファイルだけではありません。拡張子を付けなければ、Zettlrが`.md`を追加してくれます。しかし、拡張子を自分で入力すれば、`.txt`ファイルや`.tex`ファイルも作成することができます。

## 3. 書く

書くことについては、あなた次第です。しかし、これらの重要なキー操作を覚えておきましょう：

- `Cmd/Ctrl+I`: \__斜体_\_にします。Wordと同じように動作します。
- `Cmd/Ctrl+B`: \*\***太字**\*\*にします。こちらも、Wordと同じように動作します。
- `Cmd+Alt+R` (macOS) `Ctrl+Alt+F` (Windows/Linux): 脚注を作成します。
- `Alt/Ctrl+Click` (脚注の参照の上で): 脚注を編集します。`Shift+Enter`で編集を終了します。
- `Cmd/Ctrl+K`: リンクを挿入します。(`Alt/Ctrl+クリック`でリンクを開きます)
- `Cmd/Ctrl+J`: 集中モードに切り替えます。
- `Cmd/Ctrl+Alt+L`: テーマをlightとdarkの間で切り替えます。

![markdown.png](img/markdown.png)

キー操作以外だと、次の点も重要です。

- `#`記号で見出しを作成します。`#`の文字の数が見出しレベルとなります。最大は6個です。
- `>`記号で引用を作成します。`> >`のように複数重ねることで、入れ子にすることもできます。
- `#`記号の直後に半角空白を**入れない**ことで、タグを作成することができます。タグは検索やナビゲーションに使用することができます。

## 4. 他には？

サイドバーをデフォルトのthinモードで使用している場合、ファイル一覧かディレクトリツリーのどちらかが表示されます。ファイル一覧の左上にマウスカーソルを持っていくとディレクトリツリーを表示するための矢印が表示されます。ファイル一覧とディレクトリツリーの切り替えは、`Cmd/Ctrl+!`で行うこともできます。両方とも表示した状態にしたい場合は、設定から、サイドバーのextendedモードを選択してください。

![back.png](img/back.png)

Zettlrは厳密にコンテキストに基づいた動作をします。特に指定しない限り、新規ファイルやディレクトリは、現在選択しているディレクトリ内に作成されます。ファイルの操作(名前変更や削除)は現在選択しているファイルを対象に実行されます。ファイルやディレクトリを指定して操作を行いたい場合は、ファイルやディレクトリを右クリックして表示されるコンテキストメニューを使用してください。

3つのシンプルな経験則:

1. `Alt`キーは、同じ要素に対して、代替の(Alternative)動作を引き起こします。
2. `Shift`キーは、ある動作を作用させる対象をシフト(Shift)します。多くの場合、ディレクトリの代わりにファイルに対して動作を行います。
3. 重要な機能はすべてツールバーに配置されています。左側が汎用的なアクション、真ん中がファイルに対するアクション、右側がその他のアクションです。

## 5. よし、書き終わった。ファイルを共有する方法は？

簡単な3ステップです:

1. PandocとLaTeX(PDFの場合に必要)がインストールされていることを確認してください。
2. ツールバーの共有ボタンをクリックして(もしくは`Cmd/Ctrl+E`を押下して)対象の形式を選んでください。レンズ絞りのアイコンを選択すると、reveal.jsによるプレゼンテーションを表示します。
3. エクスポート時に、Zettlrはエクスポートされたファイルを自動的に開きます。その中で`Cmd/Ctrl+Shift+S`を押下して(ほとんどのアプリケーションで有効なはずです)、好きな場所に保存してください。

![export.png](img/export.png)

## 6. オーケー、5分経ったけど他に何かある？

いいえ。もう行ってもいいですよ。もし、もっと深く知りたければ、以下のガイドをチェックしてください:

- [Zettlrをノート取りアプリケーションとして使う](guides/guide-notes.md)
- [ZettlrをZettelkastenシステムとして使う](guides/guide-zettelkasten.md)
- [Zettlrをフル機能IDEとして使う](guides/guide-ide.md)