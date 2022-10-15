---
title: 開発者サブスクリプションを使用して Microsoft 365 ソリューションを構築する
description: Microsoft 365 開発者向けサブスクリプションを使用して、ソリューションを構築します。
ms.localizationpriority: high
ms.openlocfilehash: 2450b0dee53ca7a8bdaf90beea3cb08f9e2dea36
ms.sourcegitcommit: b10b392973a9eb8636ce4f1994c3bdbed000411c
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/13/2022
ms.locfileid: "68570594"
---
# <a name="use-your-developer-subscription-to-build-microsoft-365-solutions"></a>開発者サブスクリプションを使用して Microsoft 365 ソリューションを構築する

Microsoft 365 開発者サブスクリプションでどんなものを構築したいと考えていますか? 何を構築するかに応じて、可能な選択肢がたくさんあります。 最初に利用を検討できるいくつかの製品とテクノロジ分野は、次のとおりです。

## <a name="microsoft-teams"></a>Microsoft Teams

Microsoft Teams は、共同作業向けのアプリやサービスに統合されるチャット ベースのワークスペースです。 自社用のカスタム アプリと、世界中にいるチームのための SaaS アプリケーションのどちらを開発する場合も、Microsoft Teams 開発者プラットフォームなら簡単にサービスを統合できます。

Microsoft Teams をセットアップしてコーディングする方法は次のとおりです。

