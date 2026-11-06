魔導書 Grimoire 0.6.0 測試版
RPG Maker 遊戲修改與翻譯工具（Windows 10/11 64 位元）

【開始使用】
1. 把整個 ZIP 解壓縮到一般資料夾，例如 D:\Grimoire。不要在 ZIP 裡直接執行。
2. 雙擊 Grimoire.exe。如果出現「Windows 已保護您的電腦」，請按「其他資訊」，再按「仍要執行」。
3. 把遊戲資料夾拖進視窗。

【Windows 或防毒軟體跳出警告】
目前的版本還沒有數位簽章，而且修改工具會連線並改動執行中的遊戲，所以可能被警告或誤判。
請只從官方發布頁下載，並用發布頁提供的 SHA-256 核對。確認來源後，可在 SmartScreen 按「其他資訊 → 仍要執行」。

【支援的遊戲】
RPG Maker XP／VX／VX Ace／MV／MZ。
不支援：其他引擎，以及打包成單一執行檔的遊戲。

【遊戲需要 RTP】
部分舊版 RPG Maker 遊戲需要官方的 RTP。Grimoire 偵測到缺少時，會詢問是否從 RPG Maker 官方網站下載並開啟官方安裝程式。

【翻譯】
「翻譯」分頁可以匯入字典，或用一鍵設定安裝本機模型。
本機翻譯可在該分頁一鍵安裝：Ollama 會從官方網站下載，並下載約 1.13 GB 的模型（合計下載約 2.8 GB，只需要一次；裝好後不用連網也能翻譯），建議使用獨立顯卡。
遊戲內按 F7 可以切換翻譯開關。

【資料存放位置】
設定、字典與備份在 %LOCALAPPDATA%\Grimoire。
Grimoire 不會修改遊戲原始檔案；存檔備份也存放在上述位置。

【注意事項】
修改遊戲內容前，請確認遵守該遊戲的使用條款。修改可能造成存檔異常，建議先建立時光點。
CG 畫廊只供在工具內瀏覽，不提供匯出功能。請勿散布遊戲素材或含遊戲文字的字典，除非你有權這麼做。

製作者：美雪
回報問題：https://docs.google.com/forms/d/e/1FAIpQLSeVb_HJ8UxTX0_nC3DozS2at0gyMlnIXvusTpLC20zDBU5dEw/viewform
Discord 群組：https://discord.gg/euDanWRJk

本工具按現狀提供，不提供任何擔保。
Grimoire 為獨立開發的工具，不包含其他修改工具的程式檔案，也與 MTool 及其作者無關。
支援匯入 .trs 與 JSON 字典檔，僅為格式相容。


--------------------------------------------------------------------------------------------------------------
Grimoire 0.6.0 Beta

RPG Maker Game Modification and Translation Tool (Windows 10/11 64-bit)

Getting Started
Extract the entire ZIP archive into a regular directory (e.g., D:\Grimoire). Do not run the application directly from within the ZIP file.

Double-click Grimoire.exe. If the "Windows protected your PC" prompt appears, click More info, then select Run anyway.

Drag and drop your game folder directly into the application window.

Windows or Antivirus Warnings
The current build does not yet have a digital code-signing certificate. Additionally, because the tool attaches to and modifies active game processes, it may trigger security warnings or false positives.

Please only download Grimoire from the official release page and verify the integrity using the provided SHA-256 hash. Once verified, click More info → Run anyway in Windows SmartScreen.

Supported Engines
Supported: RPG Maker XP / VX / VX Ace / MV / MZ

Not Supported: Other game engines, as well as games packed into a single standalone executable.

RTP Requirements
Certain legacy RPG Maker titles require the official Run-Time Package (RTP). If missing components are detected, Grimoire will prompt to download and launch the installer directly from the official RPG Maker website.

Translation Features
Under the Translation tab, you can import dictionary files or use the one-click setup to configure a local AI model:

Local Offline Translation: Can be set up directly from this tab. Ollama will be downloaded from its official source alongside a ~1.13 GB language model (total initial download: ~2.8 GB, required only once). Once configured, translations run entirely offline without an internet connection. A dedicated GPU is recommended.

In-Game Toggle: Press F7 while in-game to toggle the translation overlay on or off.

Data Storage & Save Backups
All configuration files, dictionaries, and backups are stored at:

%LOCALAPPDATA%\Grimoire

Grimoire does not modify original game files; save data backups are also preserved in the folder specified above.

Important Notes
Ensure you comply with the respective game's terms of service before modifying any content. Modifications can cause save file instability; creating a restore point beforehand is strongly recommended.

The CG Gallery feature is intended strictly for in-app viewing and does not support exporting assets. Please do not redistribute game assets or dictionary files containing game text unless you are legally authorized to do so.

Developer: 美雪 (Miyuki)

Bug Report / Feedback: https://docs.google.com/forms/d/e/1FAIpQLSeVb_HJ8UxTX0_nC3DozS2at0gyMlnIXvusTpLC20zDBU5dEw/viewform

Discord Community: https://discord.gg/euDanWRJk

Disclaimer
This software is provided "as is", without warranty of any kind.

Grimoire is an independently developed tool. It does not include binaries from other modification utilities and is not affiliated with MTool or its creators.

Support for importing .trs and JSON dictionary formats is implemented solely for format compatibility purposes.