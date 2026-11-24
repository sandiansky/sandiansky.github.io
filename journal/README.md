# 发布新文章

1. 在 GitHub 仓库进入 [`_posts/`](https://github.com/sandiansky/sandiansky.github.io/tree/master/_posts)，点 **Add file → Create new file**。
2. 用「发布日期-英文短名.md」命名，例如 `2026-11-25-my-note.md`。
3. 粘贴下面的模板，修改标题、摘要和栏目，再用 Markdown 写正文。
4. 提交到 `master`。构建成功后，文章会出现在首页「最近更新」及对应栏目，也会进入文章归档。

```markdown
---
title: "文章标题"
description: "一句话摘要"
section: life
---

正文从这里开始。

## 小标题

下一段正文。
```

| `section` | 栏目 |
| --- | --- |
| `life` | 生活 |
| `work` | 工作 |
| `learning` | 学习 |

首页显示最新五篇。栏目和归档会列出更早的文章。[旧站归档](https://sandiansky.github.io/archives/)也保留在文章归档中。
