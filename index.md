---
title: オンラインでホストされる手順
permalink: index.html
layout: home
---

# MS-4008: エグゼクティブ向け Microsoft 365 Copilot の対話型エクスペリエンス 

## コンテンツ ディレクトリ

このコースのデモは、アクセラレータ キットのデモ [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG) に基づいています。

このトレーニングを実施する前に、デモについて理解しておくことが重要です。 いくつかのラボでは、サンプル ドキュメントと事前に作成された Teams 会議およびメールを利用します。

- [こちら](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/tree/master/ResourceFiles)のサンプル ドキュメントをすべて事前にダウンロードします。
- [こちら](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG)の手順に従って、Teams 会議とメール スレッドをセットアップします。
- 次の対話型エクスペリエンスの内容をよく理解してください。
    - オプション 1: [aka.ms/CopilotEE](https://aka.ms/CopilotEE)
    - オプション 2: [aka.ms/TeamsEE](https://aka.ms/TeamsEE)

    > **注:** 参加者が Microsoft 365 Copilot ライセンスを持っていない場合は、[aka.ms/CopilotWebEE](https://aka.ms/CopilotWebEE) にあるこのエクスペリエンスの無料商用バージョンを利用できます。

## コースの説明

Microsoft 365 Copilot が職場の生産性とイノベーションをどのように向上させるかについて確認します。 このエクスペリエンスは、現代のビジネス リーダー向けに調整されており、Copilot に対するコンテキスト プロンプトの作成についての知見を提供し、毎日のワークフローへのシームレスな統合を紹介する魅力的なユース ケース演習を含んでいます。

この配信の主な目的は、次のとおりです。

- 参加者に Microsoft 365 Copilot を紹介し、効果的なプロンプトを作成する方法を教える
- Office アプリで Microsoft 365 Copilot のデモをする (最大 3 つのデモ)
- 対話型エクスペリエンスを通じて参加者をガイドする
- 参加者に Microsoft Copilot for Mobile をダウンロードして試すように勧める

## コース スケジュール (推定) 

| # | トピック                                 | 合計時間      |
|---|---------------------------------------|-----------------|
| 1 | Microsoft 365 Copilot の概要 | 10 分    |
| 2 | 効果的なプロンプトを作成するためのエグゼクティブ向けガイド | 30 分      |
| 3 | Microsoft 365 Copilot の対話型エクスペリエンス  | 20 分      |
|   |                                       | **合計時間 60 分** |


各デモへのハイパーリンクを以下に示します。

## デモ

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
