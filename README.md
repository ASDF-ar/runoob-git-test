# 1. 查看当前文件（Windows命令）
dir

# 2. 查看git状态
git status

# 3. 查看本地分支
git branch

# 4. 配置git用户信息（如果还没配置）
git config --global user.name "您的用户名"
git config --global user.email "3397784725@qq.com"

# 5. 提交更改
git commit -m "添加README文件"

# 6. 查看当前分支名，如果不是main，可以重命名或切换
# 如果当前分支是master，可以：
git branch -M main  # 重命名当前分支为main

# 7. 再次推送
git push -u origin main

# 1. 添加文件到暂存区
git add README.md

# 2. 提交更改
git commit -m "添加README文件"

# 3. 如果第一次提交后分支是master，重命名为main
git branch -M main

# 4. 推送到远程
git push -u origin main

git config --global --unset http.proxy
git config --global --unset https.proxy
git remote set-url origin git@github.com:ASDF-ar/runoob-git-test.git
git push -u origin main

方案一：清理代理并切换至SSH	1. 取消全局代理
2. 将远程仓库URL改为SSH格式	推荐。你的SSH密钥已验证可用，一劳永逸。
