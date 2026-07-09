# xhs-content-compliance

A Claude Code Agent Skill for XHS (小红书) content compliance. Helps AI agents avoid banned words, traffic-limiting patterns, and platform policy violations when generating posts for the XHS platform.

小红书内容合规 Agent Skill，帮助 AI Agent 在生成小红书笔记时自动规避违禁词、限流词和平台政策风险。

---

## What it does / 功能

- Blocks absolute superlatives (最、第一、唯一、绝对 etc.) — 拦截极限用语
- Avoids superstition-related terms that trigger content demotion (塔罗、占卜、星座 etc.) — 规避迷信词汇降权
- Prevents competitor platform mentions (抖音、B站、TikTok etc.) — 屏蔽竞品平台词
- Provides a 72-word replacement table with safe alternatives — 72个敏感词替换对照表
- Includes a pre-publish checklist for quick review — 发布前快速核验清单
- Covers edge cases for tech/AI education content — 覆盖技术/AI教学内容的特殊场景

---

## How to use / 使用方法

**Add to Claude Code / 添加到 Claude Code：**

```
/skills add https://github.com/yifu-zhang/xhs-compliance-skill
```

**Or reference in your project's `CLAUDE.md` / 或在项目 `CLAUDE.md` 中引用：**

```
Use the XHS content compliance skill when generating any content for the XHS platform.
生成小红书内容时，使用 xhs-content-compliance Skill 进行合规检查。
```

---

## Skill file / Skill 文件

[`xhs-content-compliance.md`](./xhs-content-compliance.md)

---

## Context / 背景

Built from 2026 XHS platform policy documentation and community-sourced banned word lists.

基于2026年小红书平台政策文档和社区整理的违禁词清单构建，涵盖：

- 极限用语 (absolute superlatives)
- 权威背书词 (false authority claims)
- 迷信用语 (superstition / fortune-telling terms)
- 诱导互动词 (engagement bait)
- 竞品平台词 (competitor platform mentions)
- 化妆品/医疗虚假宣传词 (false cosmetic/medical claims)

---

Maintained by [@yifu-zhang](https://github.com/yifu-zhang).
