---
lab:
  title: ラボ 1.1:ラボ環境を検証する
  module: 'Module 1: Learn the Fundamentals of Dynamics 365 Marketing'
ms.openlocfilehash: a4936e98edafb368bbb79f18ead84db62f28ba2e
ms.sourcegitcommit: 8f0cd342cd9b9153251c25f993c732ac0d34ab9d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/04/2022
ms.locfileid: "141368407"
---
<a name="module-1-learn-the-fundamentals-of-dynamics-365-marketing"></a>モジュール 1: Dynamics 365 Marketing の基礎について学習する
========================

## <a name="practice-lab-11---validate-lab-environment"></a>実践ラボ 1.1 - ラボ環境の確認 

このラボでは、教室のテナントが期待どおりに動作していることを検証します。 個々の資格情報にアクセスし、「エイリアス」を記録し、コース全体で使用する Dynamics 365 モデル駆動型アプリケーションを開きます。 

**重要な注意:** このラボでは、実際の Dynamics 365 テナントとこのコースで使用する Power Platform アプリケーションのライセンスが提供されます。 Power Platform は常に進化していることに注意してください。 このドキュメントに記載されている手順は、実際のテナントでの操作とは異なる場合があります。 また、仮想マシンがラボを開始するためのネットワーク接続を確立するまでに数分の遅延が発生する可能性もあります。

<a name="exercise-1---access-the-dynamics-365-application"></a>演習 1 - Dynamics 365 アプリケーションへのアクセス
---------------------------------------------------

### <a name="task-1--log-into-the-power-platform-admin-center"></a>タスク 1 – Power Platform 管理センターにログインする

1.  <https://admin.Powerplatform.microsoft.com> にアクセスし、自身のユーザー資格情報でログインします。

2. スクラッチ用紙またはメモ帳に、 **@** 記号までユーザーの資格情報を記録します。 これは、Shared Dynamics 365 組織内で作成するデータを区別するために使用するラボのエイリアスになります。 

**重要:** このテナントと Dynamics 365 組織は、従業員が組織に属する Dynamics 365 インスタンスを使用する場合にテナントを共有するように、教室内の他の受講者と共有されます。 レコードの作成時に PII (個人を特定できる情報) を使用しないでください。 また、作成したすべてのレコード、データ、アプリ、フローなどの前にユーザー名プレフィックス (例、**mollyc**) を使用することをお勧めします。

3. Power Platform 管理センターを自由に探索できますが、**変更はしないでください。**

### <a name="task-2--access-the-dynamics-365-application"></a>タスク 2 – Dynamics 365 アプリケーションにアクセスする

1.  https://admin.powerplatform.microsoft.com/environments にアクセスします。

2. WWLLABnnn 環境 (nnn は数値) を選択します。 これは、共有の Dynamics 365 環境で、ここですべてのラボを実行します。

3. [環境を開く] をクリックします

4. 画面の左上にある [アプリ ランチャー] ドミノ ボタンを、**Power Platform 管理センター** の左に直接展開します。 Dynamics 365 **Marketing** アプリを選択して起動します。

5.  左側のナビゲーション ペインを確認します。 ペインの下部のボタンにより、領域を変更できます。 現在、「**マーケティング**」領域が表示されています。 

6.  ナビゲーション ペインの下部にある「**マーケティング**」を選択して、「**イベント**」領域を選択します。 ナビゲーション ペインの「**イベント**」領域を確認します。  

7. 数分間アプリケーションを確認してから、「**マーケティング**」領域に戻ります。
