---
lab:
  title: 'ラボ 3.2:Dynamics 365 Sales の営業案件の作成と管理'
  module: 'Module 3: Learn the Fundamentals of Dynamics 365 Sales'
---

<a name="module-3-learn-the-fundamentals-of-dynamics-365-sales"></a>モジュール 3:Dynamics 365 Sales の基礎を学ぶ
========================

## <a name="practice-lab-32---create-and-manage-an-opportunity-in-dynamics-365-sales"></a>実践ラボ 3.2 - Dynamics 365 Sales の営業案件の作成と管理 

## <a name="objectives"></a>目標

During this exercise, you will be manually capturing a sales opportunity for an existing customer named Jim Glynn. He works for a company called Adventure Work. Not only will you be capturing the opportunity in the system, but you will be using the tools available in Dynamics 365 Sales to work through and close the opportunity.


## <a name="lab-setup"></a>ラボのセットアップ

  - **推定時間**:25 分

## <a name="instructions"></a>Instructions

この演習では、Dynamics 365 のホーム画面を使用してさまざまな Dynamics 365 Customer Engagement アプリケーションにアクセスする方法を理解します。 

1. まだ開いていない場合、**Dynamics 365 営業ハブ**アプリケーションを開きます。 

2. 画面の左側にあるナビゲーションを使用して、**[営業案件]** を選択します。 

3. 自分のオープンしている営業案件ビューで **[新規]** ボタンを選択して、新しい営業案件を作成します。

4. 営業案件情報を次のように作成します。

    - **トピック:** 既存の機器をアップグレードしたい – あなたのイニシャル

    - **問い合わせ先:** Jim Glynn

    - **アカウント:** Adventure Works

    - **購入期間:** 今四半期

    - **予算金額:** 62500

    - **購入プロセス:** 個人

5. レコードの上部にある**新しい営業案件ヘッダー**で、所有者フィールドの横の下矢印を選択します。 

6. 次のように入力します。

    - **予測クローズ日:** 今日から 2 日後

    - **推定収益:** 62500

7. 上部にある**コマンド バー**で **[保存して閉じる]** を選択します。 

8. **自分のオープンしている営業案件**ビューで、前の演習でリードを評価するときに作成された**新規備品の検索**営業案件を指定して開きます。 

9. レコードが、リードから営業案件への営業プロセスの営業案件の**開発**フェーズにあることに注意してください。 

10. レコードの上部にある **[Looking for new equipment opportunity]\(新規備品営業案件の検索\)** ヘッダーで、所有者フィールドの横の下矢印を選択します。 

11. 次のように入力します。

    - **予測クローズ日:** 明日

    - **推定収益:** 70,000

12. 関係者サブグリッドで、Suzanne Burke が関係者として既に定義されているのに注目してください。 

13. On the Sales Team sub-grid, select the <bpt id="p1">**</bpt>Vertical Ellipsis<ept id="p1">**</ept>. From the menu that appears select <bpt id="p1">**</bpt>New Connection<ept id="p1">**</ept>. 

14. Search for and select your user record. Once completed, select the <bpt id="p1">**</bpt>Add<ept id="p1">**</ept> button. 

15. On the Competitors sub-grid, select the <bpt id="p1">**</bpt>Vertical Ellipsis<ept id="p1">**</ept>. From the menu that appears select <bpt id="p1">**</bpt>Add Existing Competitor<ept id="p1">**</ept>. 

16. **[レコードの検索]** 画面で、**[新しいレコード]** を選択し、**[競合企業]** を選択します。

17. **[競合企業の簡易作成]** 画面で、**[名前]** フィールドを **[Coho Technologies]** に設定します。

18. **[保存して閉じる]** ボタンを選択します。

19. <bpt id="p1">**</bpt>Coho Technologies<ept id="p1">**</ept> should be selected in the lookup record window. Select the <bpt id="p1">**</bpt>Add<ept id="p1">**</ept> button to finishing adding the competitor. 

20. **リードから営業案件**ビジネス プロセス フローで**開発**ステージを選択し、**関係者の特定**ステップと**競合企業の特定**ステップを両方とも**完了**に設定します。 

21. **[次のステージ]** ボタンを選択して**提案**ステージに進みます。

22. **提案**ステージで、4 つのステップすべてに**完了**をマークし、**[次のステージ]** ボタンを選択て**クローズ**ステージに進みます。 

23. **クローズ** ステージで、**[最終提案の完成]**、**[最終提案の表示]**、**[礼状の送信]**、**[報告の保存]** のステップを **[完了]** としてマークします。 

24. **決定日の確認**を**今日の日付**に設定します。 

25. **[完了]** をクリックします。 

26. この演習では、Jim Glynn という既存の顧客への営業案件を手動で取得します。 

27. **[営業案件のクローズ]** 画面で **[OK]** ボタンをクリックして営業案件レコードのクローズを完了します。 
