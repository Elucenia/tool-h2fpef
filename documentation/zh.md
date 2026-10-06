<!-- ELUCENIA technical documentation · h2fpef · zh · no clinical/professional/rights approval -->

# H₂FPEF 评分

[条件、来源与许可](https://elucenia.org/zh/tools/h2fpef)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### H — 肥胖：BMI \> 30 kg/m²（2）

`obesidade`

### H — 高血压：使用 2 种或更多降压药（1）

`anti`

### F — 阵发性或持续性房颤（3）

`fa`

### P — 肺动脉：超声估测肺动脉收缩压 \> 35 mmHg（1）

`hp`

### E — 年龄 \> 60 岁（1）

`idade`

### F — 充盈：超声 E/e' \> 9（1）

`ee`

## 方法版本

H2FPEF/Reddy 2018：6项因素，0–9；BMI 2分/房颤3分

## 已记录的公式

肥胖（BMI\>30）=2 · ≥2种降压药=1 · 房颤=3 · 肺动脉收缩压\>35 mmHg=1 · 年龄\>60=1 · E/e'\>9=1。总计0至9。

## 限制与适用人群

H2FPEF在因不明原因呼吸困难转诊接受运动侵入性血流动力学评估者中开发，比较射血分数保留型心力衰竭（HFpEF）与非心脏病因。评分有助于决定进一步检查；本身不能确诊HFpEF，也不能自动推广到所有呼吸困难病因。人群、射血分数和超声心动图定义须与方法一致。

## 参考文献

- [Reddy YNV et al. A simple, evidence-based approach to help guide diagnosis of heart failure with preserved ejection fraction. Circulation, 2018.](https://doi.org/10.1161/CIRCULATIONAHA.118.034646)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

HFpEF低概率（0至1）

调查呼吸困难的非心脏原因。


### 2

中等概率（2至5）

辅以负荷超声心动图（舒张功能）或运动导管检查；利钠肽有帮助。


### 3

中等概率（2至5）

辅以负荷超声心动图（舒张功能）或运动导管检查；利钠肽有帮助。


### 4

HFpEF高概率（6至9）

HFpEF可能：治疗并调查特定病因（淀粉样变性、肥厚型心肌病）。

