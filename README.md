# create a new repository on the command line
# 进入工程目录后，运行以下命令
echo "# hello_app" >> README.md
git init                      # 仓库初始化
git add README.md             # 添加文件到本地仓库
git commit -m "first commit"　# 提交变更的文本消息
git remote add origin git@github.com:liuguan/hello_app.git
git push -u origin master

# push an existing repository from the command line
# 进入工程目录后，运行以下命令
git remote add origin git@github.com:liuguan/hello_app.git
git push -u origin master

# 可以添加ssh key，免密登录。
# 测试ssh连接
# ssh -T git@github.com