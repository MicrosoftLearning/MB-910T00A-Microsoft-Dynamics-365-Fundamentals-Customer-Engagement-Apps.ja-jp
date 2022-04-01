---
lab:
  title: ラボ 1.5:Dynamics 365 Marketing でのセグメントの作成
  module: 'Module 1: Learn the Fundamentals of Dynamics 365 Marketing'
ms.openlocfilehash: 5f75e433fe8d38d32000c7de20878e3b471f0fca
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909012"
---
<a name="module-1-learn-the-fundamentals-of-dynamics-365-marketing"></a>モジュール 1: Dynamics 365 Marketing の基礎について学習する
========================

## <a name="practice-lab-15---create-a-segment-in-dynamics-365-marketing"></a>実践ラボ 1.5 - Dynamics 365 Marketing でのセグメントの作成

## <a name="objectives"></a>目標

この演習でわかるように、住所や興味などの一般的なデモグラフィック情報に基づいて、特定の取引先担当者の顧客セグメントをターゲットにすることは非常に簡単です。 顧客セグメントは顧客体験でターゲットにする取引先担当者を定義するなどの主要なマーケティング活動で使用されるため、Dynamics 365 Marketing では顧客セグメントの作成をよく行います。

## <a name="lab-setup"></a>ラボのセットアップ

  - **推定時間**:20 分間

## <a name="instructions"></a>Instructions


1. Dynamics Marketing アプリケーションを開きます。 **「マーケティング」** 領域が選択されます。 **「顧客」** の下の **「セグメント」** を選択します。

2. コマンド バーで、 **[新規]** を選択します。

3. 表示されるドロップダウンメニューで、 **「新しい動的セグメント」** を選択します。

4. 開いた **「セグメント テンプレート」** ダイアログ ボックスで、 **「スキップ」** を選択して閉じ、 **「新しいセグメント」** 画面に進みます。

5. 連絡先テーブルに対してクエリを作成するには、 **「クエリ ブロックの追加」** を選択します。 

6. **「属性の選択」** コントロールを選択します。

7. 「市区町村」と入力して一覧をフィルター処理し、 **[住所 1:市区町村]** を選択します。

8. 次のドロップダウン リストは「**等しい**」に設定したままにします。 

9. **「入力して検索」** をクリックして、 **「Chicago」** と入力します。

10. クエリの上部にある **「名前」** フィールドを選択し、 **「Chicago Contacts - あなたのイニシャル」** と入力します。

11. コマンド バーで **「保存」** を選択して、セグメントを保存します。

12. **「Go Live」** を選択して、セグメントを公開します 

13. 1 分ほど待ってから、コマンド バーの **「最新の情報に更新」** を選択してページを更新します。 

14. これで、 **「メンバー」** タブが追加されたことがわかります。 Jackson Andersonが一覧表示されます。
