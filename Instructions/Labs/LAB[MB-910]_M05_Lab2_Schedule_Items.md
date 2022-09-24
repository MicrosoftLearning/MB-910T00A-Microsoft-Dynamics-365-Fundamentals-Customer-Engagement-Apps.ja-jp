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

  <bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> The Booking Requirements pane cannot be opened in Internet Explorer. Please use Microsoft Edge or Google Chrome to complete this exercise.
  
## <a name="instructions"></a>Instructions

1.  まだ開いていない場合、**Dynamics 365 Field Service** アプリケーションを開きます。  

2.  左側のナビゲーションを使用して、**[作業指示書]** を選択します。

3.  **コマンド バー**で、**[新規]** を選択して、新しい作業指示書を作成します。

4.  次のように作業指示書の詳細を入力します。
    - サービス アカウント:ADatum Corporation
    - プライマリ インシデントの種類:MRI スキャナーのダウン
    - 課税対象: いいえ
    
5.  **[保存して閉じる]** を選択して変更を保存し、新しい作業指示書を終了します。

6.  On the <bpt id="p1">**</bpt>Command Bar<ept id="p1">**</ept> of the <bpt id="p2">**</bpt>Work Order<ept id="p2">**</ept>, select the <bpt id="p3">**</bpt>Book<ept id="p3">**</ept> button.  This will open the <bpt id="p1">**</bpt>Schedule Assistant<ept id="p1">**</ept>.  

7.  You should be presented with options for scheduling the item.  Select the <bpt id="p1">**</bpt>Ryan Brim<ept id="p1">**</ept> record.

8.  **[ソース予約の作成]** ウィンドウで、**開始時刻**を**次の 1 時間の先頭**に設定します。

9.  **終了時間**をその 2.5 時間後に設定します。  

10. **[予約して終了]** ボタンを選択してアイテムを予約し、スケジュール ウィンドウを終了します。  

11. 作業指示書に戻ったら、**コマンド バー**の **[保存して閉じる]** ボタンをクリックします。  

12. 左側のナビゲーションを使用して、**[スケジュール ボード]** を選択します。

13. 要件パネルの画面下部で、**[スケジュールされていない作業指示書]** を選択します。

14. Select the <bpt id="p1">**</bpt>Adventure Works<ept id="p1">**</ept> Work Order you created earlier use the work order number you wrote down. From the options that appear select <bpt id="p1">**</bpt>Find Availability<ept id="p1">**</ept>.  

15. これにより、**スケジュール アシスタント**が開きます。  

16. You should be presented with options for scheduling the item.  Select the Bob Kozak record.

17. **[ソース予約の作成]** ウィンドウで、**開始時刻**を**次の 1 時間の先頭**に設定します。

18. **終了時間**をその 2.5 時間後に設定します。
  
19. **[予約して終了]** ボタンを選択してアイテムを予約し、スケジュール ウィンドウを終了します。 

20. At times, you may need to reschedule a work order based on technician conflicts or other items.  This can be easily done by dispatchers leveraging the schedule board.  

21. スケジュール ボードの [リソースの検索] ボックス (リソース名列のすぐ上にあります) をクリックし、「Ryan」と入力して、本日遅くに Ryan にスケジュールされている作業指示書を見つけます。  

22. 作業指示書を右クリックし、表示されるメニューから **[代替リソース]** を選択し、 **[代替リソースの検索]** ボタンを選択します。


