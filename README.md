# NFC 數位名片網站

這是一個為NFC卡片設計的數位名片網站。當有人使用支援NFC的設備（如iPhone或Android手機）感應卡片時，會顯示這個網站，並讓訪客一鍵下載vCard格式的聯絡資訊或直接加入LINE好友。

## 檔案結構

- `index.html`: 主要網頁
- `styles.css`: 樣式表
- `hongshenglen.vcf`: vCard格式的聯絡人檔案 (iOS版本)
- `hongshenglen_android.vcf`: vCard格式的聯絡人檔案 (Android版本)
- `darren_photo.jpg`: 個人照片
- `README.md`: 本說明文件

## 設定NFC卡片的方法

### iPhone設定方式

1. 下載「快捷指令」應用程式（如果尚未安裝）
2. 創建一個新的自動化
3. 選擇「當NFC標籤被掃描」
4. 掃描您的NFC卡片
5. 添加「開啟URL」動作
6. 輸入您的網站URL（例如：https://hungdalun.github.io/vCard/）
7. 完成並儲存自動化

### 使用方式

當有人用手機感應您的NFC卡片時，手機將會自動開啟網頁瀏覽器並顯示您的數位名片。訪客可以：

1. 查看您的詳細資訊
2. 選擇適合自己手機的版本下載聯絡資料：
   - iOS用戶：點擊「iOS版聯絡資料」按鈕
   - Android用戶：點擊「Android版聯絡資料」按鈕
3. 點擊「加入LINE好友」按鈕，直接添加您為LINE好友

## 兩種vCard版本的差異

- **iOS版本**：提供更豐富的資訊，包含詳細的公司資訊、職稱、LINE連結和個人簡介。
- **Android版本**：提供簡化的基本資訊，優化了兼容性，確保Android設備能夠順利匯入聯絡資料。

## 部署說明

要使這個網站正常工作，您需要將所有檔案上傳到網站伺服器。您可以使用如下服務來部署：

- GitHub Pages（免費）
- Netlify（免費）
- Vercel（免費）
- 或任何其他網站主機

## 自定義

如需更改網站外觀或內容：

- 編輯 `index.html` 修改網站內容
- 編輯 `styles.css` 修改網站樣式
- 編輯 `hongshenglen.vcf` 和 `hongshenglen_android.vcf` 修改vCard聯絡人資訊 