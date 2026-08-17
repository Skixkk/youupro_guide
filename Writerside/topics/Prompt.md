# Prompt

## Common

- [技术栈选择](https://youupro.xyz/guide/test2.html)

### create

#### 必要一

```text
1.现在基于我的代码给出完整代码，只允许修改相关代码，不相干的代码，即使是注释也不能修改。代码中禁用 emoji ，
必要的图片需求使用 `src\static\images` 中的png图片
针对回复：给出代码即可，如有必要解释放在代码注释中

2.生成修改后的遵循Angular 提交规范的英文版 Git Commit Comments (English)：

<type>(<scope>): git-emoji <subject>
<BLANK LINE>
<body>（详细说明修改原因、逻辑、影响）
<BLANK LINE>
<footer>（关联Issue、关闭Bug等，如 "Fixes #123"）

```

#### 必要二

```text
1.现在基于我的代码给出完整代码，只允许修改相关代码，不相干的代码，即使是注释也不能修改。代码中禁用 emoji ，
必要的图片需求使用 `src\static\images` 中的png图片
针对回复：给出代码即可，如有必要解释放在代码注释中

2.生成修改后的遵循Angular 提交规范的英文版 Git Commit Comments (English)：

<type>(<scope>): git-emoji <subject>
<BLANK LINE>
<body>（详细说明修改原因、逻辑、影响）
<BLANK LINE>
<footer>（关联Issue、关闭Bug等，如 "Fixes #123"）

```

#### 分支命名方案（主干分支模式 Trunk‑Based Development）

```Text
使用 （主干分支模式 Trunk‑Based Development）

主干：`main`（唯一长期存活主干分支，禁止直接 push，必须走 PR）
所有开发都从 `main` 切短期功能分支，开发完合并回 main，用完删除
分支命名规范

格式：
`type/issueId‑short‑kebab‑case‑description`

使用主干分支，该 git commit 的新创建的分支名字为什么
```

#### 生成 Markdown 格式 PR 评审评论

> GitHub PR review comment

```Text
以代码的形式返回，Markdown 格式 PR 评审评论，符合 Pull request comment 规范

## PR Title:

## PR Description:

## Leave a comment

```

#### leave a commet

- [Github 常见缩写黑话](Github-LGTM.md)

### debug

```text
这是个 Django DRF PostgreSQL Redis celery 前后端分离saas多租户外卖小程序项目的后端部分

使用 django-tenants 实现多租户

现在基于我的代码给出完整代码，只允许修改相关代码，不相干的代码，即使是注释也不能修改。
针对回复：给出代码即可，如有必要解释放在代码注释中
```

```text
以注释的形式逐行解释代码
```

```text
完全复用 Customer 头像的删除逻辑实现对logo的图片的删除
```

```text
现在基于我的代码给出完整代码，只允许修改相关代码，不相干的代码，即使是注释也不能修改
```

```text
现在基于我的代码给出完整代码，只允许修改相关代码，不相干的代码，即使是注释也不能修改。
针对回复：给出代码即可，如有必要解释放在代码注释中
```

```text
现在基于我的代码给出完整代码，针对回复：给出代码即可，如有必要解释放在代码注释中
```

```text
新增需求：
实现在微信小程序中点击胶囊按钮上的三个点，在弹出的对话框中的【分享给好友】【分享到朋友圈】
```

```text
将tenants/models.py中的model注册到tenants/admin.py

1.现在基于我的代码给出完整代码，只允许修改相关代码，不相干的代码，即使是注释也不能修改。
针对回复：给出代码即可，如有必要解释放在代码注释中

2.生成修改后的遵循Angular 提交规范的英文版 Git Commit Comments (English)：

<type>(<scope>): <subject>
<BLANK LINE>
<body>（详细说明修改原因、逻辑、影响）
<BLANK LINE>
<footer>（关联Issue、关闭Bug等，如 "Fixes #123"）

```

```text
太简单，无法商用，将其写的专业些
```

```text
检查代码:
1.删除无用代码
2.合并重复代码
从而降低代码量和提高代码质量，而同时使得代码更优雅和逻辑清晰

所有代码，现在基于我的代码给出完整代码，只允许修改相关代码，不相干的代码，即使是注释也不能修改。
```

<seealso>
    <category ref="wrs">
        <a href="https://youupro.xyz/guide/starter-topic.html">Guide-首页</a>
        <a href="https://youupro.xyz/">返回主页</a>
    </category>
</seealso>