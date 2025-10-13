# 日本語のイディオムと文型（Idiomatic Japanese and Sentence Patterns）

## 概要

本リポジトリには、日本語学習者向けの **イディオム・文型表現 252項目** が収録されています。  
各項目は **日本語の穴埋め文** と **英語訳** を含む JSON 形式で保存され、印刷用 PDF や LaTeX ソースも併せて公開しています。

もともとは東京工業大学 edX講座「日本語のイディオムと表現」用に作成された教材を基礎としています。

---

## ディレクトリ構成
```
.
├── booklets/ # 冊子形式の完成版PDF（3巻）
│ ├── IdiomaticJapaneseV01.pdf
│ ├── IdiomaticJapaneseV02.pdf
│ └── IdiomaticJapaneseV03.pdf
├── db/ # 基本データ（データベースとJSON）
│ ├── editing.txt
│ ├── idiom.db
│ └── idiom.json
├── tasksheet/ # 練習用シート（10項目ごと）
│ ├── idiom001-010.pdf
│ ├── idiom011-020.pdf
│ ├── ...
│ └── idiom241-250.pdf
└── tex/ # LaTeX ソースと画像類
├── IdiomaticJapaneseV01.tex
├── IdiomaticJapaneseV02.tex
├── IdiomaticJapaneseV03.tex
├── idiom_english.tex
├── idiom_compact.pdf
├── Cc-by-sa.svg
├── bicycle201801.pdf
├── William-Bouguereau.jpg
└── ...
```

---

## `db/idiom.json` の形式

```json
{
  "id": 1,
  "expression-ja": "(傘:かさ)を(持:も)って(来:こ)ない(日:ひ)に(a)(雨:あめ)が(降:ふ)るから、(天気予報:てんきよほう)はまるで(b)。",
  "expression-en": "It only rains when you don't have an umbrella with you, so you can never count on the weather forecast.",
  "answers": {
    "a": ["(限:かぎ)って"],
    "b": [
      "(当:あ)てにならない",
      "(当:あ)てにできない",
      "(当:あ)てにはならない",
      "(当:あ)てにはできない"
    ]
  }
}
```


## 教材の目的

この教材は、実際によく使われる自然な日本語表現を文脈の中で学ぶことを目的としています。
文法規則の網羅よりも、使われ方・場面・自然さを重視しています。

>   文法的であっても、意味によって使われない形もある。
>   どれが使われるのかを見て、自分で使ってみることが大切である。
> （「はじめに」より）

## 関連プロジェクト
- LEAP 言語教育評価プラットフォーム
- AEAD 一日一表現プロジェクト
- PGM プロセス文法モデル研究

## ライセンス

© 2025 山元 啓史 (Hilofumi Yamamoto)
本データセットは Creative Commons BY-NC 4.0 国際ライセンス に基づいて公開されています。
教育・研究目的での非商用利用を歓迎します。

## 作者

山元 啓史 (Hilofumi Yamamoto)
東京科学大学（旧 東京工業大学）リベラルアーツ研究教育院教授

## 引用

>    山元 啓史『日本語のイディオムと文型 (v2.0)』
>    東京科学大学, 2025年. JSONデータセット.
>    https://github.com/yamagen/idiom

