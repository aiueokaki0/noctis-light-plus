# VS Code 拡張クイックスタート

[English](./vsc-extension-quickstart.md) | 日本語

## フォルダ構成

- このフォルダには、カラーテーマ拡張に必要なファイル一式が入っています。
- `package.json`
  拡張マニフェストです。テーマ名やテーマファイルの場所を定義しています。
- `themes/noctis-rose-color-theme.json`
  `Noctis Rose` のテーマ定義ファイルです。
- `themes/noctis-verdant-color-theme.json`
  `Noctis Verdant` のテーマ定義ファイルです。
- `themes/noctis-amber-color-theme.json`
  `Noctis Amber` のテーマ定義ファイルです。
- `themes/noctis-slate-color-theme.json`
  `Noctis Slate` のテーマ定義ファイルです。
- `themes/noctis-coral-color-theme.json`
  `Noctis Coral` のテーマ定義ファイルです。
- `themes/noctis-teal-color-theme.json`
  `Noctis Teal` のテーマ定義ファイルです。
- `themes/noctis-copper-color-theme.json`
  `Noctis Copper` のテーマ定義ファイルです。

## すぐに試す

- `F5` を押すと、この拡張を読み込んだ Extension Development Host が起動します。
- 起動したウィンドウで `Preferences: Color Theme` を実行し、7 種の `Noctis` テーマから確認したいものを選択します。
- 言語ファイルを開くと、文法定義に応じてトークンにスコープが割り当てられます。
- スコープを確認したいときは、コマンドパレットから `Developer: Inspect Editor Tokens and Scopes` を実行します。

## 変更を反映する

- テーマ JSON を編集したら、Extension Development Host 上で見え方を確認しながら調整できます。

## テーマ調整の考え方

- シンタックスハイライトは TextMate スコープをベースに行われます。
- `colors` では UI 配色を、`tokenColors` ではコードの配色を調整します。

詳しくは VS Code の [Color Theme 拡張ガイド](https://code.visualstudio.com/api/extension-guides/color-theme) を参照してください。

## 拡張のインストール

- ローカルで使う場合は `vsce package` で `.vsix` を作成し、`code --install-extension <vsixファイル>` でインストールできます。
- 将来的に公開する場合は、VS Code 拡張の標準的な公開手順に従ってください。
