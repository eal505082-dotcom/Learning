# Web開発学習 TODO

最終目標：アプリケーションを開発できるようになる。月数万円を稼げるマイクロスモールビジネスを立ち上げる。

---

## Phase 1: 基礎固め

### 01. Git & GitHub
目標：コードをバージョン管理し、GitHubでリポジトリを公開・管理できるようになる

- [x] Gitとは何か、なぜ使うのかを理解する
- [x] Gitのインストールと初期設定
- [x] 基本コマンド（init, add, commit, status, log, diff）
- [x] ブランチの作成・切り替え・マージ
- [x] GitHubアカウント作成とSSH設定
- [x] リモートリポジトリの操作（push, pull, clone）
- [x] プルリクエストの作成とレビューの流れ
- [x] .gitignoreの使い方
- [x] コンフリクトの解消

### 02. HTML & CSS
目標：Webページの構造とデザインを自力で組めるようになる

- [x] HTMLとは何か、Webページの仕組みを理解する
- [x] 基本タグ（html, head, body, div, p, a, img, ul, ol, table）
- [x] フォーム要素（input, button, form, select）
- [x] セマンティックHTML（header, nav, main, section, footer）
- [x] CSSの基本（セレクタ, プロパティ, 値）
- [x] ボックスモデル（margin, padding, border）
- [x] Flexbox レイアウト
- [ ] Grid レイアウト
- [x] レスポンシブデザイン（メディアクエリ）
- [x] 簡単なWebページを1つ作成する（ハンズオン）

### 03. JavaScript
目標：プログラミングの基礎を身につけ、Webページに動きをつけられるようになる

- [ ] JavaScriptとは何か、どこで動くのかを理解する
- [ ] 変数（let, const）とデータ型
- [ ] 演算子と条件分岐（if, switch）
- [ ] ループ（for, while, for...of）
- [ ] 関数（function, アロー関数）
- [ ] 配列とオブジェクト
- [ ] 配列メソッド（map, filter, reduce, forEach）
- [ ] DOM操作（querySelector, addEventListener）
- [ ] 非同期処理（Promise, async/await）
- [ ] fetch APIでデータ取得
- [ ] ES Modules（import/export）
- [ ] 簡単なインタラクティブページを作成する（ハンズオン）

---

## Phase 2: モダン開発技術

### 04. TypeScript
目標：型安全なコードを書けるようになり、開発時のバグを未然に防げるようになる

- [ ] TypeScriptとは何か、JavaScriptとの違いを理解する
- [ ] 基本の型（string, number, boolean, array, object）
- [ ] 型注釈と型推論
- [ ] interface と type の定義
- [ ] ジェネリクスの基礎
- [ ] ユニオン型とリテラル型
- [ ] tsconfig.jsonの基本設定
- [ ] 既存のJSコードをTSに書き換える（ハンズオン）

### 05. React
目標：コンポーネントベースのUI開発ができるようになる

- [ ] Reactとは何か、なぜ使うのかを理解する
- [ ] JSXの書き方
- [ ] コンポーネントの作成（関数コンポーネント）
- [ ] Props（親から子へのデータ渡し）
- [ ] State（useState）
- [ ] イベントハンドリング
- [ ] useEffectと副作用
- [ ] 条件付きレンダリングとリスト表示
- [ ] フォームの扱い
- [ ] カスタムフックの作成
- [ ] Todoアプリを作成する（ハンズオン）

### 06. Node.js
目標：サーバーサイドJavaScriptの基礎を理解し、APIを作れるようになる

- [ ] Node.jsとは何か、ブラウザJSとの違いを理解する
- [ ] npmとパッケージ管理（package.json）
- [ ] モジュールシステム（CommonJS, ESM）
- [ ] ファイル操作（fs）
- [ ] HTTPサーバーの基礎
- [ ] 環境変数の扱い（.env）
- [ ] 簡単なAPIサーバーを作成する（ハンズオン）

---

## Phase 3: フルスタック開発

### 07. Next.js
目標：フルスタックWebアプリをNext.jsで構築できるようになる

- [ ] Next.jsとは何か、Reactとの違いを理解する
- [ ] プロジェクト作成（create-next-app）
- [ ] App Routerの基礎（ファイルベースルーティング）
- [ ] Server Components と Client Components
- [ ] レイアウトとページの構成
- [ ] データフェッチ（Server Components でのfetch）
- [ ] API Routes（Route Handlers）
- [ ] 動的ルーティング
- [ ] ミドルウェア
- [ ] 画像最適化（next/image）
- [ ] ブログサイトを作成する（ハンズオン）

### 08. Supabase
目標：認証・データベース・ストレージを備えたバックエンドをSupabaseで構築できるようになる

- [ ] Supabaseとは何か、Firebaseとの違いを理解する
- [ ] プロジェクト作成と初期設定
- [ ] テーブル作成とデータ操作（CRUD）
- [ ] Supabase クライアントの導入（JavaScript SDK）
- [ ] 認証（サインアップ, ログイン, ログアウト）
- [ ] Row Level Security（RLS）の設定
- [ ] リアルタイム機能
- [ ] ストレージ（ファイルアップロード）
- [ ] Next.js + Supabase でアプリを作成する（ハンズオン）

### 09. Tailwind CSS
目標：ユーティリティファーストのCSSで素早くUIを構築できるようになる

- [ ] Tailwind CSSとは何か、従来CSSとの違いを理解する
- [ ] 基本クラス（余白, 色, フォント, サイズ）
- [ ] Flexbox / Grid のユーティリティ
- [ ] レスポンシブデザイン（sm, md, lg, xl）
- [ ] ダークモード対応
- [ ] カスタム設定（tailwind.config.js）
- [ ] コンポーネントの再利用パターン
- [ ] 既存プロジェクトのCSSをTailwindに置き換える（ハンズオン）

### 10. SQL基礎
目標：データベースの基本操作を理解し、Supabaseのクエリを自在に書けるようになる

- [ ] データベースとは何か、SQLとは何かを理解する
- [ ] テーブルの作成（CREATE TABLE）
- [ ] データの挿入・取得・更新・削除（INSERT, SELECT, UPDATE, DELETE）
- [ ] WHERE句でのフィルタリング
- [ ] JOINによるテーブル結合
- [ ] インデックスの基礎
- [ ] Supabaseのダッシュボードでクエリを実行する（ハンズオン）

---

## Phase 4: 実戦・公開

### 11. デプロイ & Vercel
目標：作ったアプリをインターネットに公開し、運用できるようになる

- [ ] デプロイとは何かを理解する
- [ ] Vercelアカウント作成とGitHub連携
- [ ] Next.jsプロジェクトをVercelにデプロイ
- [ ] 環境変数の設定
- [ ] カスタムドメインの設定
- [ ] 自動デプロイ（GitHub pushで自動反映）

### 12. 総合プロジェクト
目標：学んだ技術を統合し、実用的なアプリを完成させる

- [ ] アプリのアイデア出しと要件定義
- [ ] データベース設計
- [ ] Next.js + Supabase + Tailwind CSS で開発
- [ ] 認証機能の実装
- [ ] CRUD機能の実装
- [ ] レスポンシブ対応
- [ ] Vercelにデプロイして公開
- [ ] ユーザーからフィードバックを受けて改善

---

## 追加おすすめ（余裕ができたら）

- [ ] テスト（Jest, React Testing Library）
- [ ] SEO対策の基礎
- [ ] アクセシビリティ（a11y）
- [ ] Stripe決済連携（収益化に必須）
- [ ] Google Analytics導入
- [ ] PWA（プログレッシブWebアプリ）
