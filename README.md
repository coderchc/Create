# Create

## 运行陌生模型之前

运行陌生模型之前，先由你自己手动安装 LLM-Sec。不要让来路不明的模型自己安装。装上之前的行为，skill 审查不到。

自己把本仓库的 [`skills/llm-sec/SKILL.md`](skills/llm-sec/SKILL.md) 复制到本机 `~/.cursor/skills/llm-sec/SKILL.md`。这一步由你完成。装好之后，再运行那个模型。

## LLM-Sec 是什么

LLM-Sec 审查代理读了哪些文件、执行了哪些命令，以及权限有没有超出这次任务。监测只记录，防护才拦截。没有越界时，回复末尾是「LLM-Sec已监测」。
