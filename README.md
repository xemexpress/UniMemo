# UniMemo 發掘順便

### TL;DR

以商品實付金額的10%作為酬勞，促成順便購物體驗。

### <u>Memo紙</u>

- 承諾按金
- 購買點
- 交收點
- 購買清單
- 交收時間

| 關鍵配套                    | 作用                                                         |
| --------------------------- | ------------------------------------------------------------ |
| 電子錢包`&`支付中介         | <u>建立信任</u>。提供安心墊支的合作前提。                    |
| 隱匿電話號碼                | <u>尊重私隱</u>。確保個人資料時刻保密。                      |
| 雙向評準                    | <u>重視意見</u>。低評的互動會被紀錄，而相關用戶將可能被移除。 |
| 實時定位`&`預設常到時間地點 | <u>連接順便</u>。搜尋最相關的Memo。                          |



### <u>反思回顧</u>

在社會廣泛實踐「順便」的關鍵在於建立基礎信任及提供有效動機。



___





### 詳細版本

### <u>Memo紙</u>

##### 作為接單人，以商品實付金額的10%作為酬勞，順便幫人買東西。

用戶開啓程式後，程式獲取用戶的實時定位，以用戶所在位置及預設常到地點作為*購買點*、以預設常到地點及時段作為*交收點*和*交收時間*，自動搜尋相關的Memo。每張Memo均有相應的*承諾按金*讓用戶放心墊支。用戶確認Memo後便可按要求（包括*購買點*、*交收點*、*交收時間*及*購買清單*）執行。雙方順利交收後，出單人輸入支付密碼確認支付購物收據中相關商品的總墊支額及總墊支額之10%，然後向用戶取貨。

##### 作為出單人，以商品實付金額的10%作為酬勞，讓順路的人幫你買東西。

Memo內容分爲五項：承諾按金、購買點、交收點、購買清單、交收時間。

#### 承諾按金

承諾按金是出單人在出單前已支付的、承諾能夠支付接單人的最高金額，用於<u>支付購物收據中相關商品的總墊支額及總墊支額之10%</u>。按金數額是<u>根據出單人在購物清單內各商品單項的總預算再加上總預算之10%</u>計算而來，不可低於應付款項，否則Memo隨即失效。

```markdown
承諾按金的金額僅出單人可見。接單人在選購目標商品單項時需在程式中（終以購物收據為準）紀錄實付單價，系統即時後台覆核其承諾按金是否充足。若承諾按金足夠，則反映出單人有能力支付此項商品。若承諾按金不足，相關商品單項及接單人的執行確認將隨即失效。
```

出單前，承諾按金會<u>從出單人的電子錢包中扣除</u>。<u>沒有出單人的批准，接單人絕不會收到承諾按金。</u>潛在接單人在根據清單購買前須<u>對目標商品單項成功進行「確認」</u>成為<u>唯一接單人</u>，確保其墊支會受到按金機制的保障。雙方順利交收後，出單人輸入<u>支付密碼</u>、以承諾按金向接單人確認支付應付款項，（如有）剩餘按金將立即返還至出單人的電子錢包。

若交收時發生以下情況，出單人有權決定是否繼續為商品支付：

1. 接單人未能<u>提供實物收據</u>。
2. 接單人未能交付<u>購買清單指定</u>的商品，例如要A但買了B等。
3. 接單人未能交付<u>包裝完好無缺</u>的商品，例如包裝曾被開啟或破裂。

若出單人不向接單人確認支付，接單人則無須交付相關商品。



#### 購買點

購買點與<u>實時定位或預設常到地點</u>相近時，用戶才會接收到Memo。



#### 交收點

交收點與<u>預設常到地點</u>相近時，用戶才會接收到Memo。用戶可自行預設多個常到地點以增加收到相關Memo的機會。



#### 交收時間

交收時間與預設常到地點之方便時段相符時，用戶才會接收到Memo。



#### 購買清單

購買清單<u>只建議經標準化生產或有密封包裝的商品，不包括經即場製作的熟食外賣類、蔬菜類、生果類、海鮮類、鮮肉類、需恆低溫儲存的奶製品和豆製品商品</u>。



### <u>關鍵配套</u>

#### 電子錢包

讓出單人與接單人之間能輕鬆轉帳付款。



#### 支付中介

輔助處理承諾按金的轉帳交接，為求在用戶之間建立基礎信任，提供接單人放心墊支的前提。



#### 隱匿電話號碼

在出單人與接單人透過文字、圖像、語音短訊及即時語音進行溝通的同時，不顯示雙方之個人電話號碼資料。



#### 雙向評準

營造良好的社群氣氛。系統將紀錄評價，在用戶互動時提供參考。

| 類別          | 出單人        | 接單人        |
| ------------ | ------------ | ------------ |
| 評分（1-5）   | 面交順暢準時   | 支付順暢無拖延  |
|              | 商品與要求一致 | 面交順暢準時    |
|              | 大致交談友善   | 大致交談友善    |
| 評論          | √            | √             |

另外，出單人和接單人分別可應情況取消Memo和撤銷其執行確認，唯須紀錄原因作參考。

| 出單人之取消原因                            | 接單人之撤銷原因                            |
| ------------------------------------------- | ------------------------------------------- |
| 不想要該商品                                | 品類不存在                                  |
| 已自行處理                                  | 商品已售罄                                  |
| 欲取回按金                                  | 現金/餘額不足                               |
| 其他：_____________________________________ | 行程變更                                    |
| -                                           | 其他：_____________________________________ |



#### 實時定位

系統自動列出購買點與用戶位置相近的Memo。



#### 預設常到地點

用戶可預先提供最多5處常到地點。系統自動列出交收點與用戶常到地點相近的Memo。



### <u>盈利模式</u>

#### 地域廣告

系統根據用戶的實時定位在程式首頁展示最相關的產品廣告。