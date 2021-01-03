---
title: 生成構造の多様化を目指した化学空間探索型構造生成アルゴリズムの改良

event: 第41回ケモインフォマティクス討論会
event_url: https://www.chem.kumamoto-u.ac.jp/~cheminfo2018/

location: 熊本市民会館シアーズホーム夢ホール
address:
  street: ''
  city: 熊本市
  region: 熊本県
  postcode: ''
  country: 日本

summary: ''
abstract: 修士過程時の研究について, この時点までで得られた結果をケモインフォマティクス討論会にて報告した.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2018-10-26"
date_end: "2018-10-27"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: ""

authors: ["井上 貴央*", "田中 健一", "小寺 正明", "船津 公人"]
tags: ["構造生成器", "多様性"]

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: ''
#   focal_point: Right

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/Zephyros225
url_code: ""
url_pdf: https://www.jstage.jst.go.jp/article/ciqs/2018/0/2018_2B11/_pdf/-char/ja
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

---

## Abstract
近年, 機能性有機分子の開発が盛んに行われている. 開発の効率化のための手段として構造生成器が挙げられる. 目的物性を有する構造を生成するために設計された構造生成器DAECSに対し, 本研究では生成構造の多様化に取り組んだ. 構造生成の起点となる構造を生成構造群から選ぶ際に, 範囲の制限とクラスタリングを組み合わせることで, 生成構造群の多様性の向上を目指した. 提案手法を評価するため, ヒスタミンH1受容体に対するリガンド構造の生成を行い, 生成構造の分布と生成構造群の任意の2構造間のTanimoto距離の平均を確認した. 既往手法と比べて提案手法の方が, 生成構造群の分布は散らばっており, 平均Tanimoto距離が大きいため, 提案手法の生成構造群の多様性が示唆された. また, 提案手法の計算効率が良いことを理論的に示した. しかし、ターゲットに近い構造が生成されにくく, 生成構造が初期構造に依存するという課題が見出された.
