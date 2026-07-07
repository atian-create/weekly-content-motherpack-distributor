# 每周内容母题分发 Skill

把你一周里和 Agent 聊过的内容、草稿、截图、灵感、评论、未完成选题，整理成 5 个可复用的「内容母题」，再根据不同平台生成对应的内容包。

这个 Skill 适合每天都会产生很多想法、但不想每次从零开始写内容的创作者。它的核心不是多写几篇文章，而是把一周的思考整理成一套可以反复分发的内容资产。

## 每周触发一次会发生什么？

当你触发这个 Skill 后，Agent 会帮你完成这几件事：

1. 回看这一周里有价值的对话、笔记、草稿、截图、评论和未发布内容。
2. 从里面选出 5 个最适合继续放大的内容母题。
3. 为每个母题整理清楚：写给谁、痛点是什么、核心判断是什么、能给读者什么结果。
4. 判断每个母题适合发到哪些平台。
5. 生成不同平台需要的内容，例如：
   - 小红书图文内容包
   - 公众号文章
   - 播客逐字稿
   - 短口播文案
   - 社群或 Newsletter 内容
   - 未来可以公开成 Skill 或开源项目的候选方向
6. 给出一份发布清单，让你知道哪些已经可以发，哪些还缺图片、审核或补充。

最后你得到的不是一堆零散标题，而是一周的「母题包 + 分发计划 + 发布检查表」。

## 一周从什么时候开始算？

有两种常见用法。

### 第一次运行

如果你没有指定日期范围，默认回看「触发当下往前 7 天」的内容。

例如你周日晚上第一次运行，它就会整理最近 7 天里最值得变成内容的素材。

### 每周定时运行

如果你想长期使用，建议给 Agent 下一个每周任务：

> 每周日晚上 8 点，使用这个 Skill 回看上次运行以来的内容，生成下周可用的 5 个内容母题，并分发成不同平台的内容包。

定时运行时，默认按「上一次运行结束后，到这一次运行时」作为一个内容周期。  
如果你更喜欢固定日历周，也可以让它按「周一到周日」或「周日到周六」来算。

## 一个母题怎么分发？

一个母题可以变成多种内容。

比如母题是：

> 标题一直改不动，可能不是标题问题，而是选题没定清楚。

它可以被分发成：

- 一篇小红书图文：讲标题、封面和点击理由怎么对齐；
- 一篇公众号：讲为什么内容系统比临时灵感更重要；
- 一篇播客：讲创作者为什么会卡在选题和表达之间；
- 一条短口播：用更口语的方式讲一个具体场景；
- 一个 Skill 候选：沉淀成标题判断或选题检查工作流。

## 推荐每周输出

一次标准运行建议输出：

```markdown
## 本周范围
...

## 5 个内容母题
| # | 母题 | 目标读者 | 核心痛点 | 适合分发的平台 |
| --- | --- | --- | --- | --- |

## 平台分发计划
| 母题 | 小红书 | 公众号 | 播客 | 短口播 | 备注 |
| --- | --- | --- | --- | --- | --- |

## 发布检查表
- 可以直接发：
- 需要补图片：
- 需要复审：
- 暂时不发：
```

## 图片能力说明

这个 Skill 可以规划图片内容，但是否能直接生成图片，取决于你当前使用的 Agent 有没有生图能力。

如果你的 Agent 支持生图：

- 可以生成小红书封面和图文页；
- 可以生成公众号封面和正文插图；
- 最好把图片和对应文案放在同一个交付文件夹里。

如果你的 Agent 不支持生图：

- 它仍然可以先生成标题、页面结构、图片说明和生图提示词；
- 图片项会被标记为 `needs images`；
- 你可以再搭配一个生图 Skill 来完成图片层。

如果你使用的是国内 Agent 环境，也可以安装灵造的生图 Skill/API，用它来补齐小红书封面、图文页和公众号配图。

特别注意：公众号的 HTML 只是用来复制正文和排版，不等于配图。公众号封面图、正文插图必须作为单独图片文件交付；如果没有独立图片包，就应该标记为「需要补图片」，不能用 HTML 截图或网页排版假装成配图。

如果你的工作流里有审核线程，建议把文字和图片分开审核：文章 Markdown/HTML 走文字审核，封面和插图文件夹走图片审核。两边都通过后，才标记为可以发布。

