# 飞书口述知识整理 Skill

把口述的想法、需求和复盘整理成飞书知识文档：用户表达，AI 整理并写入，用户自行修改并确认最终版。

## 适用场景

- 将口述想法、会议收获或工作复盘整理到飞书知识库。
- 根据现有目录选择合适位置，创建或更新相关文档。
- 用户修改并确认后读取最新版，以确认版为准。

## 安装

将本仓库克隆到 Codex 的技能目录：

```bash
git clone https://github.com/zhangxiaomeng1/feishu-voice-knowledge-workflow.git ~/.codex/skills/feishu-voice-knowledge-workflow
```

之后可在 Codex 中使用 `$feishu-voice-knowledge-workflow`，或直接提出相关整理需求。技能是否被自动发现取决于客户端配置，必要时重新打开会话。

## 前提和边界

技能是工作说明，不包含语音转写程序，也不自动运行。需要用户提供文字或由客户端提供转写，并配置有权限的飞书文档、知识库工具；本技能可配合可用的 `lark-doc`、`lark-wiki` 使用。没有飞书访问能力时，助手应说明并提供可复制的草稿，不应声称已写入。

只按用户授权读写。用户自行修改并确认后，以其最终版为准；后续如有新修改要求，应先读取最新版。

## 许可

[MIT](LICENSE)
