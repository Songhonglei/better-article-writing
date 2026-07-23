# better-article-writing

> 一组让 AI 写出更好文章的 skill 集合（中文场景为主）。

这个仓库收纳多个面向 AI 写作 Agent 的 skill，覆盖不同文体与场景。每个 skill 独立放在 `skills/` 子目录下，可单独复制到你自己的 Agent 中使用。

## 收录的 skills

| Skill | 说明 |
|---|---|
| [skills/casual-history-article](./skills/casual-history-article) | 把历史、宗教、地理、人物和流行文化写成有现场感、幽默克制且事实可核的中文微信公众号文章 |

后续会持续加入更多文体（如深度长文、产品文案、技术博客等），欢迎关注。

## 如何使用某个 skill

以 `casual-history-article` 为例：

```bash
git clone https://github.com/Songhonglei/better-article-writing.git
# 把 skills/casual-history-article 复制到你的 Agent skills 目录
cp -r better-article-writing/skills/casual-history-article ~/.workbuddy/skills/
```

各 skill 的安装路径见其自身 README。

## License

MIT — 见 [LICENSE](./LICENSE)。各 skill 目录内如另有 LICENSE 声明，以各自目录为准。

## Author

Evan Song · [github.com/Songhonglei](https://github.com/Songhonglei)
