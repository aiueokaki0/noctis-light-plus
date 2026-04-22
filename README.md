# Noctis Light Plus

`Noctis Light Plus` は、Noctis 系を参考にした Light テーマを追加する VS Code 用カラーテーマ拡張です。ローカルでの試用と調整を目的として、次の 2 テーマを収録しています。

- `Noctis Rose`
- `Noctis Verdant`

既存の Noctis ファミリーが持つ配色バランスや役割分担を踏まえつつ、ローズ系とグリーン系の新しい Light バリアントとして再構成しています。

## 収録テーマ

### Noctis Rose

やわらかいローズトーンを基調にした Light テーマです。UI アクセントを赤みのあるピンク寄りに寄せつつ、背景は明るく落ち着いたトーンに保っています。

### Noctis Verdant

みずみずしいグリーントーンを基調にした Light テーマです。緑系アクセントを持たせつつ、Noctis らしい視認性とコントラストを維持しています。

## ローカルでの確認方法

1. このフォルダを VS Code で開きます。
2. `F5` を押して Extension Development Host を起動します。
3. 新しく開いたウィンドウで `Preferences: Color Theme` を実行します。
4. `Noctis Rose` または `Noctis Verdant` を選択します。

## VSIX の作成

```bash
vsce package
```

上記を実行すると、このフォルダ内に `.vsix` が生成されます。通常利用している VS Code に入れる場合は次を実行します。

```bash
code --install-extension noctis-light-plus-0.1.0.vsix
```

## 補足

- この拡張はローカル利用と試作用を前提にしています。
- デザインは Liviu Schera 氏の Noctis テーマファミリーを参考にしています。
- Noctis は MIT ライセンスで配布されています。
