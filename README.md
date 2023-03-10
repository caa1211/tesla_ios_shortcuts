# tesla_ios_shortcuts

用於設定使用 siri 控制 Tesla，原理是使用 ios 原生的 `捷徑` 功能，操作 [非官方公開的API](https://tesla-api.timdorr.com)，設置時間約五分鐘以內。

```
說明: 
API 雖非官方公開，是利用官方App使用逆向工程找出來的，
有一定的安全性，但有因變動造成不支援的風險
```

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/tlp4nb-dsyU/0.jpg)](https://www.youtube.com/watch?v=tlp4nb-dsyU)

# 安裝與設置

1. 從 App Store 安裝  [Auth for Tesla](https://apps.apple.com/us/app/auth-app-for-tesla/id1552058613)

2. 安裝後，打開 Auth for Tesla，接著輪入特斯拉帳號密碼，登入後，離開即可

```
說明: 
1. 依照開發者的說明，帳碼密碼是直接輸入給Tesla網頁用於取得Token，並在Token過期前儲存至使用者的手機中，
   並沒有傳送給開發者。
   
2. 該App也已公開原始碼可供檢視(https://github.com/dburkland/tesla_ios_shortcuts)

3. 本文分享的捷徑皆使用 Auth for Tesla 取得 Toekn。

4. 因Token等於控制車輛的權限，若依然有安全性的疑慮，可使用下面reddit提供的捷徑，
   他的方法是在安裝捷徑時輸入帳號密碼，而在每次執行捷徑前都重新至Tesla登入拿Token，我預期速度較慢
   https://www.reddit.com/r/shortcuts/comments/9rmgn3/tesla_commands_shortcut/
```

# 匯入捷徑

1. 點擊下面連結匯入第一個捷徑

喚醒特斯拉
https://www.icloud.com/shortcuts/79739c7adad44340a543c4c219aefece

```
說明: 此為第一個需匯入的捷徑，其它捷徑會先判斷是否已喚醒，再接續執行
```

2. 匯入其它指令

打開車上空調 https://www.icloud.com/shortcuts/5c683d4f559d47899f928027594d9bcb

打開後車箱 https://www.icloud.com/shortcuts/1dfcb1a132064b82adaa2c20de6ac1d0

關閉後車箱 https://www.icloud.com/shortcuts/68523f080fa04f55bd0dbfa39bd39a41

打開前車箱 https://www.icloud.com/shortcuts/18752dd7393a4ddb999221665f608aea


```
說明: 打開後車箱捷徑其實等同關閉後車箱捷徑，開啟的狀態再執行一次開啟也會關閉，反之亦然，這有改善的空間
```


3. 先至捷徑App中手動執行，系統會跳出權限許可詢問，點擊許可

# 其它

1. 與此教學類似的分享公開捷徑: https://github.com/dburkland/tesla_ios_shortcuts

2. 預期會新增其它捷徑至此

3. 將可連動 NFC，手機觸碰即可執行，相關教學後續新增

4. 本教學僅供分享心得，請自負一切使用上的責任

# 關於我

* FB: caa1211
* Mail: caa1211@gmail.com
