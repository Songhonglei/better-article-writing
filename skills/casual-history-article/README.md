# casual-history-article

> 用百姓家常话聊历史、宗教、地理、人物和流行文化，随意、休闲、轻松幽默，史实与出处守住底线。

适合历史闲聊、文化趣闻、由热点或旅行引出的历史话题，以及相关开头、结尾和配图文案的改写。像一个知道些来龙去脉的朋友，讲具体的人和事；默认不写成课文、专业文艺评论或博物馆导览。

## Features

- **家常话是默认口吻**：顺口、明白，不靠堆口头禅、模仿方言或固定网络梗制造亲切感。
- **内容丰富而不灌水**：围绕真实人物、行动、生活困难、细节和后续变化展开，不靠换类比或复述结论凑篇幅。
- **故事结构按题目选**：可以跟人、跟物或顺着好奇心推进，不固定章节数、纠错流程、回环或互动问题。
- **艺术品背后的人和事**：藏品用于讲制作、委托和流传故事，博物馆是证据来源，不必成为正文目录。
- **可靠事实与原创加工**：关键论断可追溯；区分事实、传说、虚构和推断，不编造亲历、对白与人物心思。
- **幽默有分寸**：笑意来自真实反差与叙述角度；苦难题可以平实亲近，不拿信徒、族群或受害者开玩笑。
- **正文计数有口径**：默认不含各级标题、备选标题和文末参考资料，统计可见字符并说明是否含标点，用户要求优先。
- **直接交付成稿**：参考资料简明放文末；素材卡和核验过程留在幕后，用户要求检查或报告时才展示。

## Quick Start

```bash
git clone https://github.com/Songhonglei/better-article-writing.git
# 将 skills/casual-history-article 复制到你的 Agent skills 目录
```

## Usage

详细要求见 [SKILL.md](./SKILL.md)。例如：

> 使用 $casual-history-article，用百姓家常话写一篇约 2,500 字的拿破仑历史闲聊文章，从他的帽子讲起。多讲真实趣事，不编造亲历和对白，字数只算正文，不含标题和参考资料。

用户只要求检查或方案时，先给结论与建议，确认后再修改；只改局部时，不擅自扩写全文。

## Install in your AI agent

| Agent | Install |
|---|---|
| Codex | 复制到 `~/.codex/skills/casual-history-article/` |
| WorkBuddy | 复制到 `~/.workbuddy/skills/casual-history-article/` |
| Claude Code | 复制到 `~/.claude/skills/casual-history-article/` |
| Cursor | 复制到 `.cursor/skills/casual-history-article/` |
| OpenClaw | 复制到你的 OpenClaw workspace 下的 `skills/casual-history-article/` |

按实际 Agent 的配置调整安装路径。

## License

MIT (see [LICENSE](./LICENSE))

## Author

Evan Song · [github.com/Songhonglei](https://github.com/Songhonglei)

## Changelog

See [CHANGELOG.md](./CHANGELOG.md) for the full version history.
