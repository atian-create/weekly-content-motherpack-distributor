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
