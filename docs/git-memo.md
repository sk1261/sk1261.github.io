---
layout: page
title: "git memo"
permalink: /docs/git-memo
---

# ソフトウェア工学 2024

講義で学んだことまとめ

# gitコマンド
- git init
gitの初期化・設定開始
- git status
ワークツリーのステータスを表示
- git config 
設定周りの確認・変更
- git log
ログを表示
 -- onelineでコミットメッセージの1行のみの一覧表示
- git diff
ファイルの差分を表示
- git add
ステージングエリアに追加
- git commit 
コミットの実行
- git commit --amend --no-edit
コミットの修正
- git checkout
削除されたファイルを復旧や過去コミットの復元など（元に戻す変更がstaging area/index内にある場合）
- git reset
コミットのリセット
- git revert
「コミットの変更を打ち消す」コミット
- git rm
ファイルとindex情報の削除
- git clone
レポジトリをコピー
- git pull
リモートレポジトリの同期	
- git push
変更をアップロードする
- git request-pull
プルリクエスト：変更依頼
- git remote
リモートレポジトリの設定
- git branch
ブランチの作成
- git checkout
ブランチの切り替え
- git merge
ブランチの統合
--ff-only: fast forward only. 変更のない統合先ブランチにマージ（参考）
- git clone
レポジトリをコピー
- git push
変更をアップロードする


# CI/CD
- Continuous Integration (CI)
コード変更を共有リポジトリに頻繁に統合するプロセス
自動テストとビルドを定期的に実行し、バグの早期発見と修正を可能に
CIの自動化により開発のスムーズな進行を促進

- Continuous Delivery (CD)
コード変更をテスト環境や本番環境に自動的にデプロイするプロセス
自動デプロイメントを組み込み、手動操作によるデプロイの必要性を排除
CDにより、ユーザーフィードバックを迅速に反映可能
