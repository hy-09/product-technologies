---
layout: default
title: 技術スタック
---

# 成果物
生成AIを活用した英語学習サービス  
[https://enxample.net/](https://enxample.net/){:target="_blank"}  

■主な機能  
・検索した英単語の使用例文を生成AIで作成  
・パターンプラクティスを生成AIで作成  

■テスト用アカウント  
メールアドレス：test@test.com  
パスワード：4vVfDr4Jj6qt  

# 技術スタック

## フロントエンド
- React 18 / TypeScript / Vite
- shadcn/ui (Radix UI × TailwindCSS)
- Tanstack Router
- Tanstack Query
- zustand
- React Hook Form / Zod

## バックエンド
- Laravel 11

## 外部サービス
- Stripe（決済プラットフォーム）
- Redis（キャッシュサーバ）
- Google reCAPTCHA
- OAuth
  - Google
  - Discord
  <!-- - Instagram -->
- Gemini API（生成AI API）
- WordsAPI（英単語辞書 API）
- Datamuse API（英単語サジェスト API）

## Webサーバ
- Nginx

## データベース
- MySQL

## インフラ（AWS）
- Lightsail
- CloudWatch
- SNS
- Lambda

## CI/CD
- GitHub Actions

## ローカル環境構築
- Docker / Docker Compose
