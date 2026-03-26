# 金物割付 キャッシュ事故ゼロ構成

## 配置するファイル
- index.html
- manifest.json
- sw.js
- icon-180.png
- icon-192.png
- icon-512.png

## この構成で削除したもの
- icon-1024.png
- splash-1170x2532.png
- 旧READMEの冗長な説明

## 反映手順
1. ZIPを解凍
2. 中身をGitHubリポジトリ直下にそのまま上書き
3. 反映しない端末は一度アプリを閉じて再起動
4. それでも反映しない場合のみサイトデータ削除

## 注意
- service worker のキャッシュ名は kanamono-v2
- 今後さらに構成変更する場合は、sw.js も含めて更新すること
