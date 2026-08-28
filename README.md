# AI for Coyote 内容包（DLC 系列）

> ⚠️ 成人内容（18+）：本仓库包含露骨的成人虚构文本，仅供成年人、双方自愿的虚构角色扮演使用。请遵守所在地区法律。

## 📦 相关仓库

本仓库是 **DLC 拓展仓库**，配套主仓库：

| 仓库 | 地址 |
|---|---|
| 🖥️ **PC 主仓库** | [indhg/AI-for-Coyote](https://github.com/indhg/AI-for-Coyote) |
| 📱 **安卓端** | [indhg/Coyote-in-Cradle-Android](https://github.com/indhg/Coyote-in-Cradle-Android) |

## 目录规范

每个 DLC 一个子目录，命名 `DLC<序号>-<名称>`，文件用「角色名-」前缀：

- `DLC1-触手-调教版/` —— 黑暗调教·支配胁迫
- `DLC2-xxx/` —— 预留

## 安装

### 🖥️ PC 桌面版

1. 先装主程序：到 [主仓库 Release](https://github.com/indhg/AI-for-Coyote/releases/latest) 下载安装（`Coyote-in-Cradle-setup-*.exe` ，或免装 zip 解压即用）；
2. 到本仓库 [Release](https://github.com/indhg/AI-for-Coyote-DLC/releases/latest) 下载 `Coyote-in-Cradle-DLC1.zip`；
3. 解压出 `DLC1-触手-调教版` 整个目录，放进主程序目录的 `content\pack\` 下（最终路径：`content\pack\DLC1-触手-调教版\触手-角色提示词-调教.md`）；
4. 打开 `config\character.yaml`，在 `profiles:` 的 `调教:` 下取消注释并指向：

   ```yaml
   调教:
     prompt_file: content/pack/DLC1-触手-调教版/触手-角色提示词-调教.md
   ```

5. 重启主程序，侧边栏切「调教」即用；没装好的 DLC 会显示「未装DLC」并被切换拦截。

### 📱 安卓 App

1. 到本仓库 Release 下载 `Coyote-in-Cradle-DLC1.zip`（或任意含「触手-角色提示词-调教.md」的 zip / 单个 .md）；
2. App 设置页 → 角色设置点「调教」→「导入调教版（选择 .zip 或 .md）」→ 选 zip；
3. 导入成功即点亮，切换即用。

## 免责声明

仅供成年用户自愿、知情、同意的前提下使用。使用本内容造成的任何后果由使用者自行承担，作者不承担任何责任。
