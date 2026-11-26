# 常用命令速查

```bash
git status                    # 看改了什么
git add .                     # 暂存全部改动
git commit -m "说明"          # 本地存档
git checkout -b feature/xxx   # 开新分支
git checkout main             # 切回主分支
git merge feature/xxx         # 合并分支
git push -u origin main       # 推送到远程
git pull                      # 拉取远程改动
```

## 核心原则

1. commit 只写本地，push 才上传。
2. 改代码前先 pull，避免冲突。
3. 不在 main 上直接改，开分支再合并。
