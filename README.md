# expression-gen · AI 人像表情生成 skill

让 AI 人像不再"摆拍脸"：用一串表情符号叠出「表面神态 + 内心情绪」，再翻译成眉眼嘴角的具体动作。可出单张，也可拼宫格对比图。

## 致谢 / 版权
提示词模板和 14 组表情预设来自 **VoxCat（[@VoxcatAI](https://x.com/VoxcatAI)）** 的文章：
[《为什么你的 AI 人像总像在摆拍？因为表情太老实了》](https://x.com/VoxcatAI/status/2111334367133847648)
模板与预设的版权归原作者所有。我只是把它整理成 agent 能直接用的 skill，补了使用流程（触发情境、宫格排版规则、禁止项、步骤）。原理和细节请看原文。

## 安装（有 agent 的话）
把整个 `expression-gen` 文件夹复制到你所用 agent 的 skills 目录：
- Claude Code：`~/.claude/skills/`
- Cursor、Codex 等支持 Agent Skills（SKILL.md）的工具：放到各自的 skills 目录，具体位置以官方文档为准

然后直接说"给这个人物出个委屈又得意的表情""挑4个表情拼一张2×2"即可。

## 不用 agent 也能用
打开 `SKILL.md`，把"提示词模板"复制出来，挑一组表情预设填进去，贴到 ChatGPT、Gemini 等任意生图工具里就行。文件里有一个填好的完整示例。

## 作者
整理：STY晒太阳 [@sty0603](https://x.com/sty0603)

---
**English summary:** An Agent Skill (SKILL.md) for generating portraits with nuanced, layered facial expressions, single image or grid. The prompt template and 14 expression presets are from VoxCat (@VoxcatAI)'s article (link above); copyright belongs to the original author. This package only adds the workflow. Install by copying the folder into your agent's skills directory (e.g. `~/.claude/skills/` for Claude Code), or just paste the template into any image generator.