1. [開発者向けサブスクリプションを準備します](/microsoftteams/platform/get-started/get-started-tenant)。
2. 開発環境をセットアップします。 どんな種類のアプリやサービスを構築するかに応じて、その手順は異なります。 詳細については、以下を参照してください。

  - [Microsoft Teams プラットフォームで Node.js を使い始める](/microsoftteams/platform/get-started/get-started-nodejs-app-studio)
  - [Microsoft Teams プラットフォームで C#/.NET を使い始める](/microsoftteams/platform/get-started/get-started-dotnet-app-studio)

## <a name="microsoft-graph"></a>Microsoft Graph

Microsoft Graph を使用すると、Microsoft クラウド内の数百万人ものユーザーのデータと対話できます。 Microsoft Graph を使用して、豊富なリソース、リレーションシップ、インテリジェンスに接続する、組織やコンシューマー向けのアプリケーションを、すべて 1 つのエンドポイントを介して構築します: `https://graph.microsoft.com`。

Microsoft Graph のシナリオを試しにサンドボックスを自動的に構成するには、ユーザーとメール、イベントのサンプル データ パックをインストールします。

- ユーザー - 各ユーザーの名前および写真を含むライセンスとメールボックスのある 16 人の架空のユーザーをインストールします。 Microsoft Graph API を使用して、次の方法でユーザー サンプル データを操作します。
  - 特定のユーザーの詳細を取得する
  - ユーザーを更新する
  - 直属の部下を取得する
  - 組織図を準備する
  - 部署別にユーザーを取得する
- メールとイベント - 各 16 人のサンプル ユーザーに Outlook メールの会話とカレンダーのイベントを追加します。 Microsoft Graph API を使用して、次の方法でメールとイベント サンプル データを操作します。
  - ユーザーがメールを取得する
  - 日付でフィルター処理されたメールを取得する
  - 今後のイベントを取得する
  - 今後のイベントを更新/削除する

詳細については、「[サンプル データ パック使用する](install-sample-packs.md)」を参照してください。 

Microsoft Graph の使用を死するその他の方法については、[Microsoft Graph アプリを構築し始める](https://developer.microsoft.com/en-us/graph/get-started)、または Microsoft Graph [クイック スタート](https://developer.microsoft.com/en-us/graph/quick-start)を参照してください。

## <a name="office-add-ins"></a>Office アドイン

You can use the Office Add-ins platform to build solutions that extend Office applications and interact with content in Office documents. With Office Add-ins, you can use familiar web technologies such as HTML, CSS, and JavaScript to extend and interact with Word, Excel, PowerPoint, OneNote, Project, and Outlook. Your solution can run in Office across multiple platforms, including Office for Windows, Office Online, Office for the Mac, and Office for the iPad.

開発環境をセットアップしてアドインを作成し始めるには、[Office アドイン クイック スタート](/office/dev/add-ins/)を参照してください。

## <a name="sharepoint-framework"></a>SharePoint Framework

The SharePoint Framework (SPFx) is a page and web part model that provides full support for client-side SharePoint development, easy integration with SharePoint data, and support for open source tooling. With the SharePoint Framework, you can use modern web technologies and tools in your preferred development environment to build productive experiences and apps that are responsive and mobile-ready.

To automatically configure your sandbox to try out different SharePoint templates and scenarios, install the SharePoint sample data pack.
For more details, see:

- [サンプル データ パックのインストール](install-sample-packs.md)
- [SPFx 開発者向けサブスクリプションをセットアップします](/sharepoint/dev/spfx/set-up-your-developer-tenant)
- [開発環境のセットアップ](/sharepoint/dev/spfx/set-up-your-development-environment)

## <a name="sharepoint-add-ins"></a>SharePoint アドイン 

自己完結型の機能パーツである SharePoint アドインは、SharePoint Web サイトの機能を拡張して、明確に定義されたビジネス上の問題を解決します。 2 種類の SharePoint アドイン (SharePoint ホスト型とプロバイダー ホスト型) を作成できます。 詳細については、「[SharePoint アドイン](/sharepoint/dev/sp-add-ins/sharepoint-add-ins)」を参照してください。

SharePoint アドインをセットアップしてコーディングを開始する方法は次のとおりです。

- [サブスクリプションをセットアップします](/sharepoint/dev/spfx/set-up-your-developer-tenant)。  
- 開発環境を次のようにセットアップします。 
  - [SharePoint ホスト型の SharePoint アドインの作成を始める](/sharepoint/dev/sp-add-ins/get-started-creating-sharepoint-hosted-sharepoint-add-ins)  
  - [プロバイダー ホスト型 SharePoint アドインの作成を始める](/sharepoint/dev/sp-add-ins/get-started-creating-provider-hosted-sharepoint-add-ins)  

## <a name="power-apps"></a>Power Apps

Microsoft 365向け Power Apps は、Microsoft 365 E5 開発者向けサブスクリプション ライセンスに含まれています。 [標準コネクタ](/connectors/connector-reference/connector-reference-standard-connectors)を使用して、許可されていないアプリを作成して テストできるということです。 [プレミアム](/connectors/connector-reference/connector-reference-premium-connectors) コネクタ またはカスタム コネクタを使用するには、追加のライセンスが必要です。 開発およびテストの目的で、[開発者プランのPower Apps](https://powerapps.microsoft.com/developerplan)を使用できます。 

Power Apps は、アプリケーション、サービス、コネクタ、データ プラットフォームで構成されるスイートで、ビジネス ニーズに合ったカスタム アプリを構築する迅速なアプリケーション開発環境を提供します。 Power アプリを使用すると、基となるデータ プラットフォーム (Common Data Service) またはさまざまなオンライン / オンプレミスのデータ ソース (SharePoint、Microsoft 365、Dynamics 365、SQL Server など) に保存されているビジネス データに接続する、カスタム ビジネス アプリをすばやく構築できます。

Power Apps を使用して構築されたアプリは、豊富なビジネス ロジックとワークフロー機能を提供し、手動のビジネス プロセスをデジタルで自動化されたプロセスに変換します。 さらに、Power Apps を使用して構築されたアプリは応答性に優れたデザインを備え、ブラウザーまたはモバイル デバイス (携帯電話またはタブレット) でシームレスに実行できます。 Power Apps は、ユーザーがコードを記述することなく、機能豊富なカスタム ビジネス アプリを構築できるようにして、カスタム ビジネス アプリの構築エクスペリエンスを "デモ" します。

また、Power Apps は、開発者がプログラムでデータやメタデータを操作し、ビジネス ロジックを適用し、カスタム コネクタを作成し、外部データと統合できる拡張プラットフォームを提供します。

詳細情報:

- [Power Apps](/powerapps/)
- [Power Apps のデモ](https://powerapps.microsoft.com/demo/) を見る
- YouTube の [ Power Appsのビデオ](https://www.youtube.com/channel/UCGfWR2ekfRFckLjev6eQYLg) を見る


## <a name="see-also"></a>関連項目

- [Microsoft 365 開発者プログラムに参加する](microsoft-365-developer-program.md)
- [Microsoft 365 開発者サブスクリプションを設定する](microsoft-365-developer-program-get-started.md) 
- [期限切れのサブスクリプションを更新する](subscription-expiration-and-renewal.md)
- [Microsoft 365 開発者プログラムの FAQ](microsoft-365-developer-program-faq.yml)
- [Microsoft 365 開発者向けドキュメント](/microsoft-365/developer)
