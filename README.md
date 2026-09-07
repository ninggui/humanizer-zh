# 中文去 AI 味

![GitHub stars](https://img.shields.io/github/stars/ninggui/humanizer-zh)
![License](https://img.shields.io/github/license/ninggui/humanizer-zh)
[![SkillHub](https://img.shields.io/badge/SkillHub-在线安装-blue)](https://skillhub.cn/skills/humanizer-zh)

去除文本中的 AI 写作痕迹，让文字读起来更像人类写作。

## 这是什么

一个可复用的 AI Agent 技能（Skill），来自真实业务场景沉淀，含完整执行流程、避坑清单与验证步骤。

## 快速使用

将本仓库放入 Agent 技能目录后，用对应触发词调用（见 SKILL.md），Agent 会自动加载并执行完整流程。

## 核心能力

| 能力 | 说明 |
|------|------|
| AI 高频词/结构/连接词检测 |
| 假靶子/堆叠副词修复 |
| 口语化改写 |

## 使用方式（安装）

- **Hermes**: 放入 `skills/` 目录
- **Claude**: 放入 `~/.claude/skills/`
- **其他 Agent**: 按对应 SKILL.md 格式放入技能目录
- **SkillHub 一键安装**: https://skillhub.cn/skills/humanizer-zh

## 优势

- 基于真实语料特征
- 保留原意不增修饰
- 适合小红书/公众号/日常输出

## 内容结构

- `SKILL.md` — 核心技能定义（触发条件、执行流程、避坑清单）
- `references/` — 可选参考文件

## 许可

MIT
