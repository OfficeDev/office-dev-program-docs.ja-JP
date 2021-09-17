---
title: 開発者サブスクリプションを使用して Microsoft 365 ソリューションを構築する
description: Microsoft 365 開発者向けサブスクリプションを使用して、ソリューションを構築します。
ms.localizationpriority: high
ms.openlocfilehash: 4fc14896d3e0833f102cabc3152fb1e3a7884843
ms.sourcegitcommit: aadd59458002b5ffcb857e92eb46c92669587d78
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/16/2021
ms.locfileid: "59396677"
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

Office アドインのプラットフォームを使用すると、Office アプリケーションを拡張し、Office ドキュメント内のコンテンツと対話するソリューションを構築できます。Office アドインで、HTML、CSS、および JavaScript などの一般的な Web テクノロジを使用し、Word、Excel、PowerPoint、OneNote、Project、および Outlook を拡張して対話操作することができます。Office for Windows、Office Online、Office for Mac、および Office for iPad を含む複数のプラットフォームにわたって Office ソリューションを実行できます。

開発環境をセットアップしてアドインを作成し始めるには、[Office アドイン クイック スタート](/office/dev/add-ins/)を参照してください。

## <a name="sharepoint-framework"></a>SharePoint Framework

SharePoint Framework (SPFx) は、クライアント側の SharePoint の開発、SharePoint データとの容易な統合、およびオープンソース ツーリングのサポートをすべてサポートするページと Web パーツ モデルです。SharePoint Framework では、優先開発環境内で最新の Web テクノロジとツールを使用し、利用初日から生産性の高い体験と、すばやい反応でモバイル対応のアプリを構築することができます。SharePoint Framework は、SharePoint のオンプレミスおよび SharePoint のオンライン用に機能します。

さまざまな SharePoint のテンプレートとシナリオを試すようにサンドボックスを自動的に構成するには、SharePoint サンプル データ パックをインストールします。詳細については、以下を参照してください。

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

Power Apps は、Microsoft 365 E5 開発者向けサブスクリプション ライセンスに含まれています。 

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