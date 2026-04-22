# Noctis Light Plus

`Noctis Light Plus` は、Noctis 系を参考にした Light テーマを追加する VS Code 用カラーテーマ拡張です。ローカルでの試用と調整を目的として、次の 7 テーマを収録しています。

- `Noctis Rose`
- `Noctis Verdant`
- `Noctis Amber`
- `Noctis Slate`
- `Noctis Coral`
- `Noctis Teal`
- `Noctis Copper`

既存の Noctis ファミリーが持つ配色バランスや役割分担を踏まえつつ、色相ごとに UI 印象を変えた新しい Light バリアントとして再構成しています。

## 収録テーマ

### Noctis Rose

やわらかいローズトーンを基調にした Light テーマです。UI アクセントを赤みのあるピンク寄りに寄せつつ、背景は明るく落ち着いたトーンに保っています。

### Noctis Verdant

みずみずしいグリーントーンを基調にした Light テーマです。緑系アクセントを持たせつつ、Noctis らしい視認性とコントラストを維持しています。

### Noctis Amber

黄土から琥珀寄りのアクセントを使った Light テーマです。暖かさはありつつも、警告色に寄りすぎない落ち着いたアンバーにまとめています。

### Noctis Slate

青灰寄りの低刺激な Light テーマです。長時間利用でも疲れにくい、実用重視の落ち着いた配色を狙っています。

### Noctis Coral

サーモンからコーラル寄りの Light テーマです。`Noctis Rose` より少しオレンジ方向に寄せて、より軽やかな暖色アクセントにしています。

### Noctis Teal

青緑寄りの Light テーマです。`Noctis Verdant` より青みを強め、爽やかで情報色に寄った印象に整えています。

### Noctis Copper

銅色からセピア寄りの Light テーマです。暖色系でありながら落ち着いたトーンに抑え、クラシックな読みやすさを重視しています。

## ローカルでの確認方法

1. このフォルダを VS Code で開きます。
2. `F5` を押して Extension Development Host を起動します。
3. 新しく開いたウィンドウで `Preferences: Color Theme` を実行します。
4. 7 種の `Noctis` テーマから確認したいものを選択します。

## VSIX の作成

```bash
vsce package
```

上記を実行すると、このフォルダ内に `.vsix` が生成されます。通常利用している VS Code に入れる場合は次を実行します。

```bash
code --install-extension noctis-light-plus-0.2.0.vsix
```

## 補足

- この拡張はローカル利用と試作用を前提にしています。
- デザインは Liviu Schera 氏の Noctis テーマファミリーを参考にしています。
- Noctis は MIT ライセンスで配布されています。
