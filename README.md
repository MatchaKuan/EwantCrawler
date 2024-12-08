Ewant報表爬蟲網站

113-01_EwantCrawler/
├── MainProgram/
│   ├── src/
│   │   ├── crawler/
│   │   │   ├── __init__.py
│   │   │   ├── login.py      # 處理登入相關
│   │   │   ├── parser.py     # 處理爬蟲和解析
│   │   │   └── export.py     # 處理資料匯出
│   │   │
│   │   ├── ui/
│   │   │   ├── __init__.py
│   │   │   └── main_window.py  # UI 主視窗類別
│   │   │
│   │   └── utils/
│   │       ├── __init__.py
│   │       ├── config.py     # 設定檔
│   │       └── logger.py     # 日誌處理
│   │
│   ├── venv/                 # 虛擬環境（已建立）
│   ├── requirements.txt      # 相依套件清單
│   └── main.py              # 程式進入點