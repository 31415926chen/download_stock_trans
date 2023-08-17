# download_stock_trans
# 股票每日成交統計表爬蟲程式

這個 Python 程式可以從台灣證券交易所（TWSE）網站爬取指定股票在特定時間範圍內的每日成交統計資料，並將資料存儲到 Excel 表格中。

## 前置需求

在執行程式之前，請確保您已經擁有以下內容：

- Python 3.x
- 安裝 `requests` 套件：`pip install requests`
- 安裝 `openpyxl` 套件：`pip install openpyxl`

## 開始使用

1. 將這個存儲庫複製到您的本地電腦，或者下載 `stock_data_scraper.py` 檔案。

2. 在 `setting.xml` 檔案中，根據您的需求設定爬取資料的參數，包括：

    - `url`：TWSE 資料查詢網址
    - `excelName`：輸出 Excel 檔案的名稱（不含副檔名）
    - `startYear`：起始年份
    - `startMonth`：起始月份
    - `endYear`：結束年份
    - `endMonth`：結束月份
    - `stockNo`：股票代號

3. 將 `setting.xml` 檔案放置於與 `stock_data_scraper.py` 同一目錄下。

4. 開啟終端機或命令提示字元。

5. 導航到包含 `stock_data_scraper.py` 程式的目錄。

6. 使用以下命令執行程式：

    ```bash
    python stock_data_scraper.py
    ```

7. 程式將爬取每日成交統計資料並儲存到指定的 Excel 檔案中。

## 自訂化

您可以透過修改 `setting.xml` 檔案中的參數來自訂爬取資料的時間範圍和股票代號。

## 注意事項

請注意 TWSE 網站的使用條款和限制，以確保您的爬取行為是合法且符合規範的。

## J.ROBERT.BARBENHEIMER

[您的名字]

## 授權

本專案採用 [MIT 授權條款](LICENSE)。

---

請將以上內容複製並貼上到您的 README.md 檔案中。如有需要，您可以根據您的需求進行進一步修改。
