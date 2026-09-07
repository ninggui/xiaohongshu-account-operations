# 小红书账号运营（评论系统）

![GitHub stars](https://img.shields.io/github/stars/ninggui/xiaohongshu-account-operations)
![License](https://img.shields.io/github/license/ninggui/xiaohongshu-account-operations)
[![SkillHub](https://img.shields.io/badge/SkillHub-在线安装-blue)](https://skillhub.cn/skills/xiaohongshu-account-operations)

小红书账号评论运营通用框架：LLM 评论生成、频率安全、质量反馈闭环。

## 这是什么

一个可复用的 AI Agent 技能（Skill），来自真实业务场景沉淀，含完整执行流程、避坑清单与验证步骤。

## 快速使用

将本仓库放入 Agent 技能目录后，用对应触发词调用（见 SKILL.md），Agent 会自动加载并执行完整流程。

## 核心能力

| 能力 | 说明 |
|------|------|
| LLM 实时评论生成（读帖现写） |
| 人设与禁词独立配置 |
| 频率安全参数表 |
| 评论质量反馈闭环 |
| 自动回复 |

## 使用方式（安装）

- **Hermes**: 放入 `skills/` 目录
- **Claude**: 放入 `~/.claude/skills/`
- **其他 Agent**: 按对应 SKILL.md 格式放入技能目录
- **SkillHub 一键安装**: https://skillhub.cn/skills/xiaohongshu-account-operations

## 优势

- 全部参数来自真实运行实测
- 自动降频/解封检测机制
- 多账号隔离管理
- 脱敏方法论，无隐私

## 内容结构

- `SKILL.md` — 核心技能定义（触发条件、执行流程、避坑清单）
- `references/` — 可选参考文件

## 许可

MIT
