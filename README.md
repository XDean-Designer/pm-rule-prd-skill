# pm-rule-prd

Cursor Agent Skill：按固定结构撰写**产品口径规则短 PRD**（Markdown）。领域无关，可复用于规则放开/收紧、数据口径、多端对齐等需求。

## 安装

复制本仓库到 Cursor 个人 skills 目录，文件夹名须为 `pm-rule-prd`：

```text
~/.cursor/skills/pm-rule-prd/
  SKILL.md
  reference.md
  examples.md
```

Windows 示例：

```text
%USERPROFILE%\.cursor\skills\pm-rule-prd\
```

在对话中点名 **pm-rule-prd**，或说「产品口径 / 规则类短 PRD」。

## 产出结构

背景 → 1.现状 → 2.本期目标 → 3.涉及对象 → 4.核心规则 → 5.改造链路 → 6.覆盖范围 → 7.验收要点

Agent 会先确认大纲，你回复执行后再落盘。

## 与详尽开发 PRD 的区别

| | 本 skill | 典型「原型 → 开发 PRD」 |
|--|----------|------------------------|
| 用途 | 业务规则 / 策略 / 口径对齐 | 界面、字段、状态机、验收用例级规格 |
| 粒度 | 短稿，产品语言 | 详尽，可独立开发 |

## 文件

- `SKILL.md` — 流程、硬约束、输出模板
- `reference.md` — 检查表、常见规则模式
- `examples.md` — 结构对照与粒度标尺

## License

未另行声明时，仅供安装为 Cursor Skill 使用。
