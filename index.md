---
title: 実験トップ
val1:
  val2: MyVal2
---

# Jekyll 実験

これは **Markdown** で書いています。

| 部品 | 数量 |
|---|---|
| 抵抗 4.7k | 1 |
| スピーカー | 1 |


- サイト名: {{ site.title }} / 作者: {{ site.author }}
- タイトル: {{ page.title }}
- 日時: {{ site.time | date: "%Y/%m/%d %H:%M" }}
- val: {{ page.val1.val2 }}


