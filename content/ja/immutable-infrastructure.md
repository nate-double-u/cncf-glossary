---
title: イミュータブルインフラストラクチャ
status: Completed
category: プロパティ
tags: ["インフラストラクチャ", "プロパティ", ""]
---

イミュータブルインフラストラクチャとは、一度デプロイされると変更することができないコンピューターインフラストラクチャ([仮想マシン](/ja/virtual-machine/)や[コンテナ](/ja/container/)、ネットワーク機器)を指します。
これは許可されていない変更を自動的に上書きするプロセスや、最初から変更を許可しないシステムによって強制されます。
コンテナはイミュータブルインフラストラクチャの良い例です。
なぜならコンテナに永続的な変更を加えるには、新しいバージョンのコンテナを作成するか、イメージから既存のコンテナを再度作成するしかないからです。

許可されていない変更の防止や特定により、イミュータブルインフラストラクチャはセキュリティリスクの特定と軽減を容易にします。
このようなシステムの運用ははるかに簡単になります。
なぜなら、管理者がそれについての前提を立てやすくなるためです。
結局のところ、誰も間違いを犯していないことや、伝え忘れた変更を行っていないことが分かっています。
イミュータブルインフラストラクチャは[Infrastructure as Code](/ja/infrastructure-as-code/)と密接に関連しており、インフラストラクチャを作成するために必要なすべての自動化がバージョン管理(たとえばGit)されています。
この不変性とバージョン管理の組み合わせにより、システムへのすべての許可された変更に対して、耐久性のある監査ログが存在します。
