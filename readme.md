# 標註您的驗證碼 (中文)

找了一些開源的標註驗證碼工具，發現有些工具還需處理跨平台問題。於是乾脆寫了一個網頁，可以直接用瀏覽器開啟 `label.html`，並且下載 csv 標註檔。

每 60 秒會自動儲存目前頁面到瀏覽器的 localStorage 為 cache。當整個完成時，就可以按 `Export as CSV` 按鈕下載 csv 標註檔。

> 因為把 cache 存在 localStorage，而 localStorage 儲存上限為 5MB，所以當標註的大小超過 5MB 時，會有問題。

# Label the captcha (English)

I've found some open-source label captcha tools, but it took me a lot of time to install on different OS platforms. Therefore I wrote a html (`label.html`), you can just open it with browser and start to label. After completing above steps, you can download this csv file.

The page will be saved to browser localStorage as cache every 60 seconds. When completing all labeling, just click `Export as CSV` button to download csv file.

> Due to save cache into localStorage, and localStorage has 5MB limitation. So it could has problem when labeling data size reaches 5MB.

# 截圖 (Screenshot)

Screenshot 1
![截圖1](image/image1.png)

Screenshot 2
![截圖2](image/image2.png)
