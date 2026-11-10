魔導書 Grimoire 0.7.9 測試版
RPG Maker／TyranoScript／Ren'Py／SRPG Studio 遊戲翻譯與修改工具（Windows 10/11 64 位元）

【開始使用】
1. 把整個 ZIP 解壓縮到一般資料夾，例如 D:\Grimoire。不要在 ZIP 裡直接執行。
2. 雙擊 Grimoire.exe。如果出現「Windows 已保護您的電腦」，請按「其他資訊」，再按「仍要執行」。
3. 把遊戲資料夾拖進視窗。

【Windows 或防毒軟體跳出警告】
目前的版本還沒有數位簽章，而且修改工具會連線並改動執行中的遊戲，所以可能被警告或誤判。
請只從官方下載處下載（見最下方），並用發布頁提供的 SHA-256 核對。確認來源後，可在 SmartScreen 按「其他資訊 → 仍要執行」。

【支援的遊戲】
RPG Maker XP／VX／VX Ace／MV／MZ：翻譯與修改。
TyranoScript／TyranoBuilder（Windows 版）：翻譯（對話、說話者名稱、選項）與遊戲變數修改。
Ren'Py（Windows 版，含 Steam 版）：翻譯（對話、角色名稱、選項、介面文字）與遊戲變數修改。遊戲執行期間會在 game 資料夾放入翻譯外掛，關閉遊戲後自動刪除。
SRPG Studio（Windows 版，加密與未加密皆可，測試中）：翻譯（對話、角色、職業、道具、技能名稱）與遊戲修改（主視窗的「遊戲修改」頁面，或遊戲中按 F8）。遊戲執行期間會在 data.dts 暫時加入翻譯外掛，並暫時調整 game.ini，關閉遊戲後自動還原。遊戲畫面放大 1.5 倍、2 倍時，滑鼠會限制在遊戲畫面內，按 Alt+Tab 可切到其他程式。
Steam 版遊戲可能會被 Steam 重新開啟，魔導書會自動等候並接上翻譯；如果遊戲沒有出現，請在 Steam 按「開始遊戲」。
不支援：其他引擎，以及打包成單一執行檔的遊戲。

【遊戲中的快捷鍵】
F8：打開魔導書選單（修正譯文、重新翻譯、修改遊戲）
F7：切換翻譯開關

【遊戲需要 RTP】
部分舊版 RPG Maker 遊戲需要官方的 RTP。Grimoire 偵測到缺少時，會詢問是否從 RPG Maker 官方網站下載並開啟官方安裝程式。

【翻譯】
「翻譯」分頁可以匯入字典，或用一鍵設定安裝本機模型。
本機翻譯可在該分頁一鍵安裝：Ollama 會從官方網站下載，並下載約 1.13 GB 的模型（合計下載約 2.8 GB，只需要一次；裝好後不用連網也能翻譯），建議使用獨立顯卡。

【連網】
啟動時會連到 GitHub 讀取公告、檢查新版本，不會送出個人資料。有新版本時，要你按下「更新並重新啟動」才會下載，並且只安裝有製作者簽章的版本。可在首頁的公告區關閉連網檢查。

【資料存放位置】
設定、字典與備份在 %LOCALAPPDATA%\Grimoire。
Grimoire 不會永久修改遊戲原始檔案（Ren'Py、SRPG Studio 遊戲執行期間暫時加入的外掛，關閉遊戲後會自動移除）。

【注意事項】
本工具僅供單機遊戲使用，請勿用於線上或多人遊戲。
修改遊戲內容前，請確認遵守該遊戲的使用條款。修改可能造成存檔異常，建議先備份存檔。
請勿散布遊戲素材或含遊戲文字的字典，除非你有權這麼做。

製作者：美雪
官方下載處（只有這兩個）：
  https://hidragon37.itch.io/grimoire
  https://github.com/HiDragon37/Grimoire/releases
回報問題：https://docs.google.com/forms/d/e/1FAIpQLSeVb_HJ8UxTX0_nC3DozS2at0gyMlnIXvusTpLC20zDBU5dEw/viewform
Discord 群組：https://discord.gg/euDanWRJk

本工具按現狀提供，不提供任何擔保。
Grimoire 為獨立開發的工具，不包含其他修改工具的程式檔案，也與 MTool 及其作者無關。

==========================================================

Grimoire 0.7.9 Beta
Translation and editing tool for RPG Maker / TyranoScript / Ren'Py / SRPG Studio games (Windows 10/11, 64-bit)

[Getting started]
1. Extract the whole ZIP to a normal folder, e.g. D:\Grimoire. Don't run it from inside the ZIP.
2. Double-click Grimoire.exe. If "Windows protected your PC" appears, click "More info", then "Run anyway".
3. Drag your game folder into the window.

[Windows or antivirus warnings]
This build isn't code-signed yet, and the tool connects to and modifies a running game, so it may be flagged.
Only download from the official pages (see below) and verify the file with the SHA-256 checksum on the release page.

[Supported games]
RPG Maker XP / VX / VX Ace / MV / MZ: translation and editing.
TyranoScript / TyranoBuilder (Windows): translation (dialogue, speaker names, choices) and game variable editing.
Ren'Py (Windows, including Steam): translation (dialogue, character names, choices, UI text) and game variable editing. A translation plug-in is placed in the game folder while the game runs and removed when it closes.
SRPG Studio (Windows, encrypted or not, beta): translation (dialogue, character,
