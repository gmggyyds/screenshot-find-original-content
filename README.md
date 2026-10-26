<div align="center">

# screenshot-find-original-video

**截图、二创、搬运片 → 找回原片或原帖。以画面为准，不靠标题猜。**

<p>
<img src="https://img.shields.io/badge/YouTube-primary-red" alt="YouTube">
<img src="https://img.shields.io/badge/X-primary-black" alt="X">
<img src="https://img.shields.io/badge/Douyin-stub-lightgrey" alt="Douyin stub">
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

直接说人话就行，例如：「这是视频号截的，帮我找回原片。」

---

## 🎯 它解决什么

| 没有它 | 有它 |
|---|---|
| 搜标题，找一堆「主题很像」的长视频 | 先对画面：人物、场景、道具、字幕时刻 |
| 帧里是推文卡还去 YouTube 硬凑 | 认出 X UI → 直接搜原帖交链接 |
| 用户说「画面不对」还继续推销同一条 | 否定即作废，换路径 |

**成功标准：画面要对上。** 对不上就老实说，并单独标「内容源 ≠ 画面源」。

---

## 🧭 怎么跑（摘要）

完整步骤在 [`SKILL.md`](./SKILL.md)。

```
读截图 → 分流
  ├─ 帧里是 X/Twitter 推文卡 → 搜 X 原帖 → 定案
  └─ 实拍/口播/棚景 → 以图搜图 → YouTube 视觉核验 → 定案
```

抖音 / 视频号入口仍预留。

---

## 📁 仓里有什么

| 文件 | 作用 |
|---|---|
| `SKILL.md` | 给助手执行的完整流程（正本） |
| `README.md` | 给人看的门面 |

---

## 🏁 说到底

**主题像不算找到。** 用户要的是那一镜或那条原帖，不是同赛道的另一条片。

**先画面，后文案。** 标题只是线索。

---

<div align="center">

**国民哥哥出品**

<sub>做的每一个东西，都是自己每天在用的</sub>

</div>
