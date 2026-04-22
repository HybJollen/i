# ÉèÖÃ´úÀí
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
