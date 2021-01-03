---
title: セルオートマトンを用いた腹膜癒着防止材の数理的設計

event: 第43回ケモインフォマティクス討論会
event_url: http://www-dsc.naist.jp/chemoinfo2020/

location: オンライン開催
address:
  street: ''
  city: ''
  region: ''
  postcode: ''
  country: ''

summary: ''
abstract: グラフデータを拡張する手法について, この時点までで得られた結果をケモインフォマティクス討論会にて報告した.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-12-09"
date_end: ""
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: ""

authors: ["井上 貴央*", "田中 健一", "船津 公人"]
tags: ["定量的構造物性相関", "データ拡張", "グラフデータ", "グラフニューラルネットワーク", "少量データ"]

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
url_pdf: https://www.jstage.jst.go.jp/article/ciqs/2020/0/2020_1A12/_pdf/-char/ja
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

創薬や材料開発では, 所望の性質を持つ新規有機分子の効率的な探索手法が求められている. 定量的構造物性相関モデルとしてグラフニューラルネットワーク (GNN) と呼ばれる深層モデルを用いることで, 既存の特徴抽出手法を用いるよりも良い予測性能で, 候補構造のバーチャルスクリーニングができる. しかし, 先行研究では学習に多量の化学構造データを利用しており, 興味のある構造・物性データが多量に集まりにくい分子設計の現場では, 十分な予測性能が得られない可能性がある. 本研究では, Message Passing Neural Network (MPNN) と呼ばれるGNNモデルの中で特徴ベクトルに摂動を加えることでグラフデータの拡張を行うPerturbating MPNN (PMPNN) を設計した. QM9データセットでMPNNとの比較を行い, 提案手法の有効性を検証し, 予測に対する摂動の効果を考察した. また, データ拡張により約半数のデータセットでも元と同等の予測性能が得られ, 少量のグラフデータでもうまく特徴抽出できると示唆された.
