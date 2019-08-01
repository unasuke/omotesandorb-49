# OpenAPI 3 によるスキーマラスト開発
subtitle
: 2019-08-01

subtitle
: 表参道.rb #49

author
: うなすけ

theme
: unasuke-white


# 自己紹介
- 名前 : うなすけ
- 仕事 : 株式会社バンク (エンジニア)
  - インフラ寄りサーバーサイドエンジニア
  - Ruby, Rails, Kubernetes...

- {::tag name="x-small"}GitHub [@unasuke](https://github.com/unasuke){:/tag}
- {::tag name="x-small"}Mastodon [@unasuke@mstdn.unasuke.com](https://mstdn.unasuke.com/@unasuke){:/tag}
- {::tag name="x-small"}Twitter [@yu\_suke1994](https://twitter.com/yu_suke1994){:/tag}

![](img/icon_raw.jpg){:relative_width="24" align="right" relative_margin_right="-10" relative_margin_top="42"}

# OpenAPI 3
![](https://www.openapis.org/wp-content/uploads/sites/3/2018/02/OpenAPI_Logo_Pantone-1.png){:relative_width="90"}

<https://www.openapis.org/>

- YAMLやJSONで REST APIの仕様を記述するやつ
- Swaggerとか聞いたことある人多いんでは

# OpenAPI 3
- スキーマファースト開発で使われる
  - serverとclientがAPIのschemaを定義してから開発
    - 手戻りが少ない
    - documentができる
- [スキーマファースト開発のススメ - onk.ninja](https://blog.onk.ninja/2017/09/21/schema_first_development)

# 現実世界には様々なことがある
- 途中からOpenAPIを導入したい
 - 大量の定義を書かねばならぬ
  - タスクがパンク
    - 終了
