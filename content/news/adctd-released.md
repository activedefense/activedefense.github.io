---
title: "Cyber Tactical Database v2 Released"
date: 2018-10-31T00:00:00+09:00
draft: false
categories:
  - "NEWS"
  - "Solution"
tags:
  - "Threat Intelligence"
---
# 概要
日本への脅威にフォーカスした脅威情報の配信サービスのアップデートをお知らせします。
AD-CTD(Cyber Tactical Database）は弊社独自のサイバー攻撃観測と自動解析を用い、マルウェアの配信元を継続的に監視しており、1時間おきに日本国内からの到達可能性やドメイン・IP情報を更新し配信しております。
JSON形式でのご提供になりますが、既にご要望頂いているMISPフィード対応についても順次進めて参ります。

# 紹介資料
<script async class="speakerdeck-embed" data-id="3e7395f87e484ec299442fc21682eb73" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>
# API仕様、ドキュメント
- ドキュメント: https://www.activedefense.co.jp/adctd-api-spec/
- Swagger定義(2.0準拠): https://github.com/activedefense/adctd-api-spec/
※ [swagger-codegen][1]を用いると、Swagger定義を元に、各種プログラミング言語のAPIクライアントを自動生成できます。

# 試用期間について
1ヶ月の試用期間を設けております。お気軽にご連絡ください。

# ライセンスについて
本サービスは3つライセンスの形態がございます。
- 二次配信不可ライセンス（No redistribution License)
  - 価格: 月額35万円（税抜）
  - ご契約組織内及びご契約組織が利用するサービス・プロダクトでのご利用のみを許可
- 二次配信可能ライセンス（redistribution License）
  - 費用：ご相談
  - 利用・再配信について制限無し
- コミュニティライセンス（Community License)
  - 費用：なし
  - 本サービスの脅威識別に利用しているOSSのコントリビュータは、本サービスを1年間単位で無償でご利用可能です。

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