# 个人网站模板快速构建



## 1 前提条件

- **Miniconda / Anaconda 环境**：用于本地部署环境的构建。如未安装请参考本篇内容进行安装：[Win11 安装配置 Miniconda 全过程记录 - 亚瑟的个人学习记录 (gis-xh.github.io)](https://gis-xh.github.io/my-note/python/01conda/Win11-Miniconda-install/)
- **Git 工具**：用于与 GitHub 进行交互。
- **Typora**：用于编写 Markdown 文件。
- **VS Code**：用于编辑和启动网站项目。
- **GitHub 账户**：网站是部署在 GitHub 上。



## 2 克隆项目

&emsp;&emsp;选择合适的目录，使用 Git 工具拉取模板仓库的所有代码。

```sh
git clone https://github.com/gis-xh/mkdocs-site.git
```



## 3 克隆虚拟环境

&emsp;&emsp;使用 conda 命令，以项目目录中的 `site_env.yaml` 文件内容为匹配，完整克隆网站项目创建时所用的开发环境。

```sh
conda env create -n my-site -f site_env.yaml
```



## 4 启动项目

&emsp;&emsp;在完整克隆开发环境后，激活虚拟环境即可在本地正常启动网站项目。

> 激活环境

```sh
conda activate my-site
```

> 启动项目

```sh
mkdocs serve
```

