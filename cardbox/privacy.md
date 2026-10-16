---
title: 名片盒 CardBox 隱私權政策 / Privacy Policy
---

# 名片盒 CardBox 隱私權政策 / Privacy Policy

> 生效日期 / Effective date: 2026-10-07（前一版：2026-10-01）
> 適用產品：名片盒 CardBox（iOS）
> 開發者聯絡方式 / Contact: alicexhaha@gmail.com

---

## 繁體中文

### 一、我們不收集你的資料

名片盒是一款「資料留在你手上」的名片管理 App：

- **沒有帳號系統後端**：你掃描與建立的所有名片資料（姓名、電話、Email、地址、公司、職稱、名片影像、備註、地圖座標）儲存在你的裝置本機。另有兩種情況會有副本在裝置之外：Pro 的 iCloud 同步（第二節），以及 iOS 本身的系統備份（第四節）。
- **沒有我們的伺服器**：App 不會把任何資料傳送到開發者的伺服器——我們根本沒有伺服器。名片文字辨識（OCR）完全在裝置上執行（Apple Vision framework），影像不會離開你的裝置。
- **會把資料交出裝置的功能，先講清楚**：人脈地圖（經你同意後把地址交給 Apple 換算座標，見第三節）、在名片上點地址開 Apple 地圖、以及用 LINE 傳送問候語（見第四節）。這些都不經過我們，我們也收不到。
- **沒有追蹤與分析**：App 不含任何廣告 SDK、分析工具或崩潰回報服務，不會建立廣告識別碼，也不會跨 App 追蹤你。

### 二、iCloud 同步（Pro 功能，可選）

若你訂閱 Pro，且裝置已登入 iCloud，名片資料會自動透過 Apple CloudKit 儲存在**你個人的 iCloud 私人資料庫**中，用於你自己裝置間的同步與備份。該資料庫由 Apple 依其隱私權政策保護，**開發者無法存取、讀取或還原其中任何內容**。App 內沒有單獨關閉同步的開關；你可以在 iOS「設定 → Apple 帳號 → iCloud」中管理或刪除 iCloud 資料。名片影像與頭像不參與同步。

### 三、人脈地圖與 Apple 地理編碼

「人脈地圖」把有地址的名片標在地圖上。要做到這件事，必須先把地址換成經緯度座標，而這個換算由 Apple 的地理編碼服務（`CLGeocoder`）完成，**不是在你的裝置上算出來的**。因此：

- **會送出什麼**：只有名片的「地址」與「城市」欄位文字。姓名、電話、Email、職稱、公司、名片影像、備註都不會送出。
- **什麼時候送**：只在你開啟人脈地圖、而且已經在說明頁上明示同意之後。首次開啟地圖時 App 會先顯示說明並讓你選擇。
- **誰收到**：Apple。此項傳送適用 Apple 的隱私權政策；地圖圖資同樣由 Apple 提供。開發者不會收到、也看不到這些查詢。
- **會不會重複送**：換算結果會存在該張名片上，同一個地址不會重複送出；你修改地址後才會重新換算。
- **不同意會怎樣**：地圖仍可開啟，只會顯示先前已換算過的地點，不會再送出任何地址。但地圖圖資仍會向 Apple 請求——Apple 因此會知道你正在看哪一帶的地圖，不過收不到任何名片內容。你可以隨時在「設定 → 進階 → 地圖：傳送地址給 Apple」更改這個選擇。

### 四、其他會讓資料離開裝置的情況

以下情況資料會離開你的裝置，但**都不會送到開發者手上**：

- **在名片上點「地址」開 Apple 地圖**：完整地址會傳送給 Apple 進行地圖搜尋。若你沒有在上一節同意「傳送地址給 Apple」，App 每次都會先跳出確認。
- **用 LINE 傳送問候語**：整段問候語（包含對方的姓名、職稱、公司，以及你的署名）會交給 **LINE（LY Corporation）**，適用 LINE 的隱私權政策。LINE 是 Apple 以外的第三方，送出前 App 會先跳出確認。未安裝 LINE 時，內容會經由 Safari 送到 LINE 的網站。
- **用 Email、簡訊或系統分享面板分享**：內容會交給你選擇的 App（郵件、訊息、AirDrop、檔案 App 等），由你在那裡決定是否送出。
- **iOS 系統備份**：如果你開啟了 iOS 的 iCloud 備份，或用電腦（Finder／iTunes）備份 iPhone，名片盒的資料（名片欄位、名片影像、頭像、設定）會依 iOS 的機制包含在那份備份中。這由 iOS 設定控制，與是否為 Pro、是否開啟 iCloud 同步無關。恢復密碼不會進入備份。
- **App Store 查詢**：每次開啟 App 時，App 會向 Apple App Store 查詢商品價格與你的訂閱狀態，以確認 Pro 是否有效。這不含任何名片資料。
- **Sign in with Apple（選用）**：你主動登入時，Apple 會提供識別碼，以及你選擇分享的姓名與 Email；這些存在你裝置的 Keychain 中（會隨 iOS 系統備份一起備份），我們沒有接收它們的伺服器。
- **隱私政策連結**：點開本政策時，你的瀏覽器會向本頁的託管服務（GitHub Pages）發出一般網頁請求。

