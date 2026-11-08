魔導書 Grimoire 0.7.4 測試版
RPG Maker・TyranoScript 遊戲翻譯與修改工具（Windows 10/11 64 位元）

【開始使用】
1. 把整個 ZIP 解壓縮到一般資料夾，例如 D:\Grimoire。不要在 ZIP 裡直接執行。
2. 雙擊 Grimoire.exe。如果出現「Windows 已保護您的電腦」，請按「其他資訊」，再按「仍要執行」。
3. 把遊戲資料夾拖進視窗。

【Windows 或防毒軟體跳出警告】
目前的版本還沒有數位簽章，而且修改工具會連線並改動執行中的遊戲，所以可能被警告或誤判。
請只從官方發布頁下載，並用發布頁提供的 SHA-256 核對。確認來源後，可在 SmartScreen 按「其他資訊 → 仍要執行」。

【支援的遊戲】
RPG Maker XP／VX／VX Ace／MV／MZ：翻譯與修改。
TyranoScript／TyranoBuilder（Windows 版）：翻譯（對話、說話者名稱、選項）與遊戲變數修改。
不支援：其他引擎，以及打包成單一執行檔的遊戲。

【遊戲需要 RTP】
部分舊版 RPG Maker 遊戲需要官方的 RTP。Grimoire 偵測到缺少時，會詢問是否從 RPG Maker 官方網站下載並開啟官方安裝程式。

【翻譯】
「翻譯」分頁可以匯入字典，或用一鍵設定安裝本機模型。
本機翻譯可在該分頁一鍵安裝：Ollama 會從官方網站下載，並下載約 1.13 GB 的模型（合計下載約 2.8 GB，只需要一次；裝好後不用連網也能翻譯），建議使用獨立顯卡。
翻譯在你的電腦上進行，遊戲文字不會上傳到網路。
遊戲內按 F7 可以切換翻譯開關，按 F8 開啟魔導書面板。
看到翻錯的句子，可以在「修正譯文」直接修改，之後都會使用你的版本。
TyranoScript 遊戲會先翻譯接下來的句子；還沒翻好的句子會等譯文再顯示，可在面板關閉。

【修改】
RPG Maker 遊戲：可修改金錢、道具、能力值等。
TyranoScript 遊戲：在「變數」分頁用數值搜尋或「最近變動」找出道具數量並修改，常用的變數可以加入收藏並自訂名稱。
TyranoScript 遊戲可在「翻譯」分頁調整視窗大小，每款遊戲各自記住。

【更新】
有新版本時，首頁會顯示更新內容，按「更新並重新啟動」即可一鍵更新（0.7.3 以上版本適用）。
更新檔都有作者的數位簽章，魔導書只會安裝官方發布的版本。

【資料存放位置】
設定、字典與備份在 %LOCALAPPDATA%\Grimoire。
Grimoire 不會修改遊戲原始檔案；存檔備份也存放在上述位置。

【注意事項】
修改遊戲內容前，請確認遵守該遊戲的使用條款。修改可能造成存檔異常，建議先建立時光點或自行存檔。
CG 畫廊只供在工具內瀏覽，不提供匯出功能。請勿散布遊戲素材或含遊戲文字的字典，除非你有權這麼做。

【授權】
魔導書 Grimoire 由美雪製作，保留所有權利，可免費用於個人用途。
未經作者書面同意，不得販售、重新散布、修改、反組譯本工具，或以「魔導書」「Grimoire」名義發布非作者製作的版本。
官方下載處只有：https://github.com/HiDragon37/Grimoire/releases
其他地方取得的版本可能被修改過，請勿使用。完整條款請見安裝包內的 LICENSE.txt。

製作者：美雪
回報問題：https://docs.google.com/forms/d/e/1FAIpQLSeVb_HJ8UxTX0_nC3DozS2at0gyMlnIXvusTpLC20zDBU5dEw/viewform
Discord 群組：https://discord.gg/euDanWRJk

本工具按現狀提供，不提供任何擔保。
Grimoire 為獨立開發的工具，不包含其他修改工具的程式檔案，也與 MTool 及其作者無關。
支援匯入 .trs 與 JSON 字典檔，僅為格式相容。


