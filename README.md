# Idiomatic Japanese and Sentence Patterns

## Overview

This repository contains **252 idiomatic expressions and sentence patterns** for learners of Japanese.  
Each expression appears both in **fill-in-the-blank Japanese** and **English translation**, stored in JSON format and accompanied by printable PDFs and LaTeX source files.

The materials were originally prepared for the Tokyo Tech edX MOOC *“Idiom Expressions in Japanese.”*

---

## Directory Structure
```
.
├── booklets/ # Complete booklet-style PDFs (3 volumes)
│ ├── IdiomaticJapaneseV01.pdf
│ ├── IdiomaticJapaneseV02.pdf
│ └── IdiomaticJapaneseV03.pdf
├── db/ # Core data (database and JSON)
│ ├── editing.txt
│ ├── idiom.db
│ └── idiom.json
├── tasksheet/ # Practice sheets (10 idioms per PDF)
│ ├── idiom001-010.pdf
│ ├── idiom011-020.pdf
│ ├── ...
│ └── idiom241-250.pdf
└── tex/ # LaTeX sources and related figures
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

## Data Format (`db/idiom.json`)

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
## Educational Purpose

The goal is to help learners acquire naturally used expressions in authentic contexts.
The dataset emphasizes real-world usage rather than grammatical completeness.

> Even if a form is grammatically correct, there are expressions that are not actually used.
> The key is to learn what is truly said — and to try saying it yourself.
(Excerpt from Preface)

## Related Projects

- LEAP:Language Education Assessment Platform
- AEAD: An Expression A Day corpus
- PGM: Process Grammar Model

## License

© 2025 Hilofumi Yamamoto
Released under the Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0) license.
Non-commercial educational and research use is encouraged.

## Author
Hilofumi Yamamoto 
Institute for Liberal Arts, Institute of Science Tokyo 

## Citation

    Yamamoto, Hilofumi. Idiomatic Japanese and Sentence Patterns (v2.0).
    Tokyo Tech / Institute of Science Tokyo, 2025.
    JSON dataset. Available at: https://github.com/yamagen/idiom
