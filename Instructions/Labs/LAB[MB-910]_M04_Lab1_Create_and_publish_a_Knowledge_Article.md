---
lab:
  title: ラボ 4.1:Dynamics 365 Customer Service で情報記事を作成して公開する
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Customer Service'
ms.openlocfilehash: 076c92c7a9b1843a0e0e4b7a03a725cfc3b1d43b
ms.sourcegitcommit: 6065e6a662bd0407d37fcc565c1b2da1c916255d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2022
ms.locfileid: "144405037"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-customer-service"></a>モジュール 4:Dynamics 365 Customer Service の基礎を学ぶ
========================

## <a name="practice-lab-41---create-and-publish-a-knowlege-article-in-dynamics-365-customer-service"></a>実践ラボ 4.1 - Dynamics 365 Customer Service で情報記事を作成して公開する

## <a name="lab-setup"></a>ラボのセットアップ

  - **推定時間**:15 分

## <a name="instructions"></a>Instructions

1. まだ開いていない場合、**Dynamics 365 顧客サービス ハブ** アプリケーションを開きます。 

2. 画面の左側にあるナビゲーションを使用して、**[情報記事]** を選択します。 

3. どの記事がさまざまな段階にあるかを簡単に確認するには、 **[自分のアクティブな記事]** の横にあるドロップダウン矢印を選択します。 

4. **[下書き記事]** を選択します。 

5. **[承認済みの記事]** を選択します。 承認済みの記事が少なくとも 1 つ表示されます。  

6. **[自分のアクティブな記事]** に戻ります

7. **コマンド バー** で、**[新規]** ボタンを選択します。 

8. 新しいレコードが開いたら、上部のレコード ヘッダーの **[状態の理由]** フィールドの横にあるドロップダウン矢印を選択します。 **[言語]** を [**英語 - 米国]** に設定します。

8. 次のように入力して、記事を完成させます。

    - **タイトル:** 到着時に壊れたアイテム – あなたのイニシャル

    - **キーワード:** 壊れたアイテム、破損、返品

    - **説明:** アイテムが破損して到着した場合の問題の解決に役立ちます。 

9. コンテンツ デザイナーのテキストに次のテキストを入力します。   
‎  
‎   到着したアイテムが破損している

    アイテムが破損して到着した場合は、次の手順を実行します。

    1. Web ポータルを開く

    2. 注文記録を探す

    3. アイテムの返品を選択する

    4. 破損の理由を選択する

    5. 印刷を選択する

    返品/破損したアイテムを受け取り次第、アカウントに返金されます。

    **注:** 必要に応じて、テキストにフォーマットを追加できます。 

10. **コマンド バー** で、**[保存]** ボタンを選択して情報記事を保存し、開いたままにします。 

11. **[新しいプロセス]** で、**作成者** ステージを選択し、**[記事の件名]** フィールドを **[配信]** ([サービス] の下にあります) に設定します。 

12. **[レビュー対象としてマーク]** フィールドを **[完了]** に設定します。

13. **[次のステージ]** ボタンを選択して、**レビュー** ステージに進みます。

14. **コマンド バー** で、**[保存して閉じる]** ボタンを選択して変更を保存し、記事を閉じます。

作成者が最初にレコードを作成した後、通常、ライブになる前に承認プロセスを経ます。 次に、承認者として記事を承認します。 

15. 情報記事で、ビューを **[提案された記事]** に切り替えて、承認が必要な記事を確認します。 

16. 作成した **[到着時に壊れたアイテム – あなたのイニシャル]** の記事を開きます。

17. **[新しいプロセス]** で、**レビュー** ステージを選択します。 **[レビュー]** フィールドを **[承認済み]** に設定します。

18. 記事の承認を確認するように求められたら、**[OK]** を選択します。 

19. **[次のステージ]** ボタンを選択して **[公開]** ステージに進みます。 

20. 記事の上部にある **コマンド バー** で、コマンド バーの左側にある **垂直の省略記号** を選択します。 表示されるメニューで、**[製品の関連付け]** を選択します。 

21. **[製品の関連付け]** ウィンドウで、**[Office 365 for Enterprise (サンプル)]** を選択します。

22. **[関連付け]** ボタンを選択します。 

23. **[新しいプロセス]** で、**[公開]** ステージを選択します。 

24. **[製品の関連付けの設定]** を **[完了]** としてマークします。 

25. **有効期限** を **本日から 1 年後の午前 12 時** に設定します。 

26. **[完了]** ボタンを選択して、プロセスを完了します。 

27. 記事の **コマンド バー** で、**[公開]** ボタンを選択します。 

28. 以下が選択されていることを確認します。

    - **発行:** 今すぐ

    - **発行状態:** 発行済み

    - **有効期限:** 本日から 1 年後の午前 12 時

    - **期限切れ状態:** 期限切れ

    - **期限切れステータス:** 期限切れ

    - **承認された翻訳を公開する:** いいえ
    
29. **公開** ボタンをクリックして、記事を公開します。

