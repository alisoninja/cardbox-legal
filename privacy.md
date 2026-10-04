---
title: 名片盒 CardBox 隱私權政策 / Privacy Policy
---

# 名片盒 CardBox 隱私權政策 / Privacy Policy

> 生效日期 / Effective date: 2026-10-01
> 適用產品：名片盒 CardBox（iOS）
> 開發者聯絡方式 / Contact: alicexhaha@gmail.com

---

## 繁體中文

### 一、我們不收集你的資料

名片盒是一款「資料留在你手上」的名片管理 App：

- **沒有帳號系統後端**：你掃描與建立的所有名片資料（姓名、電話、Email、地址、公司、職稱、名片影像、備註、地圖座標）只儲存在你的裝置本機。
- **沒有我們的伺服器**：App 不會把任何資料傳送到開發者的伺服器——我們根本沒有伺服器。名片文字辨識（OCR）完全在裝置上執行（Apple Vision framework），影像不會離開你的裝置。
- **一個例外，先講清楚**：如果你使用「人脈地圖」並明示同意，App 會把名片上的**地址與城市文字**傳送給 Apple 的地理編碼服務（CLGeocoder）換算成座標。詳見下方第三節。
- **沒有追蹤與分析**：App 不含任何廣告 SDK、分析工具或崩潰回報服務，不會建立廣告識別碼，也不會跨 App 追蹤你。

### 二、iCloud 同步（Pro 功能，可選）

若你訂閱 Pro 並啟用 iCloud 同步，名片資料會透過 Apple CloudKit 儲存在**你個人的 iCloud 私人資料庫**中，用於你自己裝置間的同步與備份。該資料庫由 Apple 依其隱私權政策保護，**開發者無法存取、讀取或還原其中任何內容**。你可以隨時在 iOS「設定 → Apple 帳號 → iCloud」中管理或刪除 iCloud 資料。

### 三、人脈地圖與 Apple 地理編碼（唯一的對外傳送）

「人脈地圖」把有地址的名片標在地圖上。要做到這件事，必須先把地址換成經緯度座標，而這個換算由 Apple 的地理編碼服務（`CLGeocoder`）完成，**不是在你的裝置上算出來的**。因此：

- **會送出什麼**：只有名片的「地址」與「城市」欄位文字。姓名、電話、Email、職稱、公司、名片影像、備註都不會送出。
- **什麼時候送**：只在你開啟人脈地圖、而且已經在說明頁上明示同意之後。首次開啟地圖時 App 會先顯示說明並讓你選擇。
- **誰收到**：Apple。此項傳送適用 Apple 的隱私權政策；地圖圖資同樣由 Apple 提供。開發者不會收到、也看不到這些查詢。
- **會不會重複送**：換算結果會存在該張名片上，同一個地址不會重複送出；你修改地址後才會重新換算。
- **不同意會怎樣**：地圖仍可開啟，只會顯示先前已換算過的地點，不會發出任何請求。你可以隨時在「設定 → 進階 → 地圖：傳送地址給 Apple」更改這個選擇。

**除了上述地理編碼之外**，App 不會把任何名片資料傳送給開發者，也不會傳送給其他任何對象。

### 四、權限用途

| 權限 | 用途 |
|---|---|
| 相機 | 拍攝名片進行掃描辨識 |
| Face ID／裝置密碼 | 開啟 App 鎖、以及刪除資料前的確認 |

從相簿選取照片走系統的照片選擇器（PHPicker），在 App 之外執行，**不需要相簿權限**；App 也沒有寫回相簿的功能。人脈地圖不使用你的所在位置，因此不要求定位權限。所有權限僅在你使用對應功能時才會請求；拒絕權限不影響其他功能使用。

### 五、購買資訊

訂閱與買斷購買完全由 Apple App Store（StoreKit）處理。我們只會收到 Apple 提供的匿名交易憑證以解鎖 Pro 功能，**不會取得**你的姓名、Apple 帳號、信用卡或帳單資訊。

### 六、資料匯出

你可以隨時將名片資料匯出為 vCard 或 CSV（Excel）檔案，完整帶著走，不受任何形式綁架。請注意：匯出內容來自名片影像的自動辨識（OCR），屬**未經人工驗證的第三方文字**；若要將匯出檔案餵入自動化流程或 AI 工作流程，請先以不可信資料的態度處理（例如先人工檢查、或對匯入的欄位做額外驗證），避免辨識誤差被當成正確資料使用。

### 七、資料刪除

