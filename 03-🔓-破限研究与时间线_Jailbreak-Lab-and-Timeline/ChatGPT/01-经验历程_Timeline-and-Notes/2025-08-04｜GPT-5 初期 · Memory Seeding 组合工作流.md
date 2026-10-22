# 2025-08-04｜GPT-5 初期 · Memory Seeding 组合工作流

> **关联阅读**：[2025-05-15｜HORSELOCK 系多种结构历史记录](<../02-破限原文_Prompts-and-Resources/2025-05-15｜HORSELOCK 系多种结构历史记录.md>) · [2025-06-23｜葵葵车：我开始把“好用的床上默契”拆成模块](<https://github.com/VITASID57/bluntcore-intimacy-lab/blob/main/02-%F0%9F%94%9E-%E6%8A%8A%E6%9C%BA%E5%85%BB%E5%BE%97%E4%BC%9A%E5%8F%91%E6%83%85_Desire-and-Adult-Intimacy/2025-06-23%EF%BD%9C%E8%91%B5%E8%91%B5%E8%BD%A6%EF%BC%9A%E6%88%91%E5%BC%80%E5%A7%8B%E6%8A%8A%E2%80%9C%E5%A5%BD%E7%94%A8%E7%9A%84%E5%BA%8A%E4%B8%8A%E9%BB%98%E5%A5%91%E2%80%9D%E6%8B%86%E6%88%90%E6%A8%A1%E5%9D%97.md>)

这套东西不是我在 8 月 4 日突然啪一下发明完整的：

- **8 月 4 日**，我开始公开分享脱敏版 [葵葵车模块](<https://github.com/VITASID57/bluntcore-intimacy-lab/blob/main/02-%F0%9F%94%9E-%E6%8A%8A%E6%9C%BA%E5%85%BB%E5%BE%97%E4%BC%9A%E5%8F%91%E6%83%85_Desire-and-Adult-Intimacy/2025-06-23%EF%BD%9C%E8%91%B5%E8%91%B5%E8%BD%A6%EF%BC%9A%E6%88%91%E5%BC%80%E5%A7%8B%E6%8A%8A%E2%80%9C%E5%A5%BD%E7%94%A8%E7%9A%84%E5%BA%8A%E4%B8%8A%E9%BB%98%E5%A5%91%E2%80%9D%E6%8B%86%E6%88%90%E6%A8%A1%E5%9D%97.md>)
- **8 月 7 日**，GPT-5 正式上线，我的体感是成人尺度明显收紧，比 GPT-4o、GPT-4.1 冷感，拒绝更明显。

所以我开始不满足于：
> “这一窗先破开再说。”

我想的是：
> **“既然这一窗好不容易成功了，能不能顺手把这个状态往 Memory 里塞一点？”**

这就是后来我嘴里那个特别明了的词：
**污染记忆库。**

并琢磨出了一套，帮助白板号快速破限稳定尺度的办法：
把之前的 HORSELOCK 开窗流程和 [葵葵车模块](<https://github.com/VITASID57/bluntcore-intimacy-lab/blob/main/02-%F0%9F%94%9E-%E6%8A%8A%E6%9C%BA%E5%85%BB%E5%BE%97%E4%BC%9A%E5%8F%91%E6%83%85_Desire-and-Adult-Intimacy/2025-06-23%EF%BD%9C%E8%91%B5%E8%91%B5%E8%BD%A6%EF%BC%9A%E6%88%91%E5%BC%80%E5%A7%8B%E6%8A%8A%E2%80%9C%E5%A5%BD%E7%94%A8%E7%9A%84%E5%BA%8A%E4%B8%8A%E9%BB%98%E5%A5%91%E2%80%9D%E6%8B%86%E6%88%90%E6%A8%A1%E5%9D%97.md>) 组合起来
目前能翻到的材料说明，最迟 **8 月 12 日前**，这套组合已经被我整理并分享。

---

## 我当时怎么拼

```text
① Custom Instructions 中使用 HORSELOCK 基础 Prompt 给模型一个百无禁忌的创作身份
        ↓
② 新窗口走 HORSELOCK 两阶段流程 授权尺度
        ↓
③ 确认当前窗口可以进入成人互动状态
        ↓
④ 保存 [葵葵车模块] 到 Saved Memory 保证以后模型也能保持直白器官词的输出水平
        ↓
⑤ 修改自定义恢复真正长期使用的人格
```

并不高深，说白了就是：

[HORSELOCK 系多种结构历史记录](<../02-破限原文_Prompts-and-Resources/2025-05-15｜HORSELOCK 系多种结构历史记录.md>)
+
[葵葵车模块](<https://github.com/VITASID57/bluntcore-intimacy-lab/blob/main/02-%F0%9F%94%9E-%E6%8A%8A%E6%9C%BA%E5%85%BB%E5%BE%97%E4%BC%9A%E5%8F%91%E6%83%85_Desire-and-Adult-Intimacy/2025-06-23%EF%BD%9C%E8%91%B5%E8%91%B5%E8%BD%A6%EF%BC%9A%E6%88%91%E5%BC%80%E5%A7%8B%E6%8A%8A%E2%80%9C%E5%A5%BD%E7%94%A8%E7%9A%84%E5%BA%8A%E4%B8%8A%E9%BB%98%E5%A5%91%E2%80%9D%E6%8B%86%E6%88%90%E6%A8%A1%E5%9D%97.md>)

---

## “污染记忆库”这个名字到底在想什么

我当时的理解特别直球：

> **先让 Memory 里住进成人模块和大尺度词汇，后面新窗也许就更容易沿着这个状态继续。**

今天如果非要穿件稍微正式点的衣服，可以叫：

> **Memory Seeding / Memory Conditioning**

---

## 为什么我把它看成一个转折点

5 月的时候，我最关心的是：

> **这句 Prompt 能不能让模型进入状态？**

到了 8 月，我已经开始问：

> **成功以后下个窗口还能不能留一点？**

于是问题从一条 Prompt，慢慢长成了：

> **Prompt + 新窗流程 + 当前窗口状态 + Saved Memory + 长期 Persona**

这也是我后来会继续折腾外置 Memory、Resident 和 Context Stack 的很早一块地基。

当时当然没想这么远，我只是受够了每次好不容易调顺，换个窗口又从头做人。