### 五、權限用途

| 權限 | 用途 |
|---|---|
| 相機 | 拍攝名片進行掃描辨識 |
| Face ID／裝置密碼 | 開啟 App 鎖、以及刪除資料前的確認 |

從相簿選取照片走系統的照片選擇器（PHPicker），在 App 之外執行，**不需要相簿權限**；App 也沒有寫回相簿的功能。人脈地圖不使用你的所在位置，因此不要求定位權限。所有權限僅在你使用對應功能時才會請求；拒絕權限不影響其他功能使用。

### 六、購買資訊

訂閱與買斷購買完全由 Apple App Store（StoreKit）處理。App 只會在你的裝置上向 Apple 確認交易與訂閱狀態以解鎖 Pro 功能；開發者**不會取得**你的姓名、Apple 帳號、信用卡或帳單資訊。

### 七、資料匯出

你可以隨時將名片資料匯出為 vCard 或 CSV（Excel）檔案，完整帶著走，不受任何形式綁架。請注意：匯出內容來自名片影像的自動辨識（OCR），屬**未經人工驗證的第三方文字**；若要將匯出檔案餵入自動化流程或 AI 工作流程，請先以不可信資料的態度處理（例如先人工檢查、或對匯入的欄位做額外驗證），避免辨識誤差被當成正確資料使用。

### 八、資料刪除

- 在 App 內刪除聯絡人會一併永久刪除其名片影像與相關資料。
- 刪除 App 即刪除所有本機資料。**刪除前請先使用「備份到檔案」或「匯出聯絡人」保存資料**——備份檔存放在 App 之外（如「檔案」App／iCloud Drive），不會隨 App 一起刪除。
- iCloud 中的同步資料可於 iOS 設定中的 iCloud 管理介面移除。
- iOS 系統備份（iCloud 備份或電腦備份）中既有的副本不會因為在 App 內刪除而消失，需在 iOS 設定或電腦上管理那些備份。

### 九、兒童隱私

本 App 非以未滿 13 歲兒童為對象，且因不收集任何個人資料，不涉及兒童個資處理。

### 十、政策變更

若未來功能改變導致資料處理方式改變（例如新增雲端服務），我們會更新本政策並在 App 內告知。重大變更不會在未告知的情況下生效。

### 十一、聯絡我們

隱私相關問題請來信：alicexhaha@gmail.com

---

## English

### 1. We don't collect your data

CardBox is a business-card manager where your data stays with you:

- **No backend, no accounts**: everything you scan or create (names, phone numbers, emails, addresses, companies, titles, card images, notes, map coordinates) is stored locally on your device. Copies exist outside the device in two cases: Pro iCloud sync (section 2) and iOS's own device backups (section 4).
- **No servers of ours**: the app never sends any data to the developer — we run no servers at all. Card text recognition (OCR) runs entirely on-device using Apple's Vision framework; images never leave your device.
- **Features that hand data off your device, stated up front**: the Contact Map (with your consent, sends addresses to Apple for coordinates — see section 3), tapping an address to open Apple Maps, and sending a greeting via LINE (see section 4). None of these go through us, and we never receive the data.
- **No tracking or analytics**: the app contains no ad SDKs, analytics, or crash-reporting services, creates no advertising identifiers, and does not track you across apps.

### 2. iCloud sync (optional, Pro)

If you subscribe to Pro and your device is signed in to iCloud, your card data is automatically stored via Apple CloudKit in **your personal private iCloud database**, solely to sync and back up across your own devices. It is protected by Apple under Apple's privacy policy, and **the developer cannot access, read, or restore any of it**. There is no separate in-app switch to turn sync off; you can manage or delete iCloud data in iOS Settings → Apple Account → iCloud. Card images and avatars are not synced.