- 在 App 內刪除聯絡人會一併永久刪除其名片影像與相關資料。
- 刪除 App 即刪除所有本機資料。**刪除前請先使用「備份到檔案」或「匯出聯絡人」保存資料**——備份檔存放在 App 之外（如「檔案」App／iCloud Drive），不會隨 App 一起刪除。
- iCloud 中的同步資料可於 iOS 設定中的 iCloud 管理介面移除。

### 八、兒童隱私

本 App 非以未滿 13 歲兒童為對象，且因不收集任何個人資料，不涉及兒童個資處理。

### 九、政策變更

若未來功能改變導致資料處理方式改變（例如新增雲端服務），我們會更新本政策並在 App 內告知。重大變更不會在未告知的情況下生效。

### 十、聯絡我們

隱私相關問題請來信：alicexhaha@gmail.com

---

## English

### 1. We don't collect your data

CardBox is a business-card manager where your data stays with you:

- **No backend, no accounts**: everything you scan or create (names, phone numbers, emails, addresses, companies, titles, card images, notes, map coordinates) is stored locally on your device only.
- **No servers of ours**: the app never sends any data to the developer — we run no servers at all. Card text recognition (OCR) runs entirely on-device using Apple's Vision framework; images never leave your device.
- **One exception, stated up front**: if you use the Contact Map and explicitly consent, the app sends the **address and city text** on your cards to Apple's geocoding service (CLGeocoder) to convert them into coordinates. See section 3 below.
- **No tracking or analytics**: the app contains no ad SDKs, analytics, or crash-reporting services, creates no advertising identifiers, and does not track you across apps.

### 2. iCloud sync (optional, Pro)

If you subscribe to Pro and enable iCloud sync, your card data is stored via Apple CloudKit in **your personal private iCloud database**, solely to sync and back up across your own devices. It is protected by Apple under Apple's privacy policy, and **the developer cannot access, read, or restore any of it**. You can manage or delete iCloud data anytime in iOS Settings → Apple Account → iCloud.

### 3. Contact Map and Apple geocoding (the only outbound transfer)

The Contact Map plots cards that have an address. Doing so requires converting each address into coordinates, and that conversion is performed by Apple's geocoding service (`CLGeocoder`) — **it is not computed on your device**. Therefore:

- **What is sent**: only the address and city fields of a card. Names, phone numbers, emails, titles, companies, card images, and notes are never sent.
- **When it is sent**: only when you open the Contact Map, and only after you have explicitly consented on the explanation screen shown the first time you open it.
- **Who receives it**: Apple. This transfer is subject to Apple's privacy policy; map tiles are likewise served by Apple. The developer never receives or sees these lookups.
- **Repeat lookups**: the result is stored on the card, so the same address is not sent again unless you edit it.
- **If you decline**: the map still opens and shows locations that were converted previously; no requests are made. You can change this at any time in Settings → Advanced → "Map: send addresses to Apple".

**Apart from the geocoding described above**, the app sends no card data to the developer or to anyone else.

### 4. Permissions

| Permission | Purpose |
|---|---|
| Camera | Capturing business cards for scanning |
| Face ID / device passcode | Unlocking the app lock and confirming destructive actions |

Picking photos uses the system photo picker (PHPicker), which runs outside the app and **requires no photo library permission**; the app also has no "save to Photos" feature. The Contact Map does not use your location, so no location permission is requested. Permissions are requested only when you use the corresponding feature; declining a permission does not affect other features.

### 5. Purchases

Subscriptions and one-time purchases are handled entirely by the Apple App Store (StoreKit). We only receive Apple's anonymized transaction entitlement to unlock Pro features. We **never** receive your name, Apple Account, credit card, or billing details.

### 6. Data export

You can export your card data as vCard or CSV (Excel) files at any time, in full, with no lock-in. Please note: exported content comes from automated recognition (OCR) of card images and is **unverified third-party text**. Before feeding exported files into any automation or AI workflow, treat it as untrusted data (e.g., review it manually or validate the imported fields) so recognition errors aren't mistaken for verified facts.

### 7. Data deletion

- Deleting a contact in the app permanently deletes its card images and related data.
- Deleting the app deletes all local data. **Before deleting, use "Back Up to Files" or "Export Contacts" to save your data** — backup files live outside the app (e.g. in the Files app / iCloud Drive) and are not removed with it.
- Synced iCloud data can be removed via the iCloud management UI in iOS Settings.

### 8. Children's privacy

The app is not directed at children under 13 and, as it collects no personal data, does not process children's data.

### 9. Changes to this policy

If future features change how data is handled (e.g., adding a cloud service), we will update this policy and notify you in the app before material changes take effect.

### 10. Contact

For privacy questions: alicexhaha@gmail.com
