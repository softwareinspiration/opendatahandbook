---
section: terms
lang: ja
title: 非識別化
---

de-identification。[匿名化](../anonymisation/)の一種で、パーソナルデータベースのレコードは保持したまま、氏名等の特定の識別情報を、匿名化された[識別子](../identifier/)に置き換えること。集成（アグリゲーション）と比べると、非識別化の方が[データ漏洩](../data-leakage/)のリスクが高い。たとえば、刑務所の記録が受刑者の犯罪記録と治療歴を含む場合、その治療歴に不正にアクセスすると多くの場合氏名が無くても受刑者の犯罪記録で個人を特定可能だ。他のケースではこのリスクは存在しないか、あるいは収集されていないデータの価値がとても大きいので、注意深く設計された安全措置に従って非識別化されたデータを作るのは有意義である。