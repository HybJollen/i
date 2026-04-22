# 设置代理
```
unset http_proxy https_proxy no_proxy HTTP_PROXY HTTPS_PROXY NO_PROXY
export http_proxy="http://10.10.8.201:12808" https_proxy="http://10.10.8.201:12808" no_proxy="localhost,127.0.0.1,.local,.internal" HTTP_PROXY="$http_proxy" HTTPS_PROXY="$https_proxy" NO_PROXY="$no_proxy"
```

# create a new repository on the command line
```
git config --global user.email "m3920752@qq.com"
git config --global user.name "HybJollen"

echo "# i" >> README.md
git init
git add README.md
git commit -m "first commit by Hyb260422"
git branch -M main
git remote add origin https://github.com/HybJollen/i.git
git push -u origin main
```

# push an existing repository from the command line
```
git remote add origin https://github.com/HybJollen/i.git
git branch -M main
git push -u origin main
```

# 将当前目录下的所有文件, 都提交上传到github
```
git add .                       # 将当前目录下的所有新文件和修改过的文件添加到 Git 的暂存区
git commit -m "add all files"   # 将暂存区的文件提交到本地仓库，并写上一条提交说明
git push                        # 将本地仓库的提交推送到 GitHub 远程仓库的 main 分支
```
