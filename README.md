# README
# Name

 「suzulink」
 組合活動をより充実したものするためのWebサービス
 組合員は課題の早期発見、組合役員は選択と集中、会社は優秀な人材の発掘が可能となる

# Problem

  組合分会長はどのような活動して良いか、判断に迷い、取組そのものを行わないことが多い
  組合役員は、組合員全員に共通した取組が中心となり、本当に困っている組合員の声を広いあげれていない
  会社は、優秀な人材を選択しているつもりで、実際は部下からの評価が悪い場合がある
  これらの問題を解決する

# 要件定義

|機能                      |目的  |詳細        |ストーリー|
|-------------------------|------|-----------|--------|
|ユーザー新規登録機能         |ユーザーを登録するため|ニックネーム、メールアドレス、パスワード、所属支店を登録する|・ニックネーム、メールアドレス、パスワードは手入力
・所属支店はプルダウンで選択|
|email                  |string|null: false|
|encrypted_password     |string|null: false|
|last_name              |string|null: false|
|first_name             |string|null: false|
|last_name_kana         |string|null: false|
|first_name_kana        |string|null: false|
|birthday               |date  |null: false|
  