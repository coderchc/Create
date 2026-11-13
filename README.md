# Create

## 运行陌生模型之前

运行陌生模型之前，先在你信任的环境里，把本仓库的 [`skills/llm-sec/SKILL.md`](skills/llm-sec/SKILL.md) 放到该 agent 会读取的 skills 目录，再运行陌生模型。不要让陌生模型自己装。装上之前的行为，skill 审查不到。

下面每行是核对过文档的一个例子：

- Cursor：`~/.cursor/skills/llm-sec/SKILL.md`。来源：[Agent Skills](https://cursor.com/docs/skills)
- Claude Code：`~/.claude/skills/llm-sec/SKILL.md`。来源：[Extend Claude with skills](https://code.claude.com/docs/en/skills)
- Codex：`~/.agents/skills/llm-sec/SKILL.md`。来源：[Build skills](https://learn.chatgpt.com/docs/build-skills)

其他产品放到该产品自己的 skills 目录。

## LLM-Sec 是什么

LLM-Sec 审查代理读了哪些文件、执行了哪些命令，以及权限有没有超出这次任务。监测只记录，防护才拦截。没有越界时，回复末尾是「LLM-Sec已监测」。
