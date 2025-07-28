# 學習型聊天機器人

這是一個簡單的命令列聊天機器人，使用 Python 編寫，能夠 **從使用者對話中學習新的知識**。它會將新學到的問答儲存到本地 JSON 檔案中，讓機器人越對話越聰明。

本專案參考自 YouTube 教學影片：  
🎥 [《A Chat Bot That Learns From The User in Python》](https://www.youtube.com/watch?v=CkkjXTER2KE)

## 功能特色

- ✅ 使用 `difflib.get_close_matches` 進行模糊比對，容錯性高
- ✅ 可從使用者那裡學習未知問題的答案
- ✅ 將知識儲存在 `knowledge_base.json` 檔案中持久保存
- ✅ 無需第三方套件，純 Python 標準函式庫實作


## 如何使用

### 1️⃣ 安裝 Python 3.10 或以上版本  
可至 [Python 官方網站](https://www.python.org/downloads/) 下載安裝。

### 2️⃣ 執行聊天機器人

打開終端機或命令提示字元，進入專案資料夾，執行以下指令：

```bash
python chatbot.py

輸入任何問題與機器人對話。
若要結束，輸入：

quit


