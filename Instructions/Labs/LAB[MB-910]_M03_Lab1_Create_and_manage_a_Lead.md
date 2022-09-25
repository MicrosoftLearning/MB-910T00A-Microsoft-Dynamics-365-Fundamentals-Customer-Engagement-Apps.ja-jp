---
lab:
  title: 'ラボ 3.1:Dynamics 365 Sales のリードの作成と管理'
  module: 'Module 3: Learn the Fundamentals of Dynamics 365 Sales'
---

<a name="module-3-learn-the-fundamentals-of-dynamics-365-sales"></a>モジュール 3:Dynamics 365 Sales の基礎を学ぶ
========================

## <a name="practice-lab-31---create-and-manage-a-lead-in-dynamics-365-sales"></a>実践ラボ 3.1 - Dynamics 365 Sales のリードの作成と管理

## <a name="objectives"></a>目標

During this exercise, you will be capturing a sales lead for Suzanne Burke. She recently reached out to you and is interested in some of your organization’s products and services. Not only will you be capturing the lead in the system, but you will be using the tools available in Dynamics 365 Sales to work the lead through the qualification process.


## <a name="lab-setup"></a>ラボのセットアップ

  - **推定時間**:15 分

## <a name="instructions"></a>Instructions

1. まだ開いていない場合、**[Dynamics 365 営業ハブ]** アプリケーションを開きます。 

2. 画面の左側にあるナビゲーションを使用して、**[リード]** を選択します。 

3. **[自分のオープンしているリード]** ビューから、コマンド バーの **[新規]** ボタンを選択します。

4. 新しいリード レコードを次のように入力します。

    - **トピック:** 新しい機器を探しています - あなたのイニシャル

    - **First Name (名):** Suzanne

    - **Last Name (姓):** Burke

    - **役職:** CFO

    - **勤務先電話番号:** 888 555-8715

    - **電子メール:** Suzanne@contososample.com

    - **会社:** Contoso - ワシントン

    - **番地 1:** 1989 Smith Ave

    - **市区町村:** シアトル

    - **都道府県:** ワシントン州

    - **郵便番号:** 98001 

5. コマンド バーの **[保存]** ボタンを選択して、新しいリードを保存し、開いたままにします。

6. Notice the <bpt id="p1">**</bpt>Lead to Opportunity<ept id="p1">**</ept> Business Process Flow at the top of the record. Click the <bpt id="p1">**</bpt>Qualify Stage<ept id="p1">**</ept> to select it. Complete the stage as follows:

    - **購入期間:** 今四半期

    - **推定予算:** 25000 

    - **購入プロセス:** 個人

    - **意思決定者の特定:** 完了

7. 画面の中央にある **[レコード タイムライン]** に移動して、**[プラス記号アイコン]** をクリックし、新しい活動を追加します。 

8. 表示されるメニューで、**[電話]** を選択します。

9. **[電話の簡易作成]** 画面で、**[件名]** フィールドを **[最初の電話]** に設定し、残りの情報はそのままにしておきます。 

10. **[保存して閉じる]** ボタンをクリックします。

11. Notice the <bpt id="p1">**</bpt>Initial Phone Call<ept id="p1">**</ept> activity is now displayed on the <bpt id="p2">**</bpt>Record Timeline<ept id="p2">**</ept>. Hover over the activity and select the close activity <bpt id="p1">**</bpt>Check Mark Icon<ept id="p1">**</ept> to mark the phone call as completed. 

12. **[電話の終了]** ウィンドウで、**[終了]** ボタンを選択します 

13. Next you will qualify the lead record.  This will create a related Opportunity record and move to the next stage of the Lead to Opportunity sales process.  On the Command Bar, select the Qualify button.  

14. After the system qualifies the lead, a new <bpt id="p1">**</bpt>Opportunity<ept id="p1">**</ept> record will be created, and the business process will advance to the <bpt id="p2">**</bpt>Develop<ept id="p2">**</ept> stage.  Select the <bpt id="p1">**</bpt>Qualify<ept id="p1">**</ept> stage to view the original lead record. 

15. 営業案件に戻るには、**開発**ステージを選択します。

