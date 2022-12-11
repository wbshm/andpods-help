
### 官网文档
> https://hexo.io/zh-cn/docs/commands

### 创建文章：
> hexo new [layout] <title>
> hexo new post <title>

### 支持rsync部署 
`npm install hexo-deployer-rsync --save`


### 本地运行
```bash
hexo g && hexo s
```

### 部署命令
```bash
hexo clean && hexo deploy
# or
hexo g -d 
```

```bash
hexo clean && hexo g && cd ./en && hexo clean && hexo g && cd ../
```

### 测试
```shell
scp -r ./public/* 106.52.148.29:/usr/share/nginx/html/
```
### 部署到服务器
```bash
scp -r ./public/* www.andpods.cn:/data/www/help/
scp -r ./en/public/* www.andpods.cn:/data/www/help/en
```