## 这个 Skill 不做什么

它不会自动替你发布内容，也不承诺流量、涨粉或成交。它更像一个每周内容操作台：帮你把一周的素材整理出来，选出值得继续放大的母题，再分发成不同平台能用的内容。

---

# Weekly Content Motherpack Distributor

Turn one week of conversations, notes, screenshots, drafts, and content-library material into five reusable mother topics, then distribute those topics into platform-ready content packages.

This is a creator workflow Skill. It is useful for people who talk to an Agent every day, save ideas everywhere, and then want one weekly planning run that turns the mess into publishable content.

## What It Does Each Week

When triggered, the Skill helps your Agent:

1. Review the week's useful conversations, drafts, notes, comments, screenshots, and unfinished ideas.
2. Select five mother topics.
3. Turn each mother topic into a clear content object: reader, pain, promise, key points, example, and risk.
4. Decide which platforms each topic fits.
5. Generate platform-ready outputs such as:
   - RedNote/Xiaohongshu graphic-note package
   - WeChat public-account article
   - podcast draft
   - short spoken script
   - newsletter/community post
   - public Skill or open-source candidate
6. Create a release checklist or release page so you know what is ready and what is still missing.

The goal is not to write random posts. The goal is to turn one week of thinking into five reusable topic assets.

## What Is A Mother Topic?

A mother topic is one reusable content source.

For example:

- "I keep changing titles because the topic is unclear."
- "My best content ideas are already hiding in my chat history."
- "A weekly content radar can turn comments and drafts into next week's tasks."

One mother topic can become:

- a RedNote/Xiaohongshu graphic note
- a WeChat article
- a podcast draft
- a short video script
- a community post
- a future Skill idea

## How The Weekly Window Works

There are two common modes.

### First Run

If you do not give a date range, the Skill uses the last seven days from the moment you start.

Example:

> Use this Skill to review my last 7 days and produce five mother topics.

### Scheduled Weekly Run

For recurring use, create a weekly task in your Agent:

> Every Sunday at 8 PM, use this Skill to review everything since the previous run, produce five mother topics for next week, and create platform-ready content packages.

In scheduled mode, the Skill should treat each run as one content week. The next run starts from the previous run's endpoint unless you tell it to use a calendar week such as Monday-Sunday.

## Recommended Output

A normal weekly run should return:

```markdown
## Weekly Range
...

## Five Mother Topics
| # | Mother Topic | Reader Pain | Why Now | Best Outputs |
| --- | --- | --- | --- | --- |

## Distribution Plan
| Mother Topic | RedNote | WeChat | Podcast | Short Script | Notes |
| --- | --- | --- | --- | --- | --- |

## Delivery Checklist
- Ready:
- Needs images:
- Needs review:
- Skipped:
```

If you want a publish-ready package, ask for a release folder or release page.

## Image Generation

This Skill can plan image assets even if your current model cannot generate images.

If your Agent has image generation:

- it can create RedNote/Xiaohongshu images;
- it can create WeChat cover and in-article images;
- it should put final images and captions together in the same delivery folder.

If your Agent does not have image generation:

- it should still create the topic, title, image plan, caption, and prompt;
- it should mark the item as `needs images`;
- you can pair this Skill with an image-generation Skill.

For Chinese/domestic Agent environments, you can install Lingzao's image-generation Skill/API and use it as the image layer for RedNote/Xiaohongshu covers, graphic-note pages, and WeChat article images.

For WeChat articles, HTML is only the copy-ready article layout. It is not a substitute for cover or in-article images. If images are promised, deliver separate image files and review them separately. If no valid image pack exists, mark the article as `needs images` instead of using HTML screenshots as images.

## Example Prompts

```text
Use $weekly-content-motherpack-distributor to review my last 7 days and give me five mother topics.
```

```text
Use $weekly-content-motherpack-distributor every Sunday night. Make five mother topics for next week and adapt them into RedNote, WeChat, podcast, and short-script outputs.
```

```text
Use $weekly-content-motherpack-distributor on this folder of drafts. Give me five mother topics first. Do not write platform versions until I confirm the topics.
```

## Boundaries

This Skill does not:

- publish automatically;
- guarantee views, followers, or sales;
- scrape private accounts;
- replace your final editorial judgment;
- expose private files or internal notes in public outputs.

It is a weekly content operating system: organize, select, distribute, and review.
