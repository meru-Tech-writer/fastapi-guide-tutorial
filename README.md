# 🚀 FastAPI Tutorial: 最速「Hello World」Docker構成

本リポジトリは、note 記事 [【FastAPI Python 入門】2026年最新の使い方・ディレクトリ構成・JWT認証・AWS公開までを網羅した実務テンプレート](https://note.com/meru_tech/n/n3b974417e36b) で解説している最小構成のサンプルコードです。

FastAPI の爆速な開発体験と、Docker によるクリーンな環境構築を 5 分で体感いただけます。

## 📦 含まれているもの

* `main.py`: シンプルな Hello World API エンドポイント
* `Dockerfile`: 軽量な Python 3.12-slim 環境の設計図
* `docker-compose.yml`: ホットリロード設定済みのコンテナ定義

## 🚀 使い方 (Quick Start)

Docker がインストールされた環境で、以下の手順を実行してください。

### 1. 起動
ターミナルで本ディレクトリに移動し、コマンドを実行します。
```bash
docker compose up
```

### 2. 動作確認

サーバーが起動したら、ブラウザで以下の URL にアクセスしてください。

* **API 実行結果**: [http://localhost:8000](https://www.google.com/search?q=http://localhost:8000) 


* **自動生成ドキュメント**: [http://localhost:8000/docs](https://www.google.com/search?q=http://localhost:8000/docs) 



## 🛡️ 次のステップ：実務レベルの構築へ

このリポジトリは、学習のスタート地点となる「最小構成」です 。

実務で必須となる **「ディレクトリ構成（関心の分離）」「JWT 認証」「SQLAlchemy による非同期 DB 接続」** などを含む完全なテンプレートと解説は、note 本編をご確認ください 。

---
