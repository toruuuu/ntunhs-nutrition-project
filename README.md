# 【建立一個行動化外食均衡營養推薦系統-Balance Diet】
## 113學年 國北護資管系 徐老師專題組 
### 此目錄分為四個資料夾：
#### DataBase/
1. DataBase_SPEC.xlsx ----各資料表欄位說明
2. DataBase_TABLE.xlsx ---包含外食資料、Dris標準

#### LineBot/
1. templates/ ----前端畫面的html檔案
2. server.ipynb --由ngrok與flask建置伺服器

#### Service/
1. generate_menu.ipynb ----生成菜單：推薦包含三餐、點心、飲料，每一餐至多出現兩種食物，可由營養攝取、SQL參數調整推薦演算法。
2. record_diet.ipynb ------紀錄飲食：串接GPT實現訊息文本轉為指定欄位格式(Str to Json)，可由提示詞調整生成結果。

#### document/
1. 專題書面報告.pdf
2. 專題海報.pdf
3. 專題發表簡報_不含影片.pptx
4. 簡報成果展示影片1.mp4
5. 簡報成果展示影片2.mp4
6. 簡報成果展示影片3.mp4

### 開發工具：
#### Python: Jupyter Notebook
#### DataBase: MySQL
#### LineBot: LINE Developers
設定LineBot環境可參考：
https://steam.oxxostudio.tw/category/python/example/line-developer.html#google_vignette
#### GPT: opaiapi
https://medium.com/@austinlaurice/openai-api-%E5%85%A5%E9%96%80-chat-endpoint-2282ae88c8f3
需要付費取得token，製作專題時花費5美金，期間只使用不到0.5美金
