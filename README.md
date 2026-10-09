# Nox Study

这是一个浅色的 Typora 主题，主要用来写笔记、读笔记。

最初是为了让自己长时间看学习笔记时更舒服一点，陆续调整了正文宽度、标题、表格和代码块。现在索性整理出来，分享给有同样需求的人。

正文、大纲、引用和表格的实际效果：

![Nox Study 正文、大纲与表格预览](docs/images/overview.png)



## 样式

- 白色背景，深灰正文，阅读区域不会铺满整个窗口。
- 标题层级清楚，方便配合左侧大纲查看长笔记。
- 表格采用暖灰配色，引用和高亮用少量暖色点缀。
- 代码块采用炭灰背景，内置 JetBrains Mono 字体。



## 代码预览

![Nox Study 代码块与语法配色](docs/images/code.png)



## 使用教程

### 下载 ZIP

[下载源码 ZIP](https://github.com/AlgorithGeek/nox-study/archive/refs/heads/main.zip) 并解压。只想快速安装使用的话，选这个方式就好。

### 通过 Git 获取

如果想通过 Git 获取后续更新，长久快捷获取最新版，可以克隆仓库：

HTTPS（无需配置 SSH 密钥）：

```bash
git clone https://github.com/AlgorithGeek/nox-study.git
```

SSH（需要先在 GitHub 配置自己的 SSH 密钥）：

```bash
git clone git@github.com:AlgorithGeek/nox-study.git
```

后续在克隆的 `nox-study` 目录中执行 `git pull` 获取更新，再将主题文件重新复制到 Typora 的主题文件夹即可。

### 安装方式

两种方式获取的文件都可以按照下面的步骤安装：

1. 在软件 Typora 的「设置 / 偏好设置 → 外观」中打开主题文件夹。
2. 将项目中的 `nox-study.css` 文件和 `nox-study/` 文件夹一起复制进去。
3. 最后重启 Typora，在主题菜单中选择 **Nox Study**！

字体随主题附带，无需单独安装。`examples/` 文件夹不用复制到主题目录。

安装后，可以打开示例笔记 [从请求到响应](examples/从请求到响应.md)，看看实际效果。



## 说明

目前在 macOS / Typora 1.14.10 中使用，其他平台尚未测试。PDF 分页和 HTML 离线字体效果也还需要进一步检查。

显示问题可以通过 [Issues](https://github.com/AlgorithGeek/nox-study/issues) 反馈，请附上截图、操作系统和 Typora 版本。



## 许可

主题采用 [MIT License](LICENSE)。

内置 JetBrains Mono 字体采用 [SIL OFL 1.1](nox-study/OFL.txt)，相关信息见 [字体来源](nox-study/FONT-SOURCES.md)。