--------------------------------------------------------------------------------------------------------------
Grimoire 0.7.4 Beta

Translation and Modification Tool for RPG Maker and TyranoScript Games (Windows 10/11 64-bit)

Getting Started
1. Extract the entire ZIP archive into a regular directory (e.g., D:\Grimoire). Do not run the application directly from within the ZIP file.
2. Double-click Grimoire.exe. If the "Windows protected your PC" prompt appears, click More info, then select Run anyway.
3. Drag and drop your game folder directly into the application window.

Windows or Antivirus Warnings
The current build does not yet have a digital code-signing certificate. Additionally, because the tool attaches to and modifies active game processes, it may trigger security warnings or false positives.
Please only download Grimoire from the official release page and verify the integrity using the provided SHA-256 hash. Once verified, click More info → Run anyway in Windows SmartScreen.

Supported Engines
RPG Maker XP / VX / VX Ace / MV / MZ: translation and modification.
TyranoScript / TyranoBuilder (Windows builds): translation (dialogue, speaker names, choices) and game variable editing.
Not Supported: Other game engines, as well as games packed into a single standalone executable.

RTP Requirements
Certain legacy RPG Maker titles require the official Run-Time Package (RTP). If missing components are detected, Grimoire will prompt to download and launch the installer directly from the official RPG Maker website.

Translation Features
Under the Translation tab, you can import dictionary files or use the one-click setup to configure a local AI model.
Local Offline Translation: Ollama will be downloaded from its official source alongside a ~1.13 GB language model (total initial download: ~2.8 GB, required only once). Once configured, translations run entirely offline. A dedicated GPU is recommended.
Translation runs on your own PC; no game text is uploaded.
In-Game: Press F7 to toggle translation, and F8 to open the Grimoire panel.
Fix Translations: Correct any mistranslated line in the "Fix translations" section; your version will be used from then on.
TyranoScript games translate upcoming lines in advance; lines that aren't translated yet wait for the translation before showing (this can be turned off in the panel).

Modification Features
RPG Maker games: edit gold, items, stats and more.
TyranoScript games: find item counts with value search or "Recently changed values" in the Variables tab, then edit them. Frequently used variables can be added to favorites with custom names.
TyranoScript games: adjust the window size in the Translation tab; the setting is remembered per game.

Updates
When a new version is available, the home screen shows the release notes. Click "Update and restart" to update in one click (version 0.7.3 or later).
Every update is digitally signed by the author; Grimoire only installs official releases.

Data Storage & Save Backups
All configuration files, dictionaries, and backups are stored at:
%LOCALAPPDATA%\Grimoire
Grimoire does not modify original game files; save data backups are also preserved in the folder specified above.

Important Notes
Ensure you comply with the respective game's terms of service before modifying any content. Modifications can cause save file instability; creating a restore point or saving beforehand is strongly recommended.
The CG Gallery feature is intended strictly for in-app viewing and does not support exporting assets. Please do not redistribute game assets or dictionary files containing game text unless you are legally authorized to do so.

License
Grimoire is made by 美雪 (Miyuki). All rights reserved. Free for personal use.
Without the author's written permission, you may not sell, redistribute, modify or reverse-engineer this software, or release versions not made by the author under the name "Grimoire" or "魔導書".
Official downloads are only available at: https://github.com/HiDragon37/Grimoire/releases
Copies obtained elsewhere may have been modified; please do not use them. See LICENSE.txt in the package for the full terms.

Developer: 美雪 (Miyuki)
Bug Report / Feedback: https://docs.google.com/forms/d/e/1FAIpQLSeVb_HJ8UxTX0_nC3DozS2at0gyMlnIXvusTpLC20zDBU5dEw/viewform
Discord Community: https://discord.gg/euDanWRJk

Disclaimer
This software is provided "as is", without warranty of any kind.
Grimoire is an independently developed tool. It does not include binaries from other modification utilities and is not affiliated with MTool or its creators.
Support for importing .trs and JSON dictionary formats is implemented solely for format compatibility purposes.
