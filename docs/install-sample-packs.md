---
title: Microsoft 365 開発者プログラム サブスクリプションでサンプル データ パックを使用する
description: サンドボックス環境を迅速に稼働させるために、開発者サブスクリプションにサンプル データ パックをインストールする方法を説明します。
localization_priority: Priority
ms.openlocfilehash: 3802c1c1e02c7be9ccb322561189ee0d085e8ce0
ms.sourcegitcommit: 3d50606496bd0bdbbcf892d2d18de6343a44c576
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/19/2021
ms.locfileid: "51890154"
---
# <a name="use-sample-data-packs-with-your-microsoft-365-developer-program-subscription"></a><span data-ttu-id="fec89-103">Microsoft 365 開発者プログラム サブスクリプションでサンプル データ パックを使用する</span><span class="sxs-lookup"><span data-stu-id="fec89-103">Use sample data packs with your Microsoft 365 Developer Program subscription</span></span>

<span data-ttu-id="fec89-104">Microsoft 365 開発者プログラム サブスクリプションにサンプル データ パックをインストールすることができます。</span><span class="sxs-lookup"><span data-stu-id="fec89-104">You can install sample data packs on your Microsoft 365 Developer Program subscription.</span></span> <span data-ttu-id="fec89-105">サンプル データ パックは、ソリューションの構築とテストに必要なデータとコンテンツを自動的にインストールするため、時間を節約することができます。</span><span class="sxs-lookup"><span data-stu-id="fec89-105">Sample data packs save you time by automatically installing data and content you need to build and test your solutions.</span></span> <span data-ttu-id="fec89-106">これには、小規模の企業環境をシミュレートするための架空のユーザー、メタデータ、および写真が含まれます。</span><span class="sxs-lookup"><span data-stu-id="fec89-106">This includes fictitious users, metadata, and photos to simulate a small corporate environment.</span></span> <span data-ttu-id="fec89-107">サンプル データをすばやくインストールできるため、サンプル データを自分で作成することに時間を費やすことなく、ソリューションに集中することができます。</span><span class="sxs-lookup"><span data-stu-id="fec89-107">You can quickly install the sample data so that you can focus on your solutions rather than spend time creating sample data yourself.</span></span>

