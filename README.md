# Mocchii Bakery

# ディレクトリ構造

public 配下

```
.
├── 404.html
├── index.html
├── site.webmanifest
├── style.css
├── images
│
├── common //共通ファイル
│   ├── css
│   │   ├── common.css //全html共通
│   │   └── type-scale.css //流体タイポグラフィ
│   └── images
│  
├── concept //コンセプトページ
│   ├── images
│   ├── concept.css
│   └── index.html
│
├── info //店舗情報ページ
│   ├── images
│   ├── index.html
│   └── info.css
│
├── menu //メニューページ
│   ├── images
│   ├── index.html
│   └── menu.css
│
└── news //お知らせページ
    ├── detail
    │   ├── 2025 //年度別に分類
    │   │   ├── 09-14
    │   │   │   └── index.html
    │   │   ├── 09-25
    │   │   │   └── index.html
    │   │   └── 10-07
    │   │       └── index.html
    │   └── detail.css
    ├── images
    ├── index.html
    └── news.css

```

# 命名規則

[BEM の命名規則](https://en.bem.info/methodology/naming-convention/)をベースに視認性を考慮し以下の規則にする

- 単語間：Lower camel case
- `block`と`element` 間：アンダースコア 2 つ「\_\_」
- `modifier`前:はハイフン 2 つ「--」

```
blockName__elementName--modifierName
```
