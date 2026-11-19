# 她的第二人生 HER SECOND SPRING

更年期健康與生活陪伴站（靜態網站原型）。

## 網站內容

- 更年期相關症狀百科與健康教育資訊
- 情緒照顧與家庭溝通指南
- 女性互助及興趣資源外部連結
- 簡易健康／心情記錄
- 主題色、字體與背景自訂
- 知心姐姐聊天介面（目前為預設回覆演示，尚未連接真實 AI）

## 發布方式

本專案使用 GitHub Pages。請到 repository 的 **Settings → Pages → Build and deployment**，將 **Source** 設為 **GitHub Actions**。之後推送至 `main` 分支會自動部署。

## 重要限制與隱私提醒

- 本網站是一般健康教育與生活資訊原型，不能取代醫師診斷、治療或心理服務。
- 聊天介面目前僅提供預設規則回覆，並非 ChatGPT，也不會呼叫任何 AI API。
- 健康記錄與主題偏好使用瀏覽器 `localStorage`，資料只保存在使用者目前的瀏覽器，不會自動同步到雲端。清除瀏覽器資料可能造成紀錄遺失。
- 不要在公開電腦輸入敏感個人資料。不要在前端程式碼中放置 API Key、密碼或任何祕密。
- GitHub 公開 repository 的原始碼會對所有人可見。發布前請確認檔案中沒有私人資料或憑證。

## 主要參考來源

- WHO：<https://www.who.int/zh/news-room/fact-sheets/detail/menopause>
- NICE NG23：<https://www.nice.org.uk/guidance/ng23/chapter/Recommendations>
- NHS：<https://www.nhs.uk/conditions/menopause-and-perimenopause/symptoms/>
- 台灣國民健康署：<https://www.hpa.gov.tw/Pages/List.aspx?nodeid=218>
- The Menopause Society：<https://menopause.org/patient-education/menopause-topics>
