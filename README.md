# Base-template

Docker を使用した **シンプルな PHP 開発環境テンプレート** です。  
Nginx + PHP（FPM）を用いた最小構成で、学習用・課題提出用のベースとして利用できます。

---

## 使用技術

- Docker / Docker Compose
- Nginx　1.21.1
- PHP　8.1

---

## ディレクトリ構成

base-template/
├── README.md
├── docker
│   ├── nginx
│   │   └── default.conf
│   └── php
│       ├── Dockerfile
│       └── php.ini
├── docker-compose.yml
└── src/
    └── (phpファイルを配置)

---

## 環境構築手順

### 1. リポジトリをクローン

```bash
git clone リポジトリURL
cd base-template

### 2.Docker コンテナを起動

・docker compose up -d --build

### 3. 動作確認

ブラウザで以下にアクセスしてください。

http://localhost

