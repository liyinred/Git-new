### .gitignore 
```bash
*.pyc
**/migrations/
**/__pycache__/
.env

# 忽略所有 Python 字节码编译文件（.pyc 文件）。
# 忽略项目中所有目录下名为 migrations 的文件夹（及其内容）。
# 略所有 __pycache__ 目录
# 忽略项目根目录（以及任意层级）的 .env 文件
```
## 单独提交 .gitignore 修改
```bash
git add .gitignore
git commit -m "chore(gitignore): exclude .env, __pycache__, and *.pyc"
```

```bash
# 查看工作区状态（已跟踪的 .pyc 修改会出现在 "Changes not staged for commit"）
git status

# 移除所有已跟踪的 .pyc 文件
git rm --cached -r -- '*.pyc'
git rm --cached .env
git rm --cached core/migrations/0001_initial.py

git status
git commit -m "chore(gitignore): stop tracking .env and .pyc files"

```
