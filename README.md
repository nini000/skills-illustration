# skills-illustration
Claude skills for the illustration pipeline: concept brainstorm → Figma finishing

[中文](#中文) · [English](#english)


---


## 中文

產出插圖時使用的 Claude Skills，涵蓋流程中的第 1 步和第 3 步。

### 流程總覽

```
Step 01 概念發想  →  Step 02 Weavy 產圖  →  Step 03 Figma 收尾
   (Claude)              (手動)                 (Claude)
```

| Skill | 做什麼 |
|---|---|
| `illustration-step01-brainstorm` | 決定插圖要畫什麼物件或場景（只管概念，不管風格） |
| `illustration-step03-figma-finishing` | 在 Figma 裡完成收尾：Group、縮放、置中、加裝飾層、套 Portal／Admin 品牌色 |

### 安裝

1. 下載最新版本的檔案
2. Claude.ai → **Settings → Skills → Upload**，把兩個 zip 分別上傳

### 使用前提

| Skill | 需要 |
|---|---|
| Step 01 | 不需要其他設定 |
| Step 03 | ・帳號已連結 **Figma MCP connector**<br>・有 **Illustration Kit** 這個 Figma 檔案的存取權限 |

### 怎麼用

**Step 01 — 概念發想**
描述插圖的使用情境，然後說：
```
Prompt brainstorming
```

**Step 03 — Figma 收尾**
1. 把 Weavy 產出的 SVG 拖進 Figma
2. 選取這個節點
3. 依品牌輸入對應的指令：

| 指令 | 套用的品牌色 |
|---|---|
| `create Portal illustration` | Portal（`cp-sys-color`） |
| `create Admin illustration` | Admin（`ac-sys-color`） |

### 更新 Skill

> 更新不會自動同步，每個人都要手動換成新版。

**維護者**
1. 修改 `SKILL.md`
2. 重新打包成 zip
3. 發布新的 Release，附上 zip
4. 通知團隊

**使用者**
從 Releases 下載新版 zip，再到 Claude.ai 重新上傳。

---


## English

Claude Skills for the illustration pipeline. They cover Step 1 and Step 3 of the process.

### Pipeline

```
Step 01 Concept  →  Step 02 Weavy generation  →  Step 03 Figma finishing
   (Claude)              (manual)                     (Claude)
```

| Skill | What it does |
|---|---|
| `illustration-step01-brainstorm` | Decides what to draw: the objects or scene in the illustration. Concept only, not visual style. |
| `illustration-step03-figma-finishing` | Finishes the illustration in Figma: group, scale, center, add the decoration layers, and apply Portal/Admin brand colors. |

### Installation

1. Download files attached to the latest release.
2. In Claude.ai, go to **Settings → Skills → Upload** and upload each zip.

### Requirements

| Skill | Requires |
|---|---|
| Step 01 | Nothing extra |
| Step 03 | • **Figma MCP connector** linked to your account<br>• Access to the **Illustration Kit** Figma file |

### Usage

**Step 01 — Concept brainstorm**
Describe the scenario the illustration is for, then say:
```
Prompt brainstorming
```

**Step 03 — Figma finishing**
1. Drag the SVG from Weavy into Figma.
2. Select the node.
3. Run the command for your brand:

| Command | Brand colors |
|---|---|
| `create Portal illustration` | Portal (`cp-sys-color`) |
| `create Admin illustration` | Admin (`ac-sys-color`) |

### Updating

> Updates don't sync automatically. Everyone has to install the new version manually.

**Maintainer**
1. Edit `SKILL.md`.
2. Re-package it as a zip.
3. Publish a new Release with the zip attached.
4. Notify the team.

**Users**
Download the new zip from Releases and re-upload it in Claude.ai.
