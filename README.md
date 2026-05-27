# Yokenteigi

ゲーム・便利ツール向けの、Googleフォーム風「要件定義入力フォーム」です。

選択式を中心に入力し、最後に以下の形式で出力できます。

- Markdown
- 短縮形式
- JSON
- ChatGPT用プロンプト

## 特徴

- ゲーム / 便利ツールの2テーマ対応
- スマホ対応
- 単一HTMLで動作
- 外部サーバー不要
- 選択肢に「その他」を用意
- 「その他」選択時は自由入力欄を表示
- 専門的な項目には「おまかせ」を用意
- ブラウザ内に入力内容を自動保存
- コピー・ダウンロード対応

## 使い方

1. `index.html` をブラウザで開く
2. 「ゲーム」または「便利ツール」を選ぶ
3. 質問に答える
4. 確認画面で内容を見る
5. Markdown / 短縮形式 / JSON / ChatGPT用プロンプトをコピーする

## GitHub Pagesで公開する場合

1. GitHubのリポジトリ画面を開く
2. `Settings` を開く
3. `Pages` を開く
4. `Build and deployment` の `Source` を `Deploy from a branch` にする
5. `Branch` を `main`、フォルダを `/root` にする
6. `Save` を押す

公開後は、ブラウザからフォームを使えるようになります。

## MVP仕様

- 対応テーマ: ゲーム / 便利ツール
- 実装形式: 単一HTML
- 保存: localStorage
- 出力: Markdown / compact / JSON / prompt
- UI: スマホ優先、選択式中心

## 今後の拡張案

- テーマ追加
- 入力内容のAI添削
- 要件定義書の詳細化
- タスク分解
- GitHub Issue形式で出力
- 複数プロジェクト保存
- テンプレート管理
