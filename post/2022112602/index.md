#  HUGO 写博客基础步骤和指令




## 步骤

基于 github 的 Hugo 静态博客 推送新博文 分为以下几步：

1. 用 hugo new 命令新建 md 文件

2. 用 hugo -D 生成 public html 文件

3. 前往 public 目录

4. 用 git add -A 命令将全部更新的文件添加到暂存区

5. 用 git commit 命令将暂存区内容添加到分支

6. 用 git push 命令将分支内容推到 github 上去

---

## 指令

1. `cd public`
2. `git add .`
3. `git commit -m "renew"`
4. `git pull --rebase origin main`
5. `git push`

---

## 报错

> [rejected]   master -> master (fetch first)    
error: failed to push some refs

解决

1. 在终端输入 `git pull --rebase origin main` 即可跟刚创建的线上远程仓库的默认分支main关联

2. 执行 `git push -u origin main` 即可将我们的项目文件上传到关联的线上远程文件中



master 切换到 main

> `git checkout -b main`




