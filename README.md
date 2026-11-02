<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Takuya&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=32&desc=Product%20%C3%97%20Engineering%20%7C%20Tokyo&descAlignY=52&descSize=18" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&duration=3200&pause=1000&color=7AA2F7&center=true&vCenter=true&width=560&lines=AWS+Serverless+%C3%97+TypeScript;Planning+%E2%86%92+Spec+%E2%86%92+Design+%E2%86%92+Release;Fixing+bugs+upstream%2C+not+around+them" alt="Typing SVG" />

</div>

SaaS プロダクトの企画・開発から、リリース後の運用まで担当しています。<br/>
仕事では AWS サーバーレスを使った開発・運用や、リリース時のテスト設計、本番監視に取り組んでいます。個人では Nuxt と Supabase で有料サービスを開発・運営しています。

まず見てほしいもの → [aws-amplify にマージされた修正PR](https://github.com/aws-amplify/amplify-data/pull/768) ／ [claude-code-meter](https://github.com/rararax16/claude-code-meter)

---

## 今の仕事

社内の手作業の自動化から始め、いまは次のことに取り組んでいます。

- Amplify Gen2・Lambda・DynamoDB・Redshift を中心とした AWS サーバーレス構成の設計・運用
- スプリント運用、テスト設計、障害を減らすためのリリース運用の改善
- Datadog の RUM・Logs を使った本番監視と、その自動化
- 企画から実装まで、AI を活用する開発フローの整備

---

## OSS へのコントリビュート

<div align="center">

<img src="https://img.shields.io/badge/Merged%20into-aws--amplify%2Famplify--data-FF9900?style=for-the-badge&logo=awsamplify&logoColor=white&labelColor=1A1B27" />

</div>

<br/>

| リポジトリ | 内容 | 状態 |
| :--- | :--- | :--- |
| [aws-amplify/amplify-data](https://github.com/aws-amplify/amplify-data/pull/768) | カスタムオペレーションで、null を許容するリスト引数が必須扱いになる不具合を修正 | **Merged** |
| [heavysixer/node-pptx](https://github.com/heavysixer/node-pptx) | ヘルパー関数のリファクタリングとドキュメント整備 | Open |
| [vuetifyjs/vuetify](https://github.com/vuetifyjs/vuetify) | `v-text-field` と `clearable` を併用したときの挙動について不具合を報告 | Reported |

---

## これまでの活動

| 時期 | 活動 | やったこと |
| :--- | :--- | :--- |
| 2025–2026 | リリース運用 | スプリント運用・テスト設計を整備／aws-amplify に修正PRがマージ |
| 2025–2026 | 個人開発 | Claude Code・Codex などの AI エージェントを使い、十数個のプロダクトを開発／有料サービス「とっておき」を本番公開 |
| 2022–2024 | 個人開発・社内ツールの内製 | TypeScript・React で個人開発／Docker・Budibase で社内ツールを内製化 |
| 2019–2020 | 手作業の自動化 | GAS-library で関数をライブラリ化／GAS-SNS-BOARD を公開（★4 / fork 7） |

---

## 個人開発

<table>
<tr>
<td width="50%" valign="top">

### とっておき

LINE のトーク履歴から思い出の会話を選び、贈り物にできる縦動画のメッセージカードを作る有料サービスです。LINE ログイン、Stripe 決済、AI によるカード作成まで一人で開発し、公開・運営しています。

<img src="https://img.shields.io/badge/Nuxt%204-00DC82?style=flat-square&logo=nuxtdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" />
<img src="https://img.shields.io/badge/LINE-00C300?style=flat-square&logo=line&logoColor=white" />
<img src="https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white" />

</td>
<td width="50%" valign="top">

### NLH ヘッズアップ

1対1のポーカーでリアルタイムに対戦できる Web アプリです。配札と勝敗はサーバー側で決め、RLS（行単位のアクセス制御）で手札が本人にしか見えないようにしています。

<img src="https://img.shields.io/badge/Nuxt%204-00DC82?style=flat-square&logo=nuxtdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase%20Realtime-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [claude-code-meter](https://github.com/rararax16/claude-code-meter)

Claude Code の使用量を Mac のメニューバーに常駐表示する Swift 製アプリです。ローカルのログだけで集計し、外部とは通信しません。

<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" />
<img src="https://img.shields.io/github/stars/rararax16/claude-code-meter?style=flat-square&color=7AA2F7&labelColor=1A1B27" />
<img src="https://img.shields.io/github/last-commit/rararax16/claude-code-meter?style=flat-square&color=7AA2F7&labelColor=1A1B27" />

</td>
<td width="50%" valign="top">

### [GAS-SNS-BOARD](https://github.com/rararax16/GAS-SNS-BOARD)

Google Workspace だけで完結する掲示板です。2020年に公開し、いまも fork されています。

<img src="https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=flat-square&logo=googleappsscript&logoColor=white" />
<img src="https://img.shields.io/github/stars/rararax16/GAS-SNS-BOARD?style=flat-square&color=7AA2F7&labelColor=1A1B27" />
<img src="https://img.shields.io/github/forks/rararax16/GAS-SNS-BOARD?style=flat-square&color=7AA2F7&labelColor=1A1B27" />

</td>
</tr>
</table>

<details>
<summary>そのほかの公開プロダクト・リポジトリ</summary>

<br/>

| 名前 | 内容 | 技術 |
| :--- | :--- | :--- |
| [Pocket Poker](https://pocketpoker-3pgl.vercel.app) | スマホでプリフロップの判断を練習するアプリ | Vue / Nuxt |
| [アニルート](https://aniroute.vercel.app) | アニメを見る順番のガイド | JavaScript |
| [react-twitter-clone](https://github.com/rararax16/react-twitter-clone) | React と Firebase で作った Twitter クローン | TypeScript |
| [GAS-library](https://github.com/rararax16/GAS-library) | GAS でよく使う関数をまとめたライブラリ。手作業の自動化を始めたころに作成 | JavaScript |

</details>

---

## 使用技術

主に TypeScript と Vue / Nuxt を使っています。インフラは AWS サーバーレスが中心です。個人開発では Supabase を使った Web サービスや、Swift 製の macOS アプリも作っています。これまでに React・Next.js・Firebase・Google Apps Script なども使ってきました。

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,vue,nuxtjs,nodejs,swift,aws,supabase,cloudflare,vercel,docker,git,github&theme=dark" />

<img src="https://skillicons.dev/icons?i=js,react,nextjs,firebase,html,css,figma,notion&theme=dark" />

<br/>

<img src="https://img.shields.io/badge/AWS%20Amplify%20Gen2-FF9900?style=flat-square&logo=awsamplify&logoColor=white" />
<img src="https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white" />
<img src="https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white" />
<img src="https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
<img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white" />
<img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=flat-square&logo=googleappsscript&logoColor=white" />
<img src="https://img.shields.io/badge/Budibase-000000?style=flat-square&logo=budibase&logoColor=white" />

</div>

---

## GitHub Stats

GitHub は2018年から利用しています。

<div align="center">

<img src="https://img.shields.io/github/stars/rararax16?style=for-the-badge&logo=github&label=Stars&color=7AA2F7&labelColor=1A1B27" />
<img src="https://img.shields.io/github/followers/rararax16?style=for-the-badge&logo=github&label=Followers&color=7AA2F7&labelColor=1A1B27" />
<img src="https://img.shields.io/badge/Public%20Repos-8-7AA2F7?style=for-the-badge&logo=github&labelColor=1A1B27" />
<img src="https://img.shields.io/badge/On%20GitHub%20since-2018-7AA2F7?style=for-the-badge&logo=github&labelColor=1A1B27" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=rararax16&theme=tokyonight" width="98%" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=rararax16&theme=tokyonight" height="200" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=rararax16&theme=tokyonight" height="200" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=rararax16&theme=tokyonight" height="200" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=rararax16&theme=tokyonight&utcOffset=9" height="200" />

</div>

<br/>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=rararax16&style=flat-square&color=7AA2F7&label=Profile+Views" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%" />

</div>
