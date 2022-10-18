---
lab:
  title: 'ラボ 4.2:Dynamics 365 Field Service でアイテムをスケジュールする'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
---

<a name="module-4-learn-the-fundamentals-of-dynamics-365-field-service"></a>モジュール 4: Dynamics 365 Field Service の基礎について学習する
========================

## <a name="practice-lab-42---schedule-items-in-dynamics-365-field-service"></a>実践ラボ 4.2 - Dynamics 365 Field Service でアイテムをスケジュールする

## <a name="lab-setup"></a>ラボのセットアップ

  - **推定時間**:20 分

  **注:** Internet Explorer で [予約要件] ペインを開くことはできません。 この演習を完了するために、Microsoft Edge または Google Chrome を使用してください。
  
## <a name="instructions"></a>Instructions

1.  まだ開いていない場合、**Dynamics 365 Field Service** アプリケーションを開きます。  

2.  左側のナビゲーションを使用して、**[作業指示書]** を選択します。

3.  **コマンド バー**で、**[新規]** を選択して、新しい作業指示書を作成します。

4.  次のように作業指示書の詳細を入力します。
    - サービス アカウント:ADatum Corporation
    - プライマリ インシデントの種類:MRI スキャナーのダウン
    - 課税対象: いいえ
    - **[保存して閉じる]** を選択して変更を保存し、新しい作業指示書を終了します。
    - **作業指示書**の**コマンド バー**で **[予約]** ボタンを選択します。
    
5.  これにより、**スケジュール アシスタント**が開きます。

6.  アイテムをスケジュールするためのオプションが表示されます。  **Ryan Brim** のレコードを選択します。  

7.  **[ソース予約の作成]** ウィンドウで、**開始時刻**を**次の 1 時間の先頭**に設定します。  **終了時間**をその 2.5 時間後に設定します。

8.  **[予約して終了]** ボタンを選択してアイテムを予約し、スケジュール ウィンドウを終了します。

9.  作業指示書に戻ったら、**コマンド バー**の **[保存して閉じる]** ボタンをクリックします。  

10. 左側のナビゲーションを使用して、**[スケジュール ボード]** を選択します。  

11. 要件パネルの画面下部で、**[スケジュールされていない作業指示書]** を選択します。  

12. 書き留めた作業指示番号を使用して、以前に作成した **Adventure Works** の作業指示書を選択します。

13. 表示されるオプションから、**[空き時間の検索]** を選択します。

14. これにより、**スケジュール アシスタント**が開きます。 アイテムをスケジュールするためのオプションが表示されます。  

15. Bob Kozak のレコードを選択します。  

16. **[ソース予約の作成]** ウィンドウで、**開始時刻**を**次の 1 時間の先頭**に設定します。  **終了時間**をその 2.5 時間後に設定します。

17. **[予約して終了]** ボタンを選択してアイテムを予約し、スケジュール ウィンドウを終了します。

18. 場合によっては、技術者の競合やその他の項目に基づいて作業指示書を再スケジュールする必要があります。
  
19. これは、スケジュール ボードを活用する派遣担当者によって簡単に実行できます。 

20. スケジュール ボードの [リソースの検索] ボックス (リソース名列のすぐ上にあります) をクリックし、「Ryan」と入力して、本日遅くに Ryan にスケジュールされている作業指示書を見つけます。  作業指示書を右クリックし、表示されるメニューから **[代替リソース]** を選択し、 **[代替リソースの検索]** ボタンを選択します。  

21. Click in search resources box on the schedule board (Located right above the resource name column), enter Ryan and locate the work order that is scheduled for Ryan later today.  

22. Right-click on the work order, and from the menu that appears, select <bpt id="p1">**</bpt>Substitute Resource<ept id="p1">**</ept>, select the <bpt id="p2">**</bpt>Find Substitution<ept id="p2">**</ept> button.


