# OneShot-TraditionalChinese-Translate

[OneShot](https://store.steampowered.com/app/420530/OneShot/) 中文正體/繁體模組

--------

[![OneShot](OneShot.png)](https://oneshot.fandom.com/zh/wiki/OneShot)

大家好，基於對 OneShot 的熱愛，希望能夠在玩遊戲中有更好的體驗，因此製作這份中文化模組，供大家參考使用～

本人因受到近年不斷有熱心的鄉民願意提供中文化，給予熱愛遊戲的玩家一個良好遊戲體驗，基於這份心也想貢獻自己綿薄之力，為該社群盡一份心力

本人並非有相關資訊背景，而是透過網路教學文章與相關開發工具，慢慢摸索得知其中文化方法，技術雖然沒有很成熟，僅能進行一些簡單結構的遊戲中文化開發，敬請見諒。

## 使用說明

以 [OneShot](https://store.steampowered.com/app/420530/OneShot/) 之 [Steam](https://store.steampowered.com/) 原版簡體中文語系為基礎， 進行正體中文化與差異口語修正，用語會參照科技部相關單位釋出的標準。若錯誤之處，希望能夠告知。

目前適用版本為 [Steam](https://store.steampowered.com/) 購買的 [OneShot](https://store.steampowered.com/app/420530/OneShot/) ，其他平台請自行測試，非正版用戶請勿下載。

## 版本日誌

2.1.1

- 補上遺漏項目

2.1.0

- 大量修正錯誤的文本敘述與字體顯示錯誤
- 部分圖檔用字格式、語法與位置修訂
- 文字限字解除，已修正大部分專有名詞

2.0.0 大幅更新版本

- 提示字體修正
- 遊戲字體修正為「思源黑體 Regular」（由 Ptt 網友 voico 感謝提供技術協助）
- 支援 itch 版本可以使用（由 Ptt 網友 voico 感謝提供技術協助）
- MD 文字敘述修正
- 遊戲用語部分修正
- 內部文字生成已繁體化（感謝 Github 朋友 454jkjh5 協助提供技術）
- 台詞用語近一步修正

1.0.1 修正部分錯誤

1.0.0 初始版正體/繁體中文翻譯

## 安裝方式

0. 至 [Gibhub download](https://github.com/danny657031/OneShot-TraditionalChinese-Translate) 點擊「 Code 」後，選擇 「 Download ZIP」，下載完成後解壓縮，或者直接在 Google Drive下載並解壓縮。

1. 尋找遊戲目標資料夾

   1. Windows: Steam\SteamApps\common\OneShot
   2. MacOX: /Users/Library/Application Support/Steam/steamapps/common/OneShot

2. 將對應的檔案進行備份 (若會自己進行 [Steam 驗證檔案完整性](https://support.steampowered.com/kb_article.php?p_faqid=282&l=traditional%20chinese)，可以略過此步驟)

    - ~\Graphics\Pictures\zh_CN\所有檔案
    - ~\Graphics\Fogs\ _\scenario1
    - ~\Graphics\Fogs\ _\scenario2
    - ~\Languages\zh_CN.loc
    - ~\Languages\internal\zh_CN.loc
    - ~\Wallpaper\zh_CN\所有檔案
    - ~\Data\xScripts.rxdata
    - ~\Fonts\wqy-microhei.ttf

3. 將本模組中對應資料夾覆蓋至遊戲目錄中，共有 5 個勿遺漏。(Windows, Mac 適用)

    - Graphics
    - Languages
    - Wallpaper
    - Data
    - Fonts

4. 補充 (僅限於 Mac)

    - 模組中有個資料夾名為 「_______ 」，裡面有中文化後的圖片，但這僅限於 MacOS 系統，因為 Windows 版本的應用程式技術上無法拆開，真的不好意思。
    - Mac版本的用戶可以在遊戲目錄中，找到名為「 _______ 」的程式，點擊右鍵，並點選「顯示套件內容」，可以找到一個資料夾名為「Content」，直接將名為 「_______ 」下載來的資料夾，把裡面的「Content」資料夾複製後進行貼上合併即可。

## Q & A

~~Q1: 關於遊戲中用語「代碼」、「螺絲刀」等一詞的問題。~~
~~> A1: 因為開中文化檔案受限於字數關係，原本我們用語是叫做「程式碼」，我也想不到其他替代單字，故持續沿用該說法。也有想過使用「編碼」，但意涵也不太對。因此其他少數名稱，如螺絲刀( = 螺絲起子) 等部分用語，基於技術問題難以翻譯，深感抱歉。~~
> 目前已解決此項問題，感謝大家給予的協助～

Q2: 中文化是全面都有做到嗎？
> A2: 大部分的文字與圖片檔案都有進行中文化，Windows版本中有個程式「 _______.exe 」，這部分中文化技術上沒辦法處理，Mac版本有提供中文化圖片協助。

Q3: 還會持續更新嗎？
> A3: 若大家願意提供給我一些錯誤的用詞，我會盡快進行修正上傳，非常謝謝大家一起願意讓這遊戲變得更好。

Q4: 有支援其他平台嗎？
> A4: 感謝熱心 Ptt 網友 voico 的技術協助，itch 版平台可以適用於此中文化！

Q5: 版本的更新如何得知？
> A4: 在這次版本 2.0.0 中，是最後一次在 Ptt 上發表，往後都會透過 [Steam 討論區](https://steamcommunity.com/sharedfiles/filedetails/?id=2180206255)，或者 [Github](https://github.com/danny657031/OneShot-TraditionalChinese-Translate#readme) 上直接更新版本，大家可以有空去留言或是關注歐！

## 製作人員

翻譯：Danny

校潤：Danny

遊戲測試：Danny

## 感謝語

真的非常感謝大家踴躍協助技術上的支援，使這個中文化模組變得更加完善，不論是在 Ptt 或者 Github 上的朋友，如此積極給予意見想法，讓人真的非常感動，也順利提供更加完整的版本給大家使用，再次感謝大家的協助與參與！這專案是大家一起幫忙合作變得更加完整，讓人充滿希望 :)

## 注意事項

本模組供個人使用為主，不保證無任何 Bug 或問題，若不幸造成您的損失，本模組無法負起相關責任，深感抱歉。

未來將不定期進行修正，直到開發者評估無需再繼續開發為止。

有任何問題或建議，可至在各大板上留言，期望能夠讓中文化更加完善。 :)

## 下載連結

1. Google: https://drive.google.com/file/d/1NW3oXsM_PooMmc6rAbIW6Bykx-Fmz2ej/view?usp=sharing
2. Github: https://github.com/danny657031/OneShot-TraditionalChinese-Translate#readme
3. Steam 討論區: https://steamcommunity.com/sharedfiles/filedetails/?id=2180206255