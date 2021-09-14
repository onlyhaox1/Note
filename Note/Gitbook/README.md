# Gitbook基本使用

> GitBook 是一个基于 Node.js 的命令行工具，可使用 [Github](https://baike.baidu.com/item/Github)/Git 和 [Markdown](https://baike.baidu.com/item/Markdown) 来制作精美的电子书，GitBook 并非关于 [Git](https://baike.baidu.com/item/Git/12647237) 的教程。

### 1.安装cnpm

```shell
npm i cnpm -g
```

### 2.安装gitbook-cli

```shell
cnpm i gitbook-cli -g
```

## 3.初始化gitbook

```shell
gitbook init
```

### 4.创建book.json

```json
{
	"title" : "学习记录分享",
	"author": "炭烧章鱼",
	"version":"1",
	"links" : {
		"sidebar" : {
			"服务器推荐" : "http://mf.0220.cn/aff/NHVRNPLY"
		}
	},
	"language" : "zh-hans"
}
```

### 5.创建.ignore文件

```
*.bat
.ignore
_book
```

#### 6. 打包gitbook

```
gitbook build
```

#### 7. gitbook预览

```
gitbook serve
```

