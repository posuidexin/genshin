# GitHub 发布教程

## 网页上传方式

适合第一次发项目。

1. 打开 GitHub，点击右上角 `+` → `New repository`。
2. 仓库名建议填写：

   ```text
   genshin-bible-groupchat-skill
   ```

3. Description 可以写：

   ```text
   一个面向 AstrBot / 群聊 Bot 的原神圣经反串梗库 Skill。
   ```

4. 选择 `Public`。
5. 不要勾选自动生成 README，因为本项目已经带了 README。
6. 创建仓库后，点击 `uploading an existing file`。
7. 把本文件夹内的所有文件上传。
8. Commit message 填：

   ```text
   Initial release
   ```

9. 点击 `Commit changes`。

## 命令行上传方式

在本项目目录下执行：

```bash
git init
git add .
git commit -m "Initial release"
git branch -M main
git remote add origin https://github.com/<你的用户名>/genshin-bible-groupchat-skill.git
git push -u origin main
```

把 `<你的用户名>` 替换成你的 GitHub 用户名。

## 发布 Release

如果你希望别人直接下载 AstrBot 可导入包：

1. 进入 GitHub 仓库页面。
2. 点击右侧 `Releases`。
3. 点击 `Create a new release`。
4. Tag 填：

   ```text
   v1.1.0
   ```

5. Release title 填：

   ```text
   v1.1.0 - GitHub ready release
   ```

6. 附件上传可导入 ZIP，例如：

   ```text
   genshin-bible-groupchat-skill-github-ready.zip
   ```

7. 描述可以写：

   ```md
   ## 更新内容

   - 补充完整 README、安装教程和 GitHub 发布教程。
   - 增加推荐人格提示词。
   - 增加知识库搭配说明。
   - 增加输出限制：禁止动作、心理、旁白描写。
   - 保留 AstrBot Skill 标准结构：文件夹内含 SKILL.md。
   ```

8. 点击 `Publish release`。

## 推荐仓库简介

可以复制这段到 GitHub 仓库 About：

```text
一个面向 AstrBot / 群聊 Bot 的原神圣经反串梗库 Skill，适合搭配原神设定知识库使用。
```

推荐 Topics：

```text
astrbot, skill, genshin-impact, chatbot, groupchat, markdown, meme, chinese
```
