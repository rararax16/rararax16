<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Takuya&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=32&desc=Product%20%C3%97%20Engineering%20%7C%20Tokyo&descAlignY=52&descSize=18" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&duration=3200&pause=1000&color=7AA2F7&center=true&vCenter=true&width=560&lines=AWS+Serverless+%C3%97+TypeScript;Planning+%E2%86%92+Spec+%E2%86%92+Design+%E2%86%92+Release;Fixing+bugs+upstream%2C+not+around+them" alt="Typing SVG" />

</div>

---

## About

SaaS プロダクトの企画から、仕様・設計・リリース運用までを担当しています。
AWS のサーバーレス構成の上で、コードを書くより **リリースが安全に回る仕組みを整える** 時間のほうが長いです。
もとは社内の手作業を自動化するところから始めました。

```yaml
location:  Tokyo
now:       SaaS プロダクトの企画 〜 リリース運用
stack:     TypeScript / AWS Serverless (Amplify Gen2, Lambda, DynamoDB)
doing:     開発フロー設計 / テスト設計・QA / Datadog での本番監視
side:      macOS アプリ（Swift）、たまに OSS への PR
```

---

## Currently

- **AWS Serverless** — Amplify Gen2・Lambda・DynamoDB・Redshift を中心とした構成の設計と運用
- **Release Ops** — スプリント運用、テスト設計、障害を「仕組み」で減らす取り組み
- **Observability** — Datadog（RUM / Logs）での本番監視と、その自動化
- **AI in the loop** — 企画から実装まで AI を組み込んだ開発フローの整備

---

## Timeline

```text
2026  ──  AWS / Swift / OSS      aws-amplify に修正PRがマージ、Claude Code Meter を公開
2025  ──  Release Ops            スプリント運用・テスト設計・障害低減の仕組み化
2024  ──  Docker / Budibase      社内ツールの内製化、コンテナ運用へ
2022  ──  TypeScript / React     OOP・健康管理アプリ、React × Firebase で Twitter クローン
2020  ──  GAS-SNS-BOARD          Google Workspace だけで動く掲示板アプリ ★4 / fork 7
2019  ──  GAS-library            よく使う関数をライブラリ化、自動化の入り口
```

---

## Open Source

<div align="center">

<img src="https://img.shields.io/badge/Merged%20into-aws--amplify%2Famplify--data-FF9900?style=for-the-badge&logo=awsamplify&logoColor=white&labelColor=1A1B27" />

</div>

<br/>

| Repository | 内容 | Status |
| :--- | :--- | :--- |
| [aws-amplify/amplify-data](https://github.com/aws-amplify/amplify-data/pull/768) | カスタムオペレーションで nullable なリスト引数が必須扱いになる不具合を修正 | **Merged** |
| [heavysixer/node-pptx](https://github.com/heavysixer/node-pptx) | ヘルパー関数のリファクタとドキュメント整備 | Open |
| [vuetifyjs/vuetify](https://github.com/vuetifyjs/vuetify) | `v-text-field` の clearable 併用時の挙動をバグレポート | Reported |

プロダクト開発で踏んだ不具合は、手元で回避策を書く前に上流へ直しに行くようにしています。

<div align="center">

<img src="https://img.shields.io/github/stars/rararax16?style=flat-square&logo=github&label=Total%20Stars&color=7AA2F7&labelColor=1A1B27" />
<img src="https://img.shields.io/badge/Achievements-Pull%20Shark%20%C2%B7%20Pair%20Extraordinaire-7AA2F7?style=flat-square&logo=github&labelColor=1A1B27" />

</div>

---

## Tech Stack

<div align="center">

**Main**

<img src="https://skillicons.dev/icons?i=ts,aws,react,nextjs,nodejs,swift,docker,git,github&theme=dark" />

<br/>

<img src="https://img.shields.io/badge/AWS%20Amplify-FF9900?style=flat-square&logo=awsamplify&logoColor=white" />
<img src="https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white" />
<img src="https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white" />
<img src="https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white" />
<img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white" />
<img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" />

<br/><br/>

**Also / Earlier**

<img src="https://skillicons.dev/icons?i=js,vue,nuxtjs,firebase,html,css,figma,notion&theme=dark" />

<br/>

<img src="https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=flat-square&logo=googleappsscript&logoColor=white" />
<img src="https://img.shields.io/badge/Budibase-000000?style=flat-square&logo=budibase&logoColor=white" />

</div>

---

## Pick Up

<table>
<tr>
<td width="50%" valign="top">

### [claude-code-meter](https://github.com/rararax16/claude-code-meter)

Claude Code の使用量を Mac のメニューバーに常駐表示する Swift 製アプリ。

<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" />
<img src="https://img.shields.io/github/stars/rararax16/claude-code-meter?style=flat-square&color=7AA2F7&labelColor=1A1B27" />
<img src="https://img.shields.io/github/last-commit/rararax16/claude-code-meter?style=flat-square&color=7AA2F7&labelColor=1A1B27" />

</td>
<td width="50%" valign="top">

### [react-twitter-clone](https://github.com/rararax16/react-twitter-clone)

React × Firebase で作った Twitter クローン。型と状態管理の整理を兼ねて書きました。

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [GAS-SNS-BOARD](https://github.com/rararax16/GAS-SNS-BOARD)

Google Workspace だけで完結する掲示板。2020年のものですが、いまも fork されています。

<img src="https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=flat-square&logo=googleappsscript&logoColor=white" />
<img src="https://img.shields.io/github/stars/rararax16/GAS-SNS-BOARD?style=flat-square&color=7AA2F7&labelColor=1A1B27" />
<img src="https://img.shields.io/github/forks/rararax16/GAS-SNS-BOARD?style=flat-square&color=7AA2F7&labelColor=1A1B27" />

</td>
<td width="50%" valign="top">

### [GAS-library](https://github.com/rararax16/GAS-library)

GAS でよく使う関数をまとめたもの。2019年、自動化の入り口でした。

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/github/stars/rararax16/GAS-library?style=flat-square&color=7AA2F7&labelColor=1A1B27" />

</td>
</tr>
</table>

---

## GitHub Stats

<div align="center">

<img src="https://img.shields.io/github/stars/rararax16?style=for-the-badge&logo=github&label=Stars&color=7AA2F7&labelColor=1A1B27" />
<img src="https://img.shields.io/github/followers/rararax16?style=for-the-badge&logo=github&label=Followers&color=7AA2F7&labelColor=1A1B27" />
<img src="https://img.shields.io/badge/Public%20Repos-8-7AA2F7?style=for-the-badge&logo=github&labelColor=1A1B27" />
<img src="https://img.shields.io/badge/On%20GitHub%20since-2018-7AA2F7?style=for-the-badge&logo=github&labelColor=1A1B27" />

</div>

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=rararax16&theme=tokyonight" width="98%" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=rararax16&theme=tokyonight" height="200" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=rararax16&theme=tokyonight" height="200" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=rararax16&theme=tokyonight" height="200" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=rararax16&theme=tokyonight&utcOffset=9" height="200" />

</div>

---

<div align="center">

<img src="https://komarev.com/ghpvc/?username=rararax16&style=flat-square&color=7AA2F7&label=Profile+Views" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%" />

</div>
