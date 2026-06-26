# rime-opencc-cangjie5-qhmy-nbshq-filter
cangjie5 qhmy-nbshq filter - 基於rime適用於cangjie5倉頡五代的opencc拆解提示濾鏡

qhmy-nbshq(手竹一卜-弓月尸竹手: 拆解) 

基於輸入法引擎rime的倉頡5代輸入法(cangjie5)提供一個opencc拆解濾鏡。

以符合香港地區粵字混書面字習慣繁體中文常用字序排列，為約3450個的字提供拆解提示，以便幫助用家更好更快更入門倉頡5。

本詞本拆解通過手工編譯而成，因而絕對有誤請望見諒。

<p align="center">
<img src="https://raw.githubusercontent.com/yuOpghH/rime-opencc-cangjie5-qhmy-nbshq-filter/refs/heads/main/png/test.png"  style="width:380px;"/>
</p>

## 使用方法

- 使用方法。請確認你的rime載有[cangjie5](https://github.com/rime/rime-cangjie)方案(一般官方rime自帶)，[獲取rime](https://github.com/rime/weasel)
  - 通過右上角code鍵-download zip下載所有文檔並解壓。
  - 右鍵於windons下的任務列RIME圖標，選擇`程序文件夾`打開，點開data資料夾，將opencc資料夾內文檔複製至此。
  - 右鍵於windons下的任務列RIME圖標，選擇`用戶文件夾`打開，將文檔cangjie5.custom.yaml 複製至此。
  - 右鍵於windons下的任務列RIME圖標，重新布署，切換即可。
  - 預設關閉狀態，你可使用F4或者`ctrl+shift+c`切換


* 因註釋長度預設調整小字體註釋。

## 訂製化


- 如何設置預設開啟
  - 打開`用戶文件夾`內的cangjie5.custom.yaml，用記事本程式打開，修改    name: cangjie5_suggestion 下的 reset: 0, 由0改為1。設置是否預設開啟 0為預設關閉 1為預設開啟。

- 如何設置註釋大小
  - 打開`用戶文件夾`內的cangjie5.custom.yaml，用記事本程式打開，修改    ncomment_font_point: 12 。設置註釋字體大小。

- 如何適用我的個製方案
  - 將cangjie5.custom.yaml，前面部份更換成你所屬的方案即可，例如假設我一個名為"cangjie3"的方案，則改為cangjie3.custom.yaml
 
## 鳴謝

- [徐碼拆解濾鏡的啟發](https://github.com/forfudan/xuma)
