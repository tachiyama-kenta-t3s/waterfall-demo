
# ディレクトリ構成
project-root/  
├── frontend/                 # フロントエンド（React＋TypeScript）  
│   ├── public/               # 静的ファイル (HTML, faviconなど)  
│   ├── src/                  # ソースコード  
│   │   ├── components/       # UIコンポーネント（再利用部品など）  
│   │   └── App.tsx           # アプリのエントリーポイント  
│   ├── package.json          # npm依存パッケージ・スクリプト管理  
│   └── tsconfig.json         # TypeScript設定  
│  
├── backend/                  # バックエンド（Flask＋Python）  
│   ├── app.py                # Flaskアプリ本体（エンドポイント/ロジック）  
│   ├── models.py             # データベースモデル（必要な場合のみ）  
│   └── requirements.txt      # Python依存パッケージリスト  
│  
├── .gitignore                # Git管理対象外ファイル定義  
└── README.md                 # プロジェクト概要・利用方法  