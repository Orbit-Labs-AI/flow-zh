# 流水句（flow-zh）

让 AI 写中文更像人写的一个 Skill：用逗号把意思连起来，句子有长有短，助词写全，少用冒号，不用套话句式。正文在 [SKILL.md](SKILL.md)。

## 怎么用

一条命令安装（Claude Code、Codex、Cursor 等）：

```bash
npx skills add Orbit-Labs-AI/flow-zh
```

手动安装到 Claude Code：

```bash
git clone https://github.com/Orbit-Labs-AI/flow-zh.git ~/.claude/skills/flow-zh
```

不安装也能用：把 [SKILL.md](SKILL.md) 里的正文整段贴进对话或系统提示词，再让模型写作或改写。