### 3. Contact Map and Apple geocoding

The Contact Map plots cards that have an address. Doing so requires converting each address into coordinates, and that conversion is performed by Apple's geocoding service (`CLGeocoder`) — **it is not computed on your device**. Therefore:

- **What is sent**: only the address and city fields of a card. Names, phone numbers, emails, titles, companies, card images, and notes are never sent.
- **When it is sent**: only when you open the Contact Map, and only after you have explicitly consented on the explanation screen shown the first time you open it.
- **Who receives it**: Apple. This transfer is subject to Apple's privacy policy; map tiles are likewise served by Apple. The developer never receives or sees these lookups.
- **Repeat lookups**: the result is stored on the card, so the same address is not sent again unless you edit it.
- **If you decline**: the map still opens and shows locations that were converted previously, and no further addresses are sent. Map tiles are still requested from Apple, so Apple can tell which area of the map you are viewing, but it receives no card details. You can change this at any time in Settings → Advanced → "Map: send addresses to Apple".

### 4. Other ways data leaves your device

In the following cases data leaves your device, but **none of it is sent to the developer**:

- **Tapping an address on a card to open Apple Maps**: the full address is sent to Apple to search in Maps. If you have not agreed to "send addresses to Apple" (section 3), the app asks for confirmation every time.
- **Sending a greeting via LINE**: the full greeting — including the recipient's name, title and company, and your signature — is handed to **LINE (LY Corporation)** under LINE's privacy policy. LINE is a third party other than Apple, and the app asks for confirmation before sending. If LINE isn't installed, the text is sent to LINE's website through Safari.
- **Sharing via Email, Messages or the system share sheet**: content goes to the app you choose (Mail, Messages, AirDrop, Files, etc.), where you decide whether to send it.
- **iOS device backups**: if you use iOS iCloud Backup, or back up your iPhone to a computer (Finder / iTunes), CardBox data (card fields, card images, avatars, settings) is included in that backup by iOS. This is controlled by your iOS settings and is independent of Pro or iCloud sync. Your recovery password is never included in backups.
- **App Store checks**: each time the app opens, it asks the Apple App Store for product prices and your subscription status to confirm whether Pro is active. No card data is included.
- **Sign in with Apple (optional)**: when you choose to sign in, Apple provides an identifier and the name and email you choose to share; these are stored in your device's Keychain (and included in iOS device backups), and we have no server to receive them.
- **Privacy policy link**: opening this policy makes an ordinary web request from your browser to the page's host (GitHub Pages).

### 5. Permissions

| Permission | Purpose |
|---|---|
| Camera | Capturing business cards for scanning |
| Face ID / device passcode | Unlocking the app lock and confirming destructive actions |

Picking photos uses the system photo picker (PHPicker), which runs outside the app and **requires no photo library permission**; the app also has no "save to Photos" feature. The Contact Map does not use your location, so no location permission is requested. Permissions are requested only when you use the corresponding feature; declining a permission does not affect other features.

### 6. Purchases

Subscriptions and one-time purchases are handled entirely by the Apple App Store (StoreKit). The app only checks your transactions and subscription status with Apple, on your device, to unlock Pro features. The developer **never** receives your name, Apple Account, credit card, or billing details.

### 7. Data export

You can export your card data as vCard or CSV (Excel) files at any time, in full, with no lock-in. Please note: exported content comes from automated recognition (OCR) of card images and is **unverified third-party text**. Before feeding exported files into any automation or AI workflow, treat it as untrusted data (e.g., review it manually or validate the imported fields) so recognition errors aren't mistaken for verified facts.

### 8. Data deletion

- Deleting a contact in the app permanently deletes its card images and related data.
- Deleting the app deletes all local data. **Before deleting, use "Back Up to Files" or "Export Contacts" to save your data** — backup files live outside the app (e.g. in the Files app / iCloud Drive) and are not removed with it.
- Synced iCloud data can be removed via the iCloud management UI in iOS Settings.
- Existing copies in iOS device backups (iCloud Backup or computer backups) are not removed by deleting data in the app; manage those backups in iOS Settings or on your computer.

### 9. Children's privacy

The app is not directed at children under 13 and, as it collects no personal data, does not process children's data.

### 10. Changes to this policy

If future features change how data is handled (e.g., adding a cloud service), we will update this policy and notify you in the app before material changes take effect.

### 11. Contact

For privacy questions: alicexhaha@gmail.com
