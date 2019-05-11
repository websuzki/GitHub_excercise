# Git基本ブランチモデル習得
Gitを実際の使用に近い形で使いこなせるように練習するためのレポジトリです。

最終的には、以下のブランチモデルを使用できるように毎日更新しております

- master
- develop/(バージョン番号）
- feature/（派生元バージョン番号）/（機能名）
- release/(バージョン番号）
- hotfix/（バグ識別名）




# 基本モデルを導入:5月10日
Developとfeatureブランチを使用して、機能ごとに、実装し、
バグがなければDevelop→masterにマージという形を練習するようにした



# ブランチ間のテスト:5月8日～10日
挙動をテストするために、3つのブランチを作成した

|key|value|
|----|----|
|Windows:Cygwin上のGit|win_workfile|
|Windows:MINGW上のGit|ming64_workfile|
|GitHubで直接編集するブランチ|workfile|



# 初期段階：5月8日以前

## 練習1
Windows側にGit2.21.0をインストールし、そことの連携を練習

## 練習2
Windowsでwin_workfileというブランチを作り、ブランチがmaster含め、3つになった。
これで挙動を試していきたい

