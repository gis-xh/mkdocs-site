---
comments: false
---

# 基于 mkdocs-material 的静态网站模板



&emsp;&emsp;本网站是基于 mkdocs-material（MkDocs的Material Design主题）与 GitHub Page 实现网站显示和在线部署的，旨在提供一个可供快速使用的网站内容显示到发布一站式的模板。更多个性化设置，请参考完整文档 [mkdocs-material](https://squidfunk.github.io/mkdocs-material/)。



## 常用命令

* `mkdocs new [dir-name]` ：创建一个新项目

* `mkdocs serve`：启动实时加载的文档服务器

* `mkdocs build`：创建文档站点

* `mkdocs -h`：打印帮助信息并退出



## 项目文件布局


```
mkdocs.yml    		# 配置文件，所有网站配置都在这里
docs/
	mkdocs/
		overrides/	# 覆盖 mkdocs 网站的底层样式
		css/		# 放置额外的 css 文件
		js/			# 放置额外的 js 文件
    index.md		# 文档 Home 主页面
	.meta.yml		# 文件元数据设置
	...       		# 其他 markdown 页面，图片和其他文件
```



## 感谢

&emsp;&emsp;感谢美国田纳西州大学吴秋生老师的 geemap 官网与清华大学杨希杰同学的个人网站的内容，本模板是参考他们基于 mkdocs-material 部署的在线文档网站的内容与框架，并结合 [mkdocs-material](https://squidfunk.github.io/mkdocs-material/) 官网内容制作而成。

- Geemap官网：https://geemap.org/

- mkdocs-material 官网：https://squidfunk.github.io/mkdocs-material/

- 杨希杰的个人网站：https://yang-xijie.github.io/BLOG/Markdown/mkdocs-site/



