# Blog

## About

[Xan's Blog](https://xancoding.github.io) Powered by [Hugo](https://gohugo.io/) & [PaperMod](https://github.com/adityatelange/hugo-PaperMod/)

## Install

```bash
sudo apt install hugo
```

## New Post

```bash
hugo new posts/title.md
```

## Serve

```bash
hugo serve -D
```

## Build

```bash 
# 生成 public 文件夹，可部署到云服务器或托管到 Github 上
# hugo # 只会往 public 文件夹里添加内容，但是不会删除外部已经不存在而 public 里面还存在的文件
hugo -F --cleanDestinationDir # 每次生成的public都是全新的，会覆盖原来的 
```

## Deploy

```bash
cd public
git add .
git commit -m "update"
git push
```
