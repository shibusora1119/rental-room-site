# 渋空 (Shibusora) ウェブサイト

渋谷区東のレンタルスペース「渋空」の公式ウェブサイトです。

## 技術スタック
- **フレームワーク:** [Astro](https://astro.build/)
- **言語:** TypeScript
- **スタイリング:** Vanilla CSS (Astro Scoped CSS)

## ローカル開発
```bash
npm install
npm run dev
```

## Cloudflare Pages へのデプロイ方法

1. このリポジトリを GitHub にプッシュします。
2. Cloudflare ダッシュボードにログインし、「Workers & Pages」を選択します。
3. 「Create application」->「Pages」->「Connect to Git」を選択します。
4. このリポジトリを選択します。
5. ビルド設定で以下を入力します：
   - **Framework preset:** `Astro`
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
6. 「Save and Deploy」をクリックします。

## 所在地
東京都渋谷区東１－１１－９
