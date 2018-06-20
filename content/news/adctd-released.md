---
title: "Cyber Tactical Database Released"
date: 2018-06-20T22:13:23+09:00
draft: false
categories:
  - "NEWS"
  - "Solution"
tags:
  - "Threat Intelligence"
---
# 概要
日本への脅威にフォーカスした脅威情報の配信サービスの提供を開始します。
弊社独自のマルウェア配信プラットフォーム観測と自動解析を用い、マルウェアの配信元を継続的に監視しており、1時間おきに日本国内からの到達可能性やドメイン・IP情報を更新し配信しております。
JSON形式でのご提供になりますが、既にご要望頂いているTAXII/STIX2.0対応についても順次進めて参ります。

# API仕様、ドキュメント
- ドキュメント: https://www.activedefense.co.jp/adctd-api-spec/
- Swagger定義(2.0準拠): https://github.com/activedefense/adctd-api-spec/
※ [swagger-codegen][1]を用いると、Swagger定義を元に、各種プログラミング言語のAPIクライアントを自動生成できます。

# 試用期間について
現在は試験公開中であり、7/31までは無料でお使い頂けます。
通常、1ヶ月の試用期間を設けております。

# ライセンスについて
本サービスは2つライセンスの形態がございます。
- 二次配信不可ライセンス（月額税抜35万円）
  - ご契約者様の組織内及びサービス・プロダクトでのご利用のみを許可
    ※本サービスで得た情報を、自社で得た扱いにして再配信することはお止めください、という意味です。

- 二次配信可能ライセンス（月額税抜70万円）
  - 制限無し

# Trial
1ヶ月間、無料でお試し頂けます。APIキーを弊社から発行致します。
タイトルに"CTDテスト利用申込"、本文に下記の情報を沿えて、ctd-info &#064; activedefense.co.jpお送りください。
- ご連絡先氏名
- ご連絡先メールアドレス
- ご所属
- ご希望ライセンス

サービス自体や使い方に関するご質問は、ctd-info &#064; activedefense.co.jpまでお問い合わせください。

[1]: https://github.com/swagger-api/swagger-codegen
[2]: https://www.activedefense.co.jp/adctd-api-spec/
[3]: https://github.com/activedefense/adctd-api-spec/