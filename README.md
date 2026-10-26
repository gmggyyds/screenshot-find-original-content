<div align="center">

# screenshot-find-original-video

**截图、二创、搬运片 → 找回原视频。以画面为准，不靠标题猜。**

<p>
<img src="https://img.shields.io/badge/platform-YouTube_first-red" alt="YouTube first">
<img src="https://img.shields.io/badge/Douyin%20%2F%20X-stub-lightgrey" alt="Douyin X stub">
<img src="https://img.shields.io/badge/for-Grok_Bot_skill-black" alt="Grok Bot skill">
</p>

简体中文

</div>

---

## 📦 怎么用

这是给 Grok Bot（或同类助手）用的 **skill**，不是要装的 CLI。

1. 打开本仓里的 [`SKILL.md`](./SKILL.md)
2. 把它做成助手的 skill（或整仓交给会跑 skill 的 Bot）
3. 丢一张短视频截图 / 二创画面，说：「找到原视频」

直接说人话就行，例如：「这是视频号截的，帮我找回 YouTube 原片。」

---

## 🎯 它解决什么

| 没有它 | 有它 |
|---|---|
| 搜标题，找一堆「主题很像」的长视频 | 先对画面：人物、场景、道具、字幕时刻 |
| 用户说「画面不对」还继续推销同一条 | 否定即作废，换路径 |
| 把二创口播者当成原作者 | 分清画面源 vs 内容源 |

**成功标准只有一条：画面要对上。** 对不上就老实说，并单独标「内容源 ≠ 画面源」。

---

## 🧭 怎么跑（摘要）

完整步骤在 [`SKILL.md`](./SKILL.md)。主路径：

```
读截图 → 裁掉 UI → 以图搜图 → 线索检索（辅助）→ 视觉核验（必做）→ 定案
```

当前主力平台：**YouTube**（可带时间戳）。抖音 / 视频号、X 在 skill 文末预留，工具齐了再补。

---

## 📁 仓里有什么

| 文件 | 作用 |
|---|---|
| `SKILL.md` | 给助手执行的完整流程（正本） |
| `README.md` | 给人看的门面 |

---

## 🏁 说到底

**主题像不算找到。** 用户要的是那一镜，不是同赛道的另一条片。

**先画面，后文案。** 标题只是线索。

下次卡住时：裁一帧干净画面，丢给会跑这个 skill 的助手。

---

<div align="center">

**国民哥哥出品**

<sub>做的每一个东西，都是自己每天在用的</sub>

</div>