<span data-ttu-id="fec89-108">サンプル データ パックは、サブスクリプション タイルの下部にある [Microsoft 365 開発者プログラム ダッシュボード](https://developer.microsoft.com/office/profile)にあります。</span><span class="sxs-lookup"><span data-stu-id="fec89-108">You can find sample data packs on your [Microsoft 365 Developer Program dashboard](https://developer.microsoft.com/office/profile), at the bottom of your subscription tile.</span></span>

![ダッシュボード ページのサブスクリプション タイルのスクリーンショット](images/sample-data-pack-ux-tile-users-beginning.PNG)

<span data-ttu-id="fec89-110">現在、次のサンプル データ パックをご利用になれます。</span><span class="sxs-lookup"><span data-stu-id="fec89-110">The following sample data packs are currently available:</span></span>

- <span data-ttu-id="fec89-111">ユーザー - 各ユーザーの名前および写真を含むライセンスとメールボックスのある 16 人の架空のユーザーをインストールします。</span><span class="sxs-lookup"><span data-stu-id="fec89-111">Users - Installs 16 fictitious users with licenses, mailboxes, and metadata, including names and photos for each user.</span></span> <span data-ttu-id="fec89-112">Microsoft Graph API を使用して、次の方法でユーザー サンプル データを操作します。</span><span class="sxs-lookup"><span data-stu-id="fec89-112">Use Microsoft Graph APIs to work with user sample data in the following ways:</span></span>
  - <span data-ttu-id="fec89-113">特定のユーザーの詳細を取得する</span><span class="sxs-lookup"><span data-stu-id="fec89-113">Get specific user details</span></span>
  - <span data-ttu-id="fec89-114">ユーザーを更新する</span><span class="sxs-lookup"><span data-stu-id="fec89-114">Update user</span></span>
  - <span data-ttu-id="fec89-115">直属の部下を取得する</span><span class="sxs-lookup"><span data-stu-id="fec89-115">Get direct reports</span></span>
  - <span data-ttu-id="fec89-116">組織図を準備する</span><span class="sxs-lookup"><span data-stu-id="fec89-116">Prepare organization chart</span></span>  
  - <span data-ttu-id="fec89-117">部署別にユーザーを取得する</span><span class="sxs-lookup"><span data-stu-id="fec89-117">Get users by department</span></span>

- <span data-ttu-id="fec89-118">メールとイベント - 各 16 人のサンプル ユーザーに Outlook メールの会話とカレンダーのイベントを追加します。</span><span class="sxs-lookup"><span data-stu-id="fec89-118">Mail and events - Adds Outlook email conversations and calendar events for each of the 16 sample users.</span></span> <span data-ttu-id="fec89-119">Microsoft Graph API を使用して、次の方法でメールとイベント サンプル データを操作します。</span><span class="sxs-lookup"><span data-stu-id="fec89-119">Use Microsoft Graph APIs to work with mail and events sample data in the following ways:</span></span>
  - <span data-ttu-id="fec89-120">ユーザーがメールを取得する</span><span class="sxs-lookup"><span data-stu-id="fec89-120">Get emails by users</span></span>
  - <span data-ttu-id="fec89-121">日付でフィルター処理されたメールを取得する</span><span class="sxs-lookup"><span data-stu-id="fec89-121">Get emails filtered by date</span></span>
  - <span data-ttu-id="fec89-122">今後のイベントを取得する</span><span class="sxs-lookup"><span data-stu-id="fec89-122">Get upcoming events</span></span>
  - <span data-ttu-id="fec89-123">今後のイベントを更新/削除する</span><span class="sxs-lookup"><span data-stu-id="fec89-123">Update/delete upcoming events</span></span>

> [!NOTE]
> <span data-ttu-id="fec89-124">メールとイベントをインストールする前に、ユーザー サンプル データ パックをインストールする必要があります。</span><span class="sxs-lookup"><span data-stu-id="fec89-124">You must install the Users sample data pack before you install Mail and Events.</span></span>

## <a name="what-do-the-sample-data-packs-add-to-my-subscription"></a><span data-ttu-id="fec89-125">サンプル データ パックは、サブスクリプションに何を追加しますか?</span><span class="sxs-lookup"><span data-stu-id="fec89-125">What do the sample data packs add to my subscription?</span></span>

<span data-ttu-id="fec89-126">ユーザー サンプル データ パックは、サブスクリプションに 16 人の架空のユーザーを作成します。各ユーザーのライセンスと、各ユーザーのメールボックス、名前、メタデータ、写真が含まれます。</span><span class="sxs-lookup"><span data-stu-id="fec89-126">The Users sample data pack creates 16 fictitious users on your subscription, and includes the licenses for each user, and mailboxes, names, metadata, and photos for each.</span></span>

<span data-ttu-id="fec89-127">メールとイベントのサンプル データ パックによって、インストールされた各 16 人のユーザーに Outlook メールの会話とカレンダーのイベントが追加されます。</span><span class="sxs-lookup"><span data-stu-id="fec89-127">The Mail and Events sample data pack adds Outlook email conversations and calendar events for each of the 16 users installed.</span></span>

## <a name="how-do-i-install-the-users-sample-data-pack"></a><span data-ttu-id="fec89-128">ユーザー サンプル データ パックをインストールする方法</span><span class="sxs-lookup"><span data-stu-id="fec89-128">How do I install the Users sample data pack?</span></span>

<span data-ttu-id="fec89-129">ユーザー サンプル データ パックをインストールする前に、Microsoft 365 開発者サブスクリプションを取得していて、管理者として自分にライセンスを割り当てていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="fec89-129">Before you install the Users sample data pack, make sure that you have a Microsoft 365 developer subscription and that you assign a license to yourself as the admin.</span></span>

> [!NOTE]
> <span data-ttu-id="fec89-130">サブスクリプションで 16 人のユーザーが利用できることを確認します。</span><span class="sxs-lookup"><span data-stu-id="fec89-130">Make sure that you have 16 users available in your subscription.</span></span> <span data-ttu-id="fec89-131">サブスクリプションには、25 人のユーザーが含まれます。</span><span class="sxs-lookup"><span data-stu-id="fec89-131">Your subscription includes 25 users.</span></span> <span data-ttu-id="fec89-132">既に 10 人以上で構成されている場合は、最初に複数のユーザーを削除してインストールが成功したことを確認します。</span><span class="sxs-lookup"><span data-stu-id="fec89-132">If you have already configured more than 10 users, remove some users first to ensure that your installation is successful.</span></span>

<span data-ttu-id="fec89-133">ユーザー サンプル データ パックをインストールするには、次の操作を行います。</span><span class="sxs-lookup"><span data-stu-id="fec89-133">To install the Users sample data pack:</span></span>

1. <span data-ttu-id="fec89-134">サブスクリプション タイルの下部にある [**ユーザー**] ボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="fec89-134">Select the **Users** box at the bottom of your subscription tile.</span></span>
2. <span data-ttu-id="fec89-135">管理者 ID をコピーします。サブスクリプションにサインインする際に、アカウントが必要です。</span><span class="sxs-lookup"><span data-stu-id="fec89-135">Copy your administrator ID; you will need it to sign in to your subscription.</span></span>
3. <span data-ttu-id="fec89-136">サインイン ページで、管理者 ID とパスワードを入力します。</span><span class="sxs-lookup"><span data-stu-id="fec89-136">Enter your administrator ID and password on the sign in page.</span></span>
4. <span data-ttu-id="fec89-137">Microsoft 365 開発者サブスクリプションの管理者としての権限に同意します。</span><span class="sxs-lookup"><span data-stu-id="fec89-137">Consent to the permissions as an administrator of your Microsoft 365 developer subscription.</span></span>

![権限の同意ダイアログ ボックスを示すスクリーンショット](images/sample-data-pack-ux-tile-users-consent-with-permissions-combined.PNG)

5. <span data-ttu-id="fec89-139">すべてのサンプル ユーザーのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="fec89-139">Configure your passwords for all sample users.</span></span> <span data-ttu-id="fec89-140">すべての架空のユーザーを簡単に管理できるように、1 つの共有パスワードを定義する必要があります。</span><span class="sxs-lookup"><span data-stu-id="fec89-140">You will need to have one shared password defined for easy administration of all your fictitious users.</span></span>

![共有ユーザー パスワードを追加するダイアログ ボックスのスクリーンショット](images/sample-data-pack-ux-tile-users-fake-user-password-creation.PNG)

6. <span data-ttu-id="fec89-142">データがインストールされます。</span><span class="sxs-lookup"><span data-stu-id="fec89-142">The data will be installed.</span></span> <span data-ttu-id="fec89-143">インストールには約 5 分ほどかかります。</span><span class="sxs-lookup"><span data-stu-id="fec89-143">The installation should take about 5 minutes.</span></span>

![ダッシュボード タイルのインストール処理を示すスクリーンショット](images/sample-data-pack-ux-tile-users-installing-status.PNG)

7. <span data-ttu-id="fec89-145">インストールが完了すると、メールで通知され、サブスクリプション タイルのボックスは緑色になります。</span><span class="sxs-lookup"><span data-stu-id="fec89-145">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span> <span data-ttu-id="fec89-146">メールとイベントのサンプル データ パックをインストールできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fec89-146">You can now install the Mail and Events sample data pack.</span></span>

![インストールの準備ができたメールとイベントが表示されているダッシュボード タイルのスクリーンショット](images/sample-data-pack-ux-tile-users-installed.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a><span data-ttu-id="fec89-148">メールとイベントのサンプル データ パックをインストールする方法</span><span class="sxs-lookup"><span data-stu-id="fec89-148">How do I install the Mail and Events sample data pack?</span></span>

<span data-ttu-id="fec89-149">ユーザー サンプル データ パックをインストールした後、メールとイベントをインストールすることができます。</span><span class="sxs-lookup"><span data-stu-id="fec89-149">After you've installed the Users sample data pack, you can install mail and events.</span></span>

1. <span data-ttu-id="fec89-150">サブスクリプション タイルの [**メール &amp; イベント**] ボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="fec89-150">Choose the **Mail &amp; Events** box on your subscription tile.</span></span>
2. <span data-ttu-id="fec89-151">[**インストール**] を選択して、インストールを開始します。</span><span class="sxs-lookup"><span data-stu-id="fec89-151">Select **Install** to begin installation.</span></span>

![インストール ダイアログ ボックスのスクリーンショット](images/sample-data-pack-ux-tile-mail-and-events-begin-install.PNG)

> [!NOTE]
> <span data-ttu-id="fec89-153">サブスクリプションを作成したばかりの場合は、インストールを開始する前にそのサブスクリプションを完全にプロビジョニングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="fec89-153">If you just created your subscription, it must be fully provisioned before installation can begin.</span></span> <span data-ttu-id="fec89-154">これには数時間かかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="fec89-154">This can take up to a few hours.</span></span> <span data-ttu-id="fec89-155">インストールが開始された後、終了には最大 20 分かかります。</span><span class="sxs-lookup"><span data-stu-id="fec89-155">After installation starts, it can take up to 20 minutes to finish.</span></span>

3. <span data-ttu-id="fec89-156">インストールが完了すると、メールで通知され、サブスクリプション タイルのボックスは緑色になります。</span><span class="sxs-lookup"><span data-stu-id="fec89-156">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span>

## <a name="how-do-i-install-the-sharepoint-sample-data-pack"></a><span data-ttu-id="fec89-157">SharePoint サンプル データ パックをインストールする方法</span><span class="sxs-lookup"><span data-stu-id="fec89-157">How do I install the SharePoint sample data pack?</span></span>

<span data-ttu-id="fec89-158">SharePoint サンプル データ パックには 7 種類の SharePoint サイト テンプレートが含まれており、これを選択してコラボレーション、コミュニケーション、エンゲージメント、知識管理用に SharePoint ソリューションを体験しモデル化できます。</span><span class="sxs-lookup"><span data-stu-id="fec89-158">The SharePoint sample data pack includes seven different SharePoint site templates to choose from to experience and model SharePoint solutions for collaboration, communication, engagement, and knowledge management.</span></span>

<span data-ttu-id="fec89-159">これらは[SharePoint PnP look book](https://provisioning.sharepointpnp.com/) の中の最も人気のあるテンプレートです。</span><span class="sxs-lookup"><span data-stu-id="fec89-159">These are some of the most popular templates from the [SharePoint PnP look book](https://provisioning.sharepointpnp.com/).</span></span> <span data-ttu-id="fec89-160">今日では、任意のデバイスや画面に美しく表示される、美しく高速なサイトおよびかっこいいページのサンプル ソリューションを簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="fec89-160">Today, it's simple to create sample solutions of beautiful, fast sites and pages that look great on any device or screen.</span></span> <span data-ttu-id="fec89-161">これらのデザインからインスピレーションを得たり、三度ボックス テナントに追加して、次のサイトの構築を始めましょう。</span><span class="sxs-lookup"><span data-stu-id="fec89-161">Get inspired with these designs or add them to your sandbox tenant to start building your next site.</span></span>

<span data-ttu-id="fec89-162">テンプレートはサブスクリプションにインストールできます。</span><span class="sxs-lookup"><span data-stu-id="fec89-162">The templates can be installed on your subscription.</span></span> <span data-ttu-id="fec89-163">テンプレートを 1 つインストールすると、その他のテンプレートをインストールするオプションを得ることができます。</span><span class="sxs-lookup"><span data-stu-id="fec89-163">After you install one template, you have the option to install the others.</span></span> <span data-ttu-id="fec89-164">インストール プロセスには、以下の手順が含まれます。</span><span class="sxs-lookup"><span data-stu-id="fec89-164">The installation process includes the following steps:</span></span>

1. <span data-ttu-id="fec89-165">ドロップダウン メニューから希望のテンプレートを選びます。</span><span class="sxs-lookup"><span data-stu-id="fec89-165">Select the Template you want from the drop down menu.</span></span>

  ![SharePoint テンプレート選択画面のスクリーンショット](images/select-sharepoint-template.jpg)

2. <span data-ttu-id="fec89-167">サイトのカスタム オプションを設定するか、既定値を受け入れます。</span><span class="sxs-lookup"><span data-stu-id="fec89-167">Configure custom options for your sites, or accept the default values.</span></span>
3. <span data-ttu-id="fec89-168">サンドボックス テナントの管理者 ID とパスワードを使用して、認証を行い、インストールするアクセス許可を与えます。</span><span class="sxs-lookup"><span data-stu-id="fec89-168">Use the administrator ID of your sandbox tenant and password to authenticate and give permissions to install.</span></span> 

<span data-ttu-id="fec89-169">インストールが自動的に始まります。</span><span class="sxs-lookup"><span data-stu-id="fec89-169">Installation will proceed automatically.</span></span>

><span data-ttu-id="fec89-170">**メモ:** これらのサイト テンプレートのプロビジョニングは、英語版の Office 365 E3 または Microsoft 365 E5 開発者サブスクリプションでのみ機能し、含まれるすべてのコンテンツは英語のみです。</span><span class="sxs-lookup"><span data-stu-id="fec89-170">**Note:** The provisioning of these site templates only works with English Office 365 E3 or Microsoft 365 E5 developer subscriptions, and all content included is English only.</span></span>

## <a name="what-sharepoint-templates-are-available"></a><span data-ttu-id="fec89-171">使用可能な SharePoint テンプレートは?</span><span class="sxs-lookup"><span data-stu-id="fec89-171">What SharePoint templates are available?</span></span>

<span data-ttu-id="fec89-172">SharePoint サンプル パックには、7 種類のテンプレートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="fec89-172">The SharePoint sample pack includes seven different templates.</span></span>

### <a name="team-site-with-data"></a><span data-ttu-id="fec89-173">データが含まれるチーム サイト</span><span class="sxs-lookup"><span data-stu-id="fec89-173">Team site with data</span></span>

<span data-ttu-id="fec89-174">データが含まれるチーム サイのテンプレートには、SharePoint チーム サイトに自動的に関連付けられる複数のドキュメント ライブラリが含まれています。SharePoint Framework、PowerApps、Microsoft Graph を使用してソリューションを開発する際に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="fec89-174">The Team site with data template includes multiple lists and document libraries that are automatically associated with a SharePoint team site to help you develop solutions using SharePoint Framework, Power Apps, and Microsoft Graph.</span></span>

<span data-ttu-id="fec89-175">このテンプレートには、次のデータが含まれます。</span><span class="sxs-lookup"><span data-stu-id="fec89-175">This template includes the following data:</span></span>

- <span data-ttu-id="fec89-176">事前入力された連絡先を含む連絡先リスト</span><span class="sxs-lookup"><span data-stu-id="fec89-176">A contact list with pre-populated contacts</span></span>
- <span data-ttu-id="fec89-177">6000を超えるアイテムが含まれるリスト</span><span class="sxs-lookup"><span data-stu-id="fec89-177">A list populated with over 6,000 items</span></span>
- <span data-ttu-id="fec89-178">サンプルの PowerPoint、Excel、Word、および OneNote のドキュメントを含むドキュメントライブラリ</span><span class="sxs-lookup"><span data-stu-id="fec89-178">Document libraries with sample PowerPoint, Excel, Word, and OneNote documents</span></span>
- <span data-ttu-id="fec89-179">お知らせアイテムを含むイベントリスト</span><span class="sxs-lookup"><span data-stu-id="fec89-179">An events list with announcement items</span></span>

<span data-ttu-id="fec89-180">このテンプレートは、ユーザーのサンプル データと統合されます。</span><span class="sxs-lookup"><span data-stu-id="fec89-180">This template integrates with the Users sample data.</span></span>

### <a name="work--contoso"></a><span data-ttu-id="fec89-181">Contoso で働く</span><span class="sxs-lookup"><span data-stu-id="fec89-181">Work @ Contoso</span></span>
<span data-ttu-id="fec89-182">Contoso で働くテンプレートは複数のサイト コレクションで構成されています。すべての既定の集計機能がどのように機能するかを示すため、これらはすべて自動的にハブ サイトに関連付けられます。</span><span class="sxs-lookup"><span data-stu-id="fec89-182">The Work @ Contoso template consists of multiple site collections that are all automatically associated with the hub site to show how all default aggregation capabilities work.</span></span>

<span data-ttu-id="fec89-183">このテンプレートには、次の構造とアセットが含まれます。</span><span class="sxs-lookup"><span data-stu-id="fec89-183">This template contains following structures and assets:</span></span>

- <span data-ttu-id="fec89-184">ハブ サイトとしてのメイン サイト コレクション セット</span><span class="sxs-lookup"><span data-stu-id="fec89-184">Main site collection set as a hub site</span></span>
- <span data-ttu-id="fec89-185">ハブ サイトに関連付けられた 2 種類のコミュニケーション サイト (福利厚生サイトとチャリティ サイト)</span><span class="sxs-lookup"><span data-stu-id="fec89-185">Two communication sites associated with the hub site - Benefits and charity sites</span></span>
- <span data-ttu-id="fec89-186">ハブ サイトに関連付けられた 1 種類のグループ チーム サイト (チーム サイト)</span><span class="sxs-lookup"><span data-stu-id="fec89-186">One group team site associated with the hub site - Team site</span></span>
- <span data-ttu-id="fec89-187">サブサイト コレクションのサンプル ニュース記事</span><span class="sxs-lookup"><span data-stu-id="fec89-187">Sample news articles in the subsite collections</span></span>
- <span data-ttu-id="fec89-188">Word、Excel、PowerPoint のサンプル ファイル</span><span class="sxs-lookup"><span data-stu-id="fec89-188">Sample Word, Excel, and PowerPoint files</span></span>
- <span data-ttu-id="fec89-189">サイト コレクションで使用している画像コンテンツのサンプル</span><span class="sxs-lookup"><span data-stu-id="fec89-189">Sample image content used in the site collections</span></span>

<span data-ttu-id="fec89-190">サブサイト コレクションでも同じテンプレートが使用されています。このテンプレートは、このサービスとは別に提供することもできます。</span><span class="sxs-lookup"><span data-stu-id="fec89-190">Subsite collections use the same templates, which you can also provision separately from this service.</span></span>

><span data-ttu-id="fec89-191">**メモ:** このテンプレートを既存のコミュニケーション サイトに適用した場合、ウェルカム ページのコンテンツが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="fec89-191">**Note:** If this template is applied on top of an existing communication site, the welcome page content of the site will be overwritten.</span></span>

### <a name="leadership-connection-leadership-news-events-engagement"></a><span data-ttu-id="fec89-192">リーダーシップ コネクション: リーダーシップ ニュース、イベント、エンゲージメント</span><span class="sxs-lookup"><span data-stu-id="fec89-192">Leadership Connection: Leadership news, events, engagement</span></span>

<span data-ttu-id="fec89-193">このリーダーシップ サイトでは、リーダーシップ チームの目標と優先事項を理解する手掛かりを提供し、イベントおよび会話へのエンゲージメントを生み出します。</span><span class="sxs-lookup"><span data-stu-id="fec89-193">This leadership site provides insight into the goals and priorities of the leadership team, and inspires engagement with events and conversations.</span></span>

<span data-ttu-id="fec89-194">このデザインをテナントに追加すると、次のコンテンツが作成されます。</span><span class="sxs-lookup"><span data-stu-id="fec89-194">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="fec89-195">Web パーツのデモを含むウェルカム ページのサンプル</span><span class="sxs-lookup"><span data-stu-id="fec89-195">Example welcome page with demonstration of web parts</span></span>
- <span data-ttu-id="fec89-196">様々なモダン ページのデザインのデモを含むニュース記事のサンプル</span><span class="sxs-lookup"><span data-stu-id="fec89-196">Example news articles demonstrating different modern page designs</span></span>

<span data-ttu-id="fec89-197">このテンプレートは、ユーザーのサンプル データと統合されます。</span><span class="sxs-lookup"><span data-stu-id="fec89-197">This template integrates with the Users sample data.</span></span>

### <a name="the-landing-news-resources-personalized-content"></a><span data-ttu-id="fec89-198">Landing : ニュース、リソース、個人用コンテンツ</span><span class="sxs-lookup"><span data-stu-id="fec89-198">The Landing: News, resources, personalized content</span></span>

<span data-ttu-id="fec89-199">このコミュニケーション サイトは、従業員がニュースや必要なリソースに加え、従業員に合った個人用コンテンツを検索できる場所となるように設計されています。</span><span class="sxs-lookup"><span data-stu-id="fec89-199">This communication site is designed to be the place where your employees can find the news and resources they need, plus personalized content tailored just for them.</span></span>

<span data-ttu-id="fec89-200">このデザインをテナントに追加すると、次のコンテンツが作成されます。</span><span class="sxs-lookup"><span data-stu-id="fec89-200">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="fec89-201">ポータルのホーム サイトのデモ構造</span><span class="sxs-lookup"><span data-stu-id="fec89-201">Demo structure for home site of the portal</span></span>
- <span data-ttu-id="fec89-202">カスタム ウェルカム ページ構造</span><span class="sxs-lookup"><span data-stu-id="fec89-202">Custom welcome page structure</span></span>
- <span data-ttu-id="fec89-203">6 種類のモダン ページとニュース記事のサンプル</span><span class="sxs-lookup"><span data-stu-id="fec89-203">Six additional sample modern pages and news articles</span></span>
- <span data-ttu-id="fec89-204">サンプル画像と Office ドキュメント</span><span class="sxs-lookup"><span data-stu-id="fec89-204">Sample images and Office documents</span></span>

### <a name="the-perspective-news-video-personalized-content"></a><span data-ttu-id="fec89-205">Perspective: ニュース、ビデオ、個人用コンテンツ</span><span class="sxs-lookup"><span data-stu-id="fec89-205">The Perspective: News, video, personalized content</span></span>

<span data-ttu-id="fec89-206">ニュースや個人用コンテンツを提供するよう設計されているこのサイトには、さらに多くのエンゲージメントを生み出すビデオも含まれています。</span><span class="sxs-lookup"><span data-stu-id="fec89-206">Designed to offer news and personalized content, this site also includes videos to inspire even more engagement.</span></span>
<span data-ttu-id="fec89-207">このデザインをテナントに追加すると、次のコンテンツが作成されます。</span><span class="sxs-lookup"><span data-stu-id="fec89-207">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="fec89-208">カスタム ウェルカム ページのデザイン</span><span class="sxs-lookup"><span data-stu-id="fec89-208">Custom welcome page designs</span></span>
- <span data-ttu-id="fec89-209">ニュース記事用のサンプル ページ テンプレート</span><span class="sxs-lookup"><span data-stu-id="fec89-209">Sample page template for news articles</span></span>
- <span data-ttu-id="fec89-210">12 種類のサンプル ニュース記事</span><span class="sxs-lookup"><span data-stu-id="fec89-210">12 sample news articles</span></span>

### <a name="new-employee-onboarding-hub-connect-engage-inform"></a><span data-ttu-id="fec89-211">新しい従業員のオンボーディング ハブ: 接続、エンゲージメント、情報提供</span><span class="sxs-lookup"><span data-stu-id="fec89-211">New Employee Onboarding Hub: Connect, Engage, Inform</span></span>

<span data-ttu-id="fec89-212">プレオンボーディング、企業レベルのオンボーディング、部門レベルのオンボーディング シナリオをカバーする既成テンプレートで、新入社員オンボーディングのプロセスを効率化し、洗練化します。</span><span class="sxs-lookup"><span data-stu-id="fec89-212">Streamline and refine your new employee onboarding process with pre-built templates that cover Pre-onboarding, Corporate-level onboarding, and Departmental-level onboarding scenarios.</span></span> <span data-ttu-id="fec89-213">このデジタルなソリューションは、4 種類のサイト テンプレートを提供します。これには、組織の目標に応じてカスタマイズ可能な事前に用意されたコンテンツが含まれます。</span><span class="sxs-lookup"><span data-stu-id="fec89-213">This digital solution offers four different site templates that contain pre-populated content that can be customized to align with the goals of your organization.</span></span>

<span data-ttu-id="fec89-214">このデザインをテナントに追加すると、次のコンテンツが作成されます。</span><span class="sxs-lookup"><span data-stu-id="fec89-214">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="fec89-215">プレオンボーディング サイト、企業オンボーディング サイト、2 種類の部門オンボーディング サイト</span><span class="sxs-lookup"><span data-stu-id="fec89-215">Pre-onboarding site, Corporate onboarding site, and two Departmental onboarding sites</span></span>
- <span data-ttu-id="fec89-216">各サイトで使用できる、事前に用意されたカスタム ホーム ページ</span><span class="sxs-lookup"><span data-stu-id="fec89-216">Custom and pre-populated home pages for each site</span></span>
- <span data-ttu-id="fec89-217">企業オンボーディングのために構成されたハブ サイトと、部門オンボーディングのための関連サイト</span><span class="sxs-lookup"><span data-stu-id="fec89-217">Configured hub site for Corporate onboarding and associated sites for Departmental onboarding</span></span>
- <span data-ttu-id="fec89-218">新入社員のオンボーディングを成功させるのに役立つ、SharePoint のリストに構築された新入社員チェックリスト</span><span class="sxs-lookup"><span data-stu-id="fec89-218">New employee checklist built on SharePoint Lists to help new hires onboard successfully</span></span>
- <span data-ttu-id="fec89-219">連絡先 Web パーツ、Yammer Web パーツ、ニュース Web パーツ、クイック リンク Web パーツ用のサンプル コンテンツ</span><span class="sxs-lookup"><span data-stu-id="fec89-219">Example content for the People web part, Yammer web part, News web part, and Quick links web part</span></span>
- <span data-ttu-id="fec89-220">各サイトで使用できる、事前に記入された FAQ</span><span class="sxs-lookup"><span data-stu-id="fec89-220">Pre-written FAQs for each site</span></span>
- <span data-ttu-id="fec89-221">YouTube Web パーツを使用してプレオンボーディング サイトにウェルカム ビデオを含めるなど、交流とエンゲージメントを促進するエクスペリエンスを作るためのおすすめ候補</span><span class="sxs-lookup"><span data-stu-id="fec89-221">Recommendations for creating social and engaging experiences, like including a welcome video using the YouTube web part on the Pre-onboarding site</span></span>

### <a name="crisis-communications-announcements-news-resources-communities-and-calls-to-action"></a><span data-ttu-id="fec89-222">Crisis Communication: お知らせ、ニュース、リソース、コミュニティ、実施すべき内容</span><span class="sxs-lookup"><span data-stu-id="fec89-222">Crisis Communications: Announcements, news, resources, communities and calls-to-action</span></span>

<span data-ttu-id="fec89-223">異常気象現象、医療上や保安上の緊急事態などの非常時でも、ユーザーに情報を提供し、エンゲージメントを保ち、前進するよう助けます。</span><span class="sxs-lookup"><span data-stu-id="fec89-223">Keep people informed, engaged, and moving forward during crises, from extreme weather events to health and safety emergencies.</span></span> <span data-ttu-id="fec89-224">このテンプレートは、重要なニュースや告知を共有するリーダーや通信者のための中心的なリソースを作成し、人々に最新の情報を提供する真実の単一ソースであり、組織全員を接続する場所となります。</span><span class="sxs-lookup"><span data-stu-id="fec89-224">This template creates a central resource for leaders and communicators to share important news and announcements, a single source of truth where people can stay up-to-date, and a place to connect people across the organization.</span></span>

<span data-ttu-id="fec89-225">このデザインをテナントに追加すると、次のコンテンツが作成されます。</span><span class="sxs-lookup"><span data-stu-id="fec89-225">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="fec89-226">Web パーツを使用して構築されたカスタムのウェルカム ページ</span><span class="sxs-lookup"><span data-stu-id="fec89-226">Custom welcome page built using a web part</span></span>
- <span data-ttu-id="fec89-227">コンテンツを含む 4 種類のニュース記事</span><span class="sxs-lookup"><span data-stu-id="fec89-227">Four news articles with example content</span></span>

<span data-ttu-id="fec89-228">このテンプレートは、ユーザーのサンプル データと統合されます。</span><span class="sxs-lookup"><span data-stu-id="fec89-228">This template integrates with the Users sample data.</span></span>

## <a name="are-more-sample-data-packs-coming"></a><span data-ttu-id="fec89-229">サンプル データ パックは追加されますか?</span><span class="sxs-lookup"><span data-stu-id="fec89-229">Are more sample data packs coming?</span></span>

<span data-ttu-id="fec89-230">はい。</span><span class="sxs-lookup"><span data-stu-id="fec89-230">Yes.</span></span> <span data-ttu-id="fec89-231">将来、Microsoft Teams など、他の製品とテクノロジのサンプル データ パックを追加することを検討しています。</span><span class="sxs-lookup"><span data-stu-id="fec89-231">In the future, we will consider adding sample data packs for more products and technologies, including Microsoft Teams.</span></span> <span data-ttu-id="fec89-232">サンプル データ パックに関してご提案のある場合は[お知らせください](https://officespdev.uservoice.com/forums/224641-feature-requests-and-feedback?category_id=171306)。</span><span class="sxs-lookup"><span data-stu-id="fec89-232">If you have suggestions for sample data packs that you would like to see, [let us know](https://officespdev.uservoice.com/forums/224641-feature-requests-and-feedback?category_id=171306).</span></span>

## <a name="can-i-install-sample-data-packs-on-my-other-microsoft-365-subscriptions"></a><span data-ttu-id="fec89-233">サンプル データ パックを他の Microsoft 365 サブスクリプションにインストールできますか?</span><span class="sxs-lookup"><span data-stu-id="fec89-233">Can I install sample data packs on my other Microsoft 365 subscriptions?</span></span>

<span data-ttu-id="fec89-234">いいえ。</span><span class="sxs-lookup"><span data-stu-id="fec89-234">No.</span></span> <span data-ttu-id="fec89-235">これらのサンプル データ パックは、Microsoft 365 開発者プログラムの一部として取得した Microsoft 365 開発者サブスクリプションとのみ互換性があります。</span><span class="sxs-lookup"><span data-stu-id="fec89-235">These sample data packs are only compatible with the Microsoft 365 developer subscription you get as part of the Microsoft 365 Developer Program.</span></span>

## <a name="how-can-i-see-the-sample-data-in-my-subscription"></a><span data-ttu-id="fec89-236">サンプル データをサブスクリプションに表示するにはどのようにすればよいですか?</span><span class="sxs-lookup"><span data-stu-id="fec89-236">How can I see the sample data in my subscription?</span></span>

<span data-ttu-id="fec89-237">ユーザーのサンプル データ パックのインストール後に、追加されたユーザーを表示するには、Microsoft 365 開発者サブスクリプションの [**Microsoft 365 管理センター**](https://admin.microsoft.com/) に移動します。</span><span class="sxs-lookup"><span data-stu-id="fec89-237">After you install the Users sample data pack, to see the users that were added, go to the [**Microsoft 365 Admin Center**](https://admin.microsoft.com/) on your Microsoft 365 developer subscription.</span></span> <span data-ttu-id="fec89-238">[**ユーザー**] の下で [**アクティブなユーザー**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="fec89-238">Under **Users**, select **Active users**.</span></span> <span data-ttu-id="fec89-239">16 人のユーザーの一覧が表示されます。</span><span class="sxs-lookup"><span data-stu-id="fec89-239">You will see the list of 16 users.</span></span> <span data-ttu-id="fec89-240">ユーザーを選択すると、写真やライセンスを含む関連付けられたメタデータを表示できます。</span><span class="sxs-lookup"><span data-stu-id="fec89-240">You can select a user to view the associated metadata, including photos and licenses.</span></span>

![Microsoft 365 管理センターで表示される、16 人のユーザーと選択したユーザーのメタデータのスクリーンショット ](images/content-packs-07.PNG)

<span data-ttu-id="fec89-242">メールとイベントのサンプル パックのインストール後にサンプル データを表示するには、[**Microsoft 365 管理センター**](/microsoft-365/admin/admin-overview/about-the-admin-center?view=o365-worldwide)で [**すべて表示**] を選択して、[**Exchange**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="fec89-242">After you install the Mail and Events sample pack, to see the sample data, in the [**Microsoft 365 Admin Center**](/microsoft-365/admin/admin-overview/about-the-admin-center?view=o365-worldwide), choose **Show all** and then select **Exchange**.</span></span> <span data-ttu-id="fec89-243">Exchange 管理センターで [**受信者**] を選択すると、16 人のユーザーそれぞれがメールボックスを持ち、メールやイベントが追加されていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="fec89-243">In the Exchange admin center, when you select **recipients**, you can see that each of the 16 users has mailboxes with mail and events added.</span></span>
<span data-ttu-id="fec89-244">![Exchange 管理センターに追加された 16 人のユーザーのスクリーンショット](images/content-packs-08.PNG)</span><span class="sxs-lookup"><span data-stu-id="fec89-244">![Screenshot of 16 users added to the Exchange Admin Center](images/content-packs-08.PNG)</span></span>

## <a name="see-also"></a><span data-ttu-id="fec89-245">関連項目</span><span class="sxs-lookup"><span data-stu-id="fec89-245">See also</span></span>

- [<span data-ttu-id="fec89-246">Microsoft 365 開発者サブスクリプションを設定する</span><span class="sxs-lookup"><span data-stu-id="fec89-246">Set up a Microsoft 365 developer subscription</span></span>](microsoft-365-developer-program-get-started.md)
