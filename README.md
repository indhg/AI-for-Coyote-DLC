<a id="top"></a>

<div align="center">

<h1>Coyote in Cradle · DLC</h1>
<p><strong>AI 角色扮演 × 郊狼（DG-Lab）—— 正式角色内容包（R18，自行导入）</strong></p>

<p>
  <a href="https://github.com/indhg/AI-for-Coyote-DLC/releases/latest"><img alt="Release" src="https://img.shields.io/badge/下载-内容包-orange?style=flat-square&logo=download"></a>
  <a href="LICENSE"><img alt="License" src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-green?style=flat-square"></a>
</p>

<p>
  <a href="#中文">中文</a> · <a href="#english">English</a>
</p>

<p><sub>18+ · 成人向 · 请在自愿、知情、同意的前提下使用</sub></p>

</div>

---

<a id="中文"></a>

## 🇨🇳 中文

## ⬇️ 下载导航

| 内容 | 下载 | 说明 |
|---|---|---|
| 🧩 **DLC-zh**（触手 / 品评会 中文稿） | 👉 [v0.4.2](https://github.com/indhg/AI-for-Coyote-DLC/releases/tag/v0.4.2) | 主程序 v1.1.6+；程序内「内容 / 语言包」一键导入 |
| 🧩 **DLC-en**（触手 / 品评会 英文稿） | 👉 [v0.4.1](https://github.com/indhg/AI-for-Coyote-DLC/releases/tag/v0.4.1) | 同上（需先装 DLC-zh 或用英文界面切换） |
| 🗺️ **紫金地牢 demo**（剧情包） | 👉 `releases/Coyote-in-Cradle-DLC-zijin-demo.zip` | 导入后生成 `content/pack/dungeon/zijin/`；需主程序含 dungeon_v2 |
| ⚠️ legacy（旧调教架构包） | 👉 [v0.1.8 / v0.2.0](https://github.com/indhg/AI-for-Coyote-DLC/releases) | **已过时**，仅适配旧版多档程序；v1.1.6+ 请勿使用 |

主程序（不含本仓库内容）：

| 端 | 下载 |
|---|---|
| 🖥️ **PC（Windows）** | 👉 <https://github.com/indhg/AI-for-Coyote/releases/latest> |
| 📱 **安卓（Android）** | 👉 <https://github.com/indhg/Coyote-in-Cradle-Android/releases/latest> |

---

## 🧩 内容清单

> 📁 **仓库结构**：仓库根为说明与许可；`releases/` 目录存放当前分发包（与下方 GitHub Releases 资产同一文件，二选一下载即可）。
> 📌 **角色**：当前正式角色仅 **触手 / 品评会**（哥布林 / 史莱姆 / 蛛后已回撤）。**地牢**：另发 `Coyote-in-Cradle-DLC-zijin-demo.zip`（紫金地牢 demo 剧情包）。

```
AI-for-Coyote-DLC/
├── README.md                     本说明
├── LICENSE                       许可（CC BY-NC 4.0）
└── releases/
    ├── Coyote-in-Cradle-DLC-zh-v1.1.6.zip   触手/品评会 中文稿（= DLC-zh v0.4.2）
    ├── Coyote-in-Cradle-DLC-en-v1.1.6.zip   触手/品评会 英文稿（= DLC-en v0.4.1）
    └── Coyote-in-Cradle-DLC-zijin-demo.zip  紫金地牢 demo 剧情包（content/pack/dungeon/zijin）
```

主程序 **v1.1.6+ 已内置**纯爱体验版（触手 · 纯爱向，中英双语，开箱即玩），**无需安装本仓库任何内容**。

本仓库提供的是 **2 个正式角色稿（R18）**，安装到程序目录后生成：

```
content/
├── roles/                         （角色 DLC）
│   ├── 触手-角色提示词.md
│   ├── 品评会-角色提示词.md
│   ├── 触手-角色提示词-EN.md
│   └── 品评会-角色提示词-EN.md
└── pack/dungeon/zijin/            （紫金地牢 demo 剧情包）
    ├── manifest.json
    ├── theme.json
    └── events/…
```

| 内容 | 分发形态 | 语言 |
|---|---|---|
| 体验版（触手 · 纯爱向） | ✅ 随主程序内置（content/pure），本仓库不含 | 中文 + 英文 |
| 触手 / 品评会（正式角色稿） | DLC-zh（v0.4.2） | 中文 |
| 上述角色英文稿 | DLC-en（v0.4.1） | 英文 |
| 紫金地牢 demo（剧情包） | `Coyote-in-Cradle-DLC-zijin-demo.zip` | 中文 |

---

## 📥 安装（主程序 v1.1.6+）

1. 下载对应 zip（见上方下载导航）；
2. 打开主程序 → 侧边栏底部 **「内容 / 语言包」→ 选择 zip 并安装**，自动合并进 `content/` 即时生效；
3. 或手动解压，把 zip 内 `content/…` 合并到程序目录的 `content/` 后重启。

安装完成后，角色入口（顶部角色卡 → 点击换入口）出现对应角色；**未导入的角色入口显示灰显「未导入」，导入后恢复正常**。

> 旧版主程序（v1.1.5 及更早）为多档架构，请使用 legacy 包（v0.1.8 / v0.2.0）；v1.1.6 起本仓库只维护 v0.4.x 结构。

---

## 📜 许可证

本仓库内容采用 **[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)**（见 [LICENSE](LICENSE)）：可免费使用、修改与分享，**须署名**，**禁止商业性使用**。

---

## 🙏 致谢与联系

- 反馈 / 建议 / 报错 → 主仓库 [issues](https://github.com/indhg/AI-for-Coyote/issues)
- 作者：<https://x.com/cinnanirch>

[回到顶部](#top)

---

<a id="english"></a>

## 🇬🇧 English

## ⬇️ Downloads

| Content | Download | Notes |
|---|---|---|
| 🧩 **DLC-zh**（Tentacle / Appraisal, Chinese） | 👉 [v0.4.2](https://github.com/indhg/AI-for-Coyote-DLC/releases/tag/v0.4.2) | Requires main app v1.1.6+; import in-app via “Content / language packs” |
| 🧩 **DLC-en**（Tentacle / Appraisal, English） | 👉 [v0.4.1](https://github.com/indhg/AI-for-Coyote-DLC/releases/tag/v0.4.1) | Same (install DLC-zh first or switch UI to EN) |
| ⚠️ legacy（old multi-tier packs） | 👉 [v0.1.8 / v0.2.0](https://github.com/indhg/AI-for-Coyote-DLC/releases) | **Outdated** — old multi-tier UI only; do not use on v1.1.6+ |

Main app (does not include this repo's content):

| Platform | Download |
|---|---|
| 🖥️ **PC (Windows)** | 👉 <https://github.com/indhg/AI-for-Coyote/releases/latest> |
| 📱 **Android** | 👉 <https://github.com/indhg/Coyote-in-Cradle-Android/releases/latest> |

## 🧩 Content

> 📁 **Repo layout**: the repo root holds docs & license only; the `releases/` folder holds the current packs (same files as the GitHub Releases assets below — grab them from either place).
> 📌 **2026-09-04 scope narrowed**: DLC now ships only two official roles — **Tentacle / Appraisal**. Goblin / Slime / Arachne were withdrawn with the old v0.4.1-era releases and are no longer provided.

```
AI-for-Coyote-DLC/
├── README.md                     This file
├── LICENSE                       License (CC BY-NC 4.0)
└── releases/
    ├── Coyote-in-Cradle-DLC-zh-v1.1.6.zip   Tentacle/Appraisal, Chinese (= DLC-zh v0.4.2)
    └── Coyote-in-Cradle-DLC-en-v1.1.6.zip   Tentacle/Appraisal, English (= DLC-en v0.4.1)
```

The main app **v1.1.6+ ships the Trial version built in**（Tentacle pure-love sample, ZH + EN, ready to play）— nothing from this repo is required to start.

This repo provides **2 official character scripts (R18)**. After install (content/ merged into the app dir):

```
content/
└── roles/
    ├── 触手-角色提示词.md          (DLC-zh)
    ├── 品评会-角色提示词.md        (DLC-zh)
    ├── 触手-角色提示词-EN.md       (DLC-en)
    └── 品评会-角色提示词-EN.md     (DLC-en)
```

| Content | Distribution | Language |
|---|---|---|
| Trial（Tentacle pure-love sample） | ✅ Built into the main app（content/pure）— not in this repo | Chinese + English |
| Tentacle / Appraisal（official roles） | DLC-zh（v0.4.2） | Chinese |
| English scripts of the above | DLC-en（v0.4.1） | English |

## 📥 Installation (main app v1.1.6+)

1. Download the zip you need (see above);
2. Open the app → sidebar footer **“Content / language packs” → pick the zip and install** — files are merged into `content/` and take effect immediately;
3. Or unzip manually and merge the `content/…` folder into the app's `content/`, then restart.

After install the roles appear in the role selector (top role card → switch entry); **unimported entries are greyed out with a “Not installed” badge until imported**.

> Older main app (≤ v1.1.5) used a multi-tier UI — use the legacy packs (v0.1.8 / v0.2.0). From v1.1.6 this repo only maintains the v0.4.x layout.

## 📜 License

This repository's content is under a **“CC BY-NC 4.0” license** (see [LICENSE](LICENSE)): free sharing and personal use are allowed (keep this notice and the author credit); **any profit-driven distribution, resale or paid hosting is prohibited**. Commercial licensing — contact the author.

## 🙏 Thanks & contact

- Feedback / issues → main repo [issues](https://github.com/indhg/AI-for-Coyote/issues)
- Author: <https://x.com/cinnanirch>

[Back to top](#top)
