---
lab:
  title: 'ラボ 4.2:Dynamics 365 Customer Service でサポート案件を作成および管理する'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Customer Service'
---

<a name="module-4-learn-the-fundamentals-of-dynamics-365-customer-service"></a>モジュール 4:Dynamics 365 Customer Service の基礎を学ぶ
========================

## <a name="practice-lab-42---create-and-manage-cases-in-dynamics-365-customer-service"></a>実践ラボ 4.2 - Dynamics 365 Customer Service でサポート案件を作成および管理する

## <a name="lab-setup"></a>ラボのセットアップ

  - **推定時間**:10 分

## <a name="instructions"></a>Instructions

1. まだ開いていない場合、**Dynamics 365 顧客サービス ハブ** アプリケーションを開きます。 

2. 画面の左側にあるナビゲーションを使用して、**[サポート案件]** を選択します。 

3. **コマンド バー**で、**[新しいサポート案件]** を選択して、新しいサポート案件レコードを作成します。

4. 新しいサポート案件レコードを次のように入力します。

    - **サポート案件のタイトル:** 到着したアイテムが破損している - あなたのイニシャル

    - **顧客:** Alpine Ski House

    - **作成元:** 電話

5. **[保存]** ボタンを選択してレコードを保存し、開いたままにしておきます。 

6. **サポート案件への電話**のプロセスで、**識別**ステージを選択し、**[連絡先の検索]** フィールドを「**Patrick Sands**」に設定します。 

7. **[識別]** ステージ フライアウト ウィンドウの **[X]** を選択してウィンドウを削除し、作業を続行できるようにします。 

8. **レコード タイムライン**を使用して、**プラス記号アイコン**を選択し、新しいアクティビティを作成します。 

9. 表示されたメニューで、**[電話] ** を選択します。

10. **"件名"** フィールドを **[Patrick に折り返し電話する – あなたのイニシャル]** に設定し、残りのフィールドはそのままにします。 

11. **[保存して閉じる]** ボタンを選択します。 

12. **サポート案件への電話プロセス**で、**識別**ステージを選択します。

13. **[次のステージ]** ボタンを選択して **[調査]** ステージに進みます。 

14. **[調査]** ステージ フライアウト ウィンドウで **[X]** を選択してウィンドウを削除し、作業を続行できるようにします。 

15. On the right side of the case screen, locate and select the <bpt id="p1">**</bpt>Knowledge<ept id="p1">**</ept> book Icon. (It will be directly below the <bpt id="p1">**</bpt>wrench<ept id="p1">**</ept> icon).

16. Notice that the title of the case you created is automatically provided as the search text. Locate and select the <bpt id="p1">**</bpt>Item Broken on Arrival<ept id="p1">**</ept> article you created earlier. 

17. The full contents of the article will be displayed, select the <bpt id="p1">**</bpt>Link this article to the current record<ept id="p1">**</ept> icon. Verify that the text <bpt id="p1">**</bpt>Linked to Case<ept id="p1">**</ept> appears. 

18. Now we will get ready to resolve the case. On the <bpt id="p1">**</bpt>Record Timeline<ept id="p1">**</ept>, hover over the <bpt id="p2">**</bpt>Return call to Patrick<ept id="p2">**</ept> Phone Call activity you created earlier. Select the mark complete <bpt id="p1">**</bpt>Check Mark Icon<ept id="p1">**</ept> to complete the activity. 

19. On the <bpt id="p1">**</bpt>Close Phone Call<ept id="p1">**</ept> screen, select the <bpt id="p2">**</bpt>Close<ept id="p2">**</ept> button. Verify the activity says <bpt id="p1">**</bpt>Closed<ept id="p1">**</ept>. 

20. **[サポート案件への電話プロセス]** で、**[調査]** ステージを選択し、**[次のステージ]** を選択して、**[解決]** ステージに進みます。 

21. **[解決]** ステージで、**[完了]** ボタンを選択して、プロセス フローを完了します。 

22. サポート案件レコードの **コマンド バー**で、**[ケースの解決]** ボタンを選択します。

23. **[ケースの解決]** ウィンドウで、**"解決"** フィールドを **[ナレッジ記事]** に設定します。 

24. **[解決]** ボタンを選択して、プロセスを完了します。 
