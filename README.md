# xhs-content-compliance

A Claude Code Agent Skill for XHS (小红书) content compliance. Helps AI agents avoid banned words, traffic-limiting patterns, and platform policy violations when generating posts for the XHS platform.

## What it does

- Blocks absolute superlatives (最、第一、唯一、绝对 etc.)
- Avoids superstition-related terms that trigger content demotion (塔罗、占卜、星座 etc.)
- Prevents competitor platform mentions (抖音、B站、TikTok etc.)
- Provides a 72-word replacement table with safe alternatives
- Includes a pre-publish checklist for quick review
- Covers edge cases for tech/AI education content

## How to use

Add to Claude Code:

```
/skills add https://github.com/yifu-zhang/xhs-compliance-skill
```

Or reference directly in your project's `CLAUDE.md`:

```
Use the XHS content compliance skill when generating any content for the XHS platform.
```

## Skill file

[`xhs-content-compliance.md`](./xhs-content-compliance.md)

## Context

Built from 2026 XHS platform policy documentation and community-sourced banned word lists. Covers:

- 极限用语 (absolute superlatives)
- 权威背书词 (false authority claims)
- 迷信用语 (superstition terms)
- 诱导互动词 (engagement bait)
- 竞品平台词 (competitor mentions)
- 化妆品/医疗虚假宣传词 (false claims, cosmetics/medical)

Maintained by [@yifu-zhang](https://github.com/yifu-zhang).
