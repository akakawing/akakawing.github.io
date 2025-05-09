---
title: "Linux命令"
collection: posts
type: "posts"
date: 2025-02-24
location: "Hefei"
tag: it
---

## Git

Git配置设置

```bash
git config --global --list //查看配置设置
git config --global user.name YourUserName  //设置Username
git config --global user.email YourUserEmail  //设置UserEmail
```

Git 远程仓库连接查询

```bash
git remote -v
```

## Jekyll安装

1.先更新apt

```bash
sudo apt-get update
```
2.安装ruby

```bash
sudo apt-get install ruby-full build-essential zlib1g-dev
```
3.设置.bashrc文件

```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/
```
4.用gem安装jekyll和bundler
```bash
gem install jekyll bundler
```

5.更新bundle
```bash
bundle update
```

6.启动调试服务器
```bash
bundle exec jekyll serve
```


