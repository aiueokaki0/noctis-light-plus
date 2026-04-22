# VS Code 拡張クイックスタート

## フォルダ構成

- このフォルダには、カラーテーマ拡張に必要なファイル一式が入っています。
- `package.json`
  拡張マニフェストです。テーマ名やテーマファイルの場所を定義しています。
- `themes/noctis-rose-color-theme.json`
  `Noctis Rose` のテーマ定義ファイルです。
- `themes/noctis-verdant-color-theme.json`
  `Noctis Verdant` のテーマ定義ファイルです。

## すぐに試す

- `F5` を押すと、この拡張を読み込んだ Extension Development Host が起動します。
- 起動したウィンドウで `Preferences: Color Theme` を実行し、テーマを選択します。
- 言語ファイルを開くと、文法定義に応じてトークンにスコープが割り当てられます。
- スコープを確認したいときは、コマンドパレットから `Developer: Inspect Editor Tokens and Scopes` を実行します。

## 変更を反映する

- テーマ JSON を編集すると、Extension Development Host 側に変更が反映されます。

## テーマ調整の考え方

- シンタックスハイライトは TextMate スコープをベースに行われます。
- `colors` では UI 配色を、`tokenColors` ではコードの配色を調整します。

詳しくは VS Code の [Color Theme 拡張ガイド](https://code.visualstudio.com/api/extension-guides/color-theme) を参照してください。

## 拡張のインストール

- ローカルで使う場合は `vsce package` で `.vsix` を作成し、`code --install-extension <vsixファイル>` でインストールできます。
- Marketplace 公開が必要になった場合は、VS Code 拡張の公開手順を別途参照してください。
