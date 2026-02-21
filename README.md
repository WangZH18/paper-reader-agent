# Paper Reader Agent

一个用于 Claude Code 的学术论文阅读助手 Agent，帮助用户理解、分析和总结学术论文。

## 功能特点

- 结构化分析学术论文（背景、方法、实验、结论）
- 自动生成 Markdown 格式的论文解读文档
- 支持页码标注，方便回溯原文
- 维护论文索引，便于管理多篇论文
- 中文输出，技术术语双语呈现

## 安装

将 `paper-reader.md` 复制到 Claude Code 的 agents 目录：

```bash
# Windows
copy paper-reader.md %USERPROFILE%\.claude\agents\

# macOS/Linux
cp paper-reader.md ~/.claude/agents/
```

## 使用方法

在 Claude Code 中，当你需要分析论文时，agent 会自动被调用。示例：

- "帮我分析这篇论文"
- "这篇论文的主要贡献是什么？"
- "解释一下第3节的方法"

## 配置

默认输出路径为 `./output/`，可在 `paper-reader.md` 中修改 `保存路径` 配置。

## 许可证

MIT License
