# GitHub 上传指南

## 使用命令行上传（需要已安装Git）

### 1. 打开命令行
- 按 `Win + R`
- 输入 `cmd` 回车
- 或者在项目文件夹右键 → Git Bash Here

### 2. 依次执行以下命令

```bash
# 进入项目目录
cd "e:\作品集全文件\打字软件\English-Speaking-Practice-Tool"

# 初始化Git仓库
git init

# 添加所有文件
git add .

# 提交
git commit -m "Initial commit: English Speaking Practice Tool v1.0"

# 设置主分支名为main
git branch -M main

# 连接到你的GitHub仓库（先在GitHub网站创建仓库）
git remote add origin https://github.com/你的用户名/English-Speaking-Practice-Tool.git

# 推送到GitHub
git push -u origin main
```

### 3. 输入GitHub账号密码
- 如果提示输入用户名和密码
- 密码需要使用Personal Access Token（不是登录密码）
- 获取Token: GitHub → Settings → Developer settings → Personal access tokens

## 启用在线访问

### 在GitHub仓库页面：
1. 点击 `Settings`
2. 左侧菜单找到 `Pages`
3. Source 选择 `main` 分支
4. 点击 `Save`
5. 等待1-2分钟，访问：`https://你的用户名.github.io/English-Speaking-Practice-Tool/`

✅ 完成！你的工具已经可以在线访问了！
