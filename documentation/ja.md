<!-- ELUCENIA technical documentation · h2fpef · ja · no clinical/professional/rights approval -->

# H₂FPEFスコア

[条件・出典・許諾](https://elucenia.org/ja/tools/h2fpef)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### H — 肥満：BMI \> 30 kg/m²（2）

`obesidade`

### H — 高血圧：降圧薬2剤以上（1）

`anti`

### F — 発作性または持続性心房細動（3）

`fa`

### P — 肺動脈：心エコーの肺動脈収縮期圧 \> 35 mmHg（1）

`hp`

### E — 年齢 \> 60歳（1）

`idade`

### F — 充満：心エコーのE/e' \> 9（1）

`ee`

## 方法の版

H2FPEF/Reddy 2018：6因子，0–9；BMI 2点/心房細動3点

## 記載された計算式

肥満（BMI\>30）=2 · ≥2種類の降圧薬=1 · 心房細動=3 · 肺動脈収縮期圧\>35 mmHg=1 · 年齢\>60=1 · E/e'\>9=1。合計0～9。

## 限界・対象集団

H2FPEFは、原因不明の呼吸困難で運動時の侵襲的血行動態評価に紹介された人を対象に、駆出率が保たれた心不全（HFpEF）と非心臓性の原因を比較して開発されました。スコアは追加検査の判断を助けますが、単独でHFpEFを確定するものではなく、あらゆる呼吸困難の原因へ自動的に外挿してはいけません。集団、駆出率、心エコーの定義は、この方法に対応する必要があります。

## 参考文献

- [Reddy YNV et al. A simple, evidence-based approach to help guide diagnosis of heart failure with preserved ejection fraction. Circulation, 2018.](https://doi.org/10.1161/CIRCULATIONAHA.118.034646)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
